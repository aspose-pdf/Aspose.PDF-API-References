---
title: PdfViewer.CustomPrint
second_title: Aspose.PDF for .NET API Reference
description: PdfViewer イベント。印刷が開始される前に発生し、デフォルトのハンドラーの代わりにカスタム印刷ハンドラーを提供することを可能にします。
type: docs
weight: 200
url: /ja/net/aspose.pdf.facades/pdfviewer/customprint/
---
## PdfViewer.CustomPrint イベント

印刷が開始される前に発生し、デフォルトのハンドラーの代わりにカスタム印刷ハンドラーを提供することを可能にします。

```csharp
public event EventHandler<CustomPrintEventArgs> CustomPrint;
```

## 例

この例は、Linux システムで Aspose.PDF から印刷する方法を示しています。以下のコードは、主に Linux システムで Aspose.PDF から印刷することを目的としています。Windows システムのユーザーは、CustomPrint ハンドラーを提供せずにデフォルトの PdfViewer 印刷実装を引き続き使用できます。

### 前提条件

1. 印刷サーバーシステムに CUPS をインストールして構成する必要があります。
* sudo apt update && apt install cups
* sudo service cups start
* Aspose.PDF 対応アプリが実行されている同じシステムで文書を印刷する場合、追加の CUPS 構成は必要ありません。別のシステムから印刷する必要がある場合は、ネットワーク経由で印刷サーバーへのアクセスを許可する方法について CUPS ドキュメントを参照してください。
2. CUPS ウェブインターフェースを使用してプリンターを設定できます。オプションで、仮想 PDF プリンターを使用することもできます。
* sudo apt install printer-driver-cups-pdf
* sudo service cups restart
* 仮想 PDF プリンターが CUPS ウェブインターフェースの利用可能なプリンターのリストに表示されていることを確認してください（デフォルトの CUPS 設定で http://localhost:631/printers/ にて）。
3. クライアントシステム（Aspose.PDF 対応アプリが実行されている場所）が印刷サーバーと異なる場合、そこにも CUPS をインストールして実行する必要があります。
* sudo apt update && apt install cups
* sudo service cups start

### lp コマンドを使用して文書を印刷する方法

```csharp
var docPath = dataDir + "input.pdf";
var viewer = new PdfViewer();
viewer.BindPdf(docPath);

// Set a custom printing handler that builds an lp command and runs it with bash
viewer.CustomPrint += ViewerOnCustomPrintLp;

// Send the document to the virtual PDF printer installed with the printer-driver-cups-pdf package
var ps = new PrinterSettings
{
    PrinterName = "PDF"
};
var pgs = ps.DefaultPageSettings;
pgs.PaperSize = PaperSizes.A4;

// The document will be printed using the provided print handler
viewer.PrintDocumentWithSettings(pgs, ps);
viewer.Close();

// Custom print handler
private void ViewerOnCustomPrintLp(object sender, CustomPrintEventArgs e)
{
    var sb = new StringBuilder("lp ");
    // Set the name of the printer to print at
    sb.AppendFormat("-d {0} ", e.PrinterSettings.PrinterName);

    // Set the number of copies
    if (e.PrinterSettings.Copies > 0)
    {
        sb.AppendFormat("-n {0} ", e.PrinterSettings.Copies);
    }

    // Set the range of pages to print
    if (e.PrinterSettings.PrintRange == PrintRange.SomePages)
    {
        sb.AppendFormat("-P {0}-{1} ", e.PrinterSettings.FromPage, e.PrinterSettings.ToPage);
    }

    // Set paper size
    sb.AppendFormat("-o media={0} ", e.PageSettings.PaperSize.Kind.ToString("G").ToLower());

    // Set landscape orientation if requested
    if (e.PageSettings.Landscape)
    {
        sb.Append("-o orientation-requested=4 ");
    }

    // Set printer resolution
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

    // Set two-sided print if requested
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

    // The name of the file to print
    sb.AppendFormat("-- {0} ", e.FileName);

    // Run the prepared lp command with bash
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

### ipptool を使用して文書を印刷する方法

```csharp
var docPath = dataDir + "input.pdf";
var viewer = new PdfViewer();
viewer.BindPdf(docPath);

// Set a custom printing handler that builds an ipptool job file and runs ipptool with bash
viewer.CustomPrint += ViewerOnCustomPrintIpptool;

// Send the document to the virtual PDF printer installed with the printer-driver-cups-pdf package
var ps = new PrinterSettings
{
    PrinterUri = new Uri("ipp://localhost/printers/PDF");
};
var pgs = ps.DefaultPageSettings;
pgs.PaperSize = PaperSizes.A4;

// The document will be printed using the provided print handler
viewer.PrintDocumentWithSettings(pgs, ps);
viewer.Close();

// Custom print handler
private void ViewerOnCustomPrintIpptool(object sender, CustomPrintEventArgs e)
{
    var command = new StringBuilder("ipptool -tv ");

    // The name of the file to print
    command.AppendFormat("-f {0} ", e.FileName);

    // Set the URI of the printer to print at
    command.Append(e.PrinterSettings.PrinterUri);

    // Get the temporary file name for the ipptool job file
    var jobFile = Path.GetTempFileName();

    var sb = new StringBuilder();
    sb.AppendLine("{");

    // Set job name and type of the job
    sb.AppendLine("  NAME \"Print file using Print-Job\"");
    sb.AppendLine("  OPERATION Print-Job");

    // Set default job settings
    sb.AppendLine("  GROUP operation-attributes-tag");
    sb.AppendLine("  ATTR charset attributes-charset utf-8");
    sb.AppendLine("  ATTR language attributes-natural-language en");
    sb.AppendLine("  ATTR uri printer-uri $uri");
    sb.AppendLine("  ATTR name requesting-user-name $user");
    sb.AppendLine("  ATTR mimeMediaType document-format $filetype");

    sb.AppendLine("  GROUP job-attributes-tag");

    // Set number of copies
    var copies = e.PrinterSettings.Copies < 1 ? 1 : e.PrinterSettings.Copies;
    sb.AppendFormat("  ATTR integer copies {0}{1}", copies, Environment.NewLine);

    sb.AppendLine("  ATTR collection media-col {");
    // Set paper size
    sb.AppendLine("    MEMBER collection media-size {");
    // .NET uses 1/100th of inch to represent paper size while IPP requires 1/1000th of millimeter - conversion is needed
    sb.AppendFormat("      MEMBER integer x-dimension {0}{1}", (int) (e.PageSettings.PaperSize.Width * 25.4),
        Environment.NewLine);
    sb.AppendFormat("      MEMBER integer y-dimension {0}{1}", (int) (e.PageSettings.PaperSize.Height * 25.4),
        Environment.NewLine);
    sb.AppendLine("    }");

    // Set margins
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

    // Create ipptool job file
    File.WriteAllText(jobFile, sb.ToString());

    // Pass the job file to ipptool
    command.AppendFormat(" {0}", jobFile);

    // Run the prepared ipptool command with bash
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

    // Delete temporary job file after the document is printed
    File.Delete(jobFile);
}
```

### 関連項目

* class [CustomPrintEventArgs](../../../aspose.pdf.printing/customprinteventargs/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)