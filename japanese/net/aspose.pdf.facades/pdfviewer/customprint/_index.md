---
title: "PdfViewer.CustomPrint"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfViewer イベント。印刷開始前に発生し、デフォルトのハンドラの代わりにカスタム印刷ハンドラを提供できます"
type: docs
weight: 200
url: /ja/net/aspose.pdf.facades/pdfviewer/customprint/
---
## PdfViewer.CustomPrint event

印刷が開始される前に発生し、デフォルトのハンドラの代わりにカスタム印刷ハンドラを提供できるようにします。

```csharp
public event EventHandler<CustomPrintEventArgs> CustomPrint;
```

## 例

この例は Linux システム上で Aspose.PDF から印刷する方法を示しています。以下のコードは主に Linux システム上で Aspose.PDF から印刷することを目的としています。Windows システムのユーザーは、CustomPrint ハンドラを提供せずにデフォルトの PdfViewer 印刷実装を引き続き使用できます

### Prerequisites

1. 印刷サーバーシステムに CUPS をインストールし、設定する必要があります：
* sudo apt update && apt install cups
* sudo service cups start
* if you're going to print documents on the same system where the Aspose.PDF-enabled app is running, you won't need additional CUPS configuration. If you need to print from a different system, please refer to the CUPS documentation on how to allow access to print server via the network.
2. CUPS のウェブインターフェイスを使用してプリンターを設定できます。必要に応じて、仮想 PDF プリンターを使用することもできます：
* sudo apt install printer-driver-cups-pdf
* sudo service cups restart
* please make sure that the virtual PDF printer appeared in the list of available printers in the CUPS web interface (at http://localhost:631/printers/ with default CUPS settings)
3. クライアントシステム（Aspose.PDF 対応アプリが実行されている場所）が印刷サーバーと異なる場合、そこでも CUPS をインストールして実行する必要があります：
* sudo apt update && apt install cups
* sudo service cups start

### How to print a document using the lp command

```csharp
var docPath = dataDir + "input.pdf";
var viewer = new PdfViewer();
viewer.BindPdf(docPath);

// lp コマンドを構築し、bash で実行するカスタム印刷ハンドラを設定します
viewer.CustomPrint += ViewerOnCustomPrintLp;

// printer-driver-cups-pdf パッケージでインストールされた仮想 PDF プリンターにドキュメントを送信します
var ps = new PrinterSettings
{
    PrinterName = "PDF"
};
var pgs = ps.DefaultPageSettings;
pgs.PaperSize = PaperSizes.A4;

// ドキュメントは提供された印刷ハンドラを使用して印刷されます
viewer.PrintDocumentWithSettings(pgs, ps);
viewer.Close();

// カスタム印刷ハンドラ
private void ViewerOnCustomPrintLp(object sender, CustomPrintEventArgs e)
{
    var sb = new StringBuilder("lp ");
    // 印刷先プリンターの名前を設定します
    sb.AppendFormat("-d {0} ", e.PrinterSettings.PrinterName);

    // コピー数を設定します
    if (e.PrinterSettings.Copies > 0)
    {
        sb.AppendFormat("-n {0} ", e.PrinterSettings.Copies);
    }

    // 印刷するページ範囲を設定します
    if (e.PrinterSettings.PrintRange == PrintRange.SomePages)
    {
        sb.AppendFormat("-P {0}-{1} ", e.PrinterSettings.FromPage, e.PrinterSettings.ToPage);
    }

    // 用紙サイズを設定する
    sb.AppendFormat("-o media={0} ", e.PageSettings.PaperSize.Kind.ToString("G").ToLower());

    // 要求があれば横向きに設定する
    if (e.PageSettings.Landscape)
    {
        sb.Append("-o orientation-requested=4 ");
    }

    // プリンターの解像度を設定する
    switch (e.PageSettings.PrinterResolution.Kind)
    {
        case PrinterResolutionKind.High:
            sb.Append("-o print-quality=5 ");
            break;

        case PrinterResolutionKind.Medium:
            sb.Append("-o print-quality=4 ");
            break;

        case PrinterResolutionKind.Draft:
            sb.Append("-o print-quality=3 ");
            break;
    }

    // 要求があれば両面印刷を設定する
    switch (e.PrinterSettings.Duplex)
    {
        case Duplex.Simplex:
            sb.Append("-o sides=one-sided ");
            break;

        case Duplex.Vertical:
            sb.Append("-o sides=two-sided-short-edge ");
            break;

        case Duplex.Horizontal:
            sb.Append("-o sides=two-sided-long-edge ");
            break;
    }

    // 印刷するファイルの名前
    sb.AppendFormat("-- {0} ", e.FileName);

    // 準備した lp コマンドを bash で実行する
    var psi = new ProcessStartInfo
    {
        FileName = "/bin/bash",
        Arguments = string.Format("-c \"{0}\"", sb.ToString()),
        RedirectStandardOutput = true,
        UseShellExecute = false,
        CreateNoWindow = true
    };

    using (var process = Process.Start(psi))
    {
        process.WaitForExit();
    }
}
```

### How to print a document using the ipptool

```csharp
var docPath = dataDir + "input.pdf";
var viewer = new PdfViewer();
viewer.BindPdf(docPath);

// ipptool ジョブファイルを作成し、bash で ipptool を実行するカスタム印刷ハンドラを設定する
viewer.CustomPrint += ViewerOnCustomPrintIpptool;

// printer-driver-cups-pdf パッケージでインストールされた仮想 PDF プリンターにドキュメントを送信します
var ps = new PrinterSettings
{
    PrinterUri = new Uri("ipp://localhost/printers/PDF");
};
var pgs = ps.DefaultPageSettings;
pgs.PaperSize = PaperSizes.A4;

// ドキュメントは提供された印刷ハンドラを使用して印刷されます
viewer.PrintDocumentWithSettings(pgs, ps);
viewer.Close();

// カスタム印刷ハンドラ
private void ViewerOnCustomPrintIpptool(object sender, CustomPrintEventArgs e)
{
    var command = new StringBuilder("ipptool -tv ");

    // 印刷するファイルの名前
    command.AppendFormat("-f {0} ", e.FileName);

    // 印刷先プリンターの URI を設定する
    command.Append(e.PrinterSettings.PrinterUri);

    // ipptool ジョブファイルの一時ファイル名を取得する
    var jobFile = Path.GetTempFileName();

    var sb = new StringBuilder();
    sb.AppendLine("{");

    // ジョブ名とジョブの種類を設定する
    sb.AppendLine("  NAME \"Print file using Print-Job\"");
    sb.AppendLine("  OPERATION Print-Job");

    // デフォルトのジョブ設定を行う
    sb.AppendLine("  GROUP operation-attributes-tag");
    sb.AppendLine("  ATTR charset attributes-charset utf-8");
    sb.AppendLine("  ATTR language attributes-natural-language en");
    sb.AppendLine("  ATTR uri printer-uri $uri");
    sb.AppendLine("  ATTR name requesting-user-name $user");
    sb.AppendLine("  ATTR mimeMediaType document-format $filetype");

    sb.AppendLine("  GROUP job-attributes-tag");

    // コピー数を設定する
    var copies = e.PrinterSettings.Copies < 1 ? 1 : e.PrinterSettings.Copies;
    sb.AppendFormat("  ATTR integer copies {0}{1}", copies, Environment.NewLine);

    sb.AppendLine("  ATTR collection media-col {");
    // 用紙サイズを設定する
    sb.AppendLine("    MEMBER collection media-size {");
    // .NET は用紙サイズをインチの 1/100 で表し、IPP はミリメートルの 1/1000 を要求します - 変換が必要です
    sb.AppendFormat("      MEMBER integer x-dimension {0}{1}", (int) (e.PageSettings.PaperSize.Width * 25.4),
        Environment.NewLine);
    sb.AppendFormat("      MEMBER integer y-dimension {0}{1}", (int) (e.PageSettings.PaperSize.Height * 25.4),
        Environment.NewLine);
    sb.AppendLine("    }");

    // 余白を設定する
    if (pageSettings.Margins != null)
    {
        sb.AppendFormat("    MEMBER integer media-top-margin {0}{1}", (int) (e.PageSettings.Margins.Top * 25.4),
            Environment.NewLine);
        sb.AppendFormat("    MEMBER integer media-bottom-margin {0}{1}", (int) (e.PageSettings.Margins.Bottom * 25.4),
            Environment.NewLine);
        sb.AppendFormat("    MEMBER integer media-left-margin {0}{1}", (int) (e.PageSettings.Margins.Left * 25.4),
            Environment.NewLine);
        sb.AppendFormat("    MEMBER integer media-top-margin {0}{1}", (int) (e.PageSettings.Margins.Right * 25.4),
            Environment.NewLine);
    }

    sb.AppendLine("    MEMBER keyword media-source \"main\"");
    sb.AppendLine("    MEMBER keyword media-type \"stationery\"");
    sb.AppendLine("  }");

    sb.AppendLine("  FILE $filename");
    sb.AppendLine("  STATUS successful-ok");
    sb.AppendLine("  STATUS successful-ok-ignored-or-substituted-attributes");
    sb.AppendLine("  EXPECT job-id");
    sb.AppendLine("  EXPECT job-uri");
    sb.AppendLine("}");

    // ipptool ジョブファイルを作成する
    File.WriteAllText(jobFile, sb.ToString());

    // ジョブファイルを ipptool に渡す
    command.AppendFormat(" {0}", jobFile);

    // 準備した ipptool コマンドを bash で実行する
    var psi = new ProcessStartInfo
    {
        FileName = "/bin/bash",
        Arguments = string.Format("-c \"{0}\"", command.ToString()),
        RedirectStandardOutput = true,
        UseShellExecute = false,
        CreateNoWindow = true
    };

    using (var process = Process.Start(psi))
    {
        process.WaitForExit();
    }

    // ドキュメントが印刷された後、一時ジョブファイルを削除する
    File.Delete(jobFile);
}
```

### 関連項目

* class [CustomPrintEventArgs](../../../aspose.pdf.printing/customprinteventargs/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


