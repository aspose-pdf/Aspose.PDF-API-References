---
title: "PdfViewer.CustomPrint"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfViewer 이벤트. 인쇄가 시작되기 전에 발생하며 기본 핸들러 대신 사용자 정의 인쇄 핸들러를 제공할 수 있습니다"
type: docs
weight: 200
url: /ko/net/aspose.pdf.facades/pdfviewer/customprint/
---
## PdfViewer.CustomPrint event

인쇄가 시작되기 전에 발생하며 기본 핸들러 대신 사용자 정의 인쇄 핸들러를 제공할 수 있습니다.

```csharp
public event EventHandler<CustomPrintEventArgs> CustomPrint;
```

## 예제

이 예제는 Linux 시스템에서 Aspose.PDF를 사용하여 인쇄하는 방법을 보여줍니다. 다음 코드는 주로 Linux 시스템에서 Aspose.PDF를 사용한 인쇄를 목표로 합니다. Windows 시스템 사용자는 CustomPrint 핸들러를 제공하지 않고도 기본 PdfViewer 인쇄 구현을 계속 사용할 수 있습니다.

### Prerequisites

1. 인쇄 서버 시스템에 CUPS를 설치하고 구성해야 합니다:
* sudo apt update && apt install cups
* sudo service cups start
* if you're going to print documents on the same system where the Aspose.PDF-enabled app is running, you won't need additional CUPS configuration. If you need to print from a different system, please refer to the CUPS documentation on how to allow access to print server via the network.
2. CUPS 웹 인터페이스를 사용하여 프린터를 설정할 수 있습니다. 필요에 따라 가상 PDF 프린터를 사용할 수 있습니다:
* sudo apt install printer-driver-cups-pdf
* sudo service cups restart
* please make sure that the virtual PDF printer appeared in the list of available printers in the CUPS web interface (at http://localhost:631/printers/ with default CUPS settings)
3. 클라이언트 시스템(Aspose.PDF가 활성화된 앱이 실행되는 곳)이 인쇄 서버와 다르면 해당 시스템에도 CUPS를 설치하고 실행해야 합니다:
* sudo apt update && apt install cups
* sudo service cups start

### How to print a document using the lp command

```csharp
var docPath = dataDir + "input.pdf";
var viewer = new PdfViewer();
viewer.BindPdf(docPath);

// lp 명령을 생성하고 bash로 실행하는 사용자 정의 인쇄 핸들러를 설정합니다
viewer.CustomPrint += ViewerOnCustomPrintLp;

// printer-driver-cups-pdf 패키지로 설치된 가상 PDF 프린터에 문서를 보냅니다
var ps = new PrinterSettings
{
    PrinterName = "PDF"
};
var pgs = ps.DefaultPageSettings;
pgs.PaperSize = PaperSizes.A4;

// 문서는 제공된 인쇄 핸들러를 사용하여 인쇄됩니다
viewer.PrintDocumentWithSettings(pgs, ps);
viewer.Close();

// 사용자 정의 인쇄 핸들러
private void ViewerOnCustomPrintLp(object sender, CustomPrintEventArgs e)
{
    var sb = new StringBuilder("lp ");
    // 인쇄할 프린터 이름을 설정합니다
    sb.AppendFormat("-d {0} ", e.PrinterSettings.PrinterName);

    // 복사 수를 설정합니다
    if (e.PrinterSettings.Copies > 0)
    {
        sb.AppendFormat("-n {0} ", e.PrinterSettings.Copies);
    }

    // 인쇄할 페이지 범위를 설정합니다
    if (e.PrinterSettings.PrintRange == PrintRange.SomePages)
    {
        sb.AppendFormat("-P {0}-{1} ", e.PrinterSettings.FromPage, e.PrinterSettings.ToPage);
    }

    // 용지 크기 설정
    sb.AppendFormat("-o media={0} ", e.PageSettings.PaperSize.Kind.ToString("G").ToLower());

    // 요청 시 가로 방향으로 설정
    if (e.PageSettings.Landscape)
    {
        sb.Append("-o orientation-requested=4 ");
    }

    // 프린터 해상도 설정
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

    // 요청 시 양면 인쇄 설정
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

    // 인쇄할 파일 이름
    sb.AppendFormat("-- {0} ", e.FileName);

    // 준비된 lp 명령을 bash로 실행
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

// ipptool 작업 파일을 생성하고 bash로 ipptool을 실행하는 사용자 지정 인쇄 핸들러 설정
viewer.CustomPrint += ViewerOnCustomPrintIpptool;

// printer-driver-cups-pdf 패키지로 설치된 가상 PDF 프린터에 문서를 보냅니다
var ps = new PrinterSettings
{
    PrinterUri = new Uri("ipp://localhost/printers/PDF");
};
var pgs = ps.DefaultPageSettings;
pgs.PaperSize = PaperSizes.A4;

// 문서는 제공된 인쇄 핸들러를 사용하여 인쇄됩니다
viewer.PrintDocumentWithSettings(pgs, ps);
viewer.Close();

// 사용자 정의 인쇄 핸들러
private void ViewerOnCustomPrintIpptool(object sender, CustomPrintEventArgs e)
{
    var command = new StringBuilder("ipptool -tv ");

    // 인쇄할 파일 이름
    command.AppendFormat("-f {0} ", e.FileName);

    // 인쇄할 프린터의 URI 설정
    command.Append(e.PrinterSettings.PrinterUri);

    // ipptool 작업 파일의 임시 파일 이름 가져오기
    var jobFile = Path.GetTempFileName();

    var sb = new StringBuilder();
    sb.AppendLine("{");

    // 작업 이름 및 작업 유형 설정
    sb.AppendLine("  NAME \"Print file using Print-Job\"");
    sb.AppendLine("  OPERATION Print-Job");

    // 기본 작업 설정 적용
    sb.AppendLine("  GROUP operation-attributes-tag");
    sb.AppendLine("  ATTR charset attributes-charset utf-8");
    sb.AppendLine("  ATTR language attributes-natural-language en");
    sb.AppendLine("  ATTR uri printer-uri $uri");
    sb.AppendLine("  ATTR name requesting-user-name $user");
    sb.AppendLine("  ATTR mimeMediaType document-format $filetype");

    sb.AppendLine("  GROUP job-attributes-tag");

    // 복사본 수 설정
    var copies = e.PrinterSettings.Copies < 1 ? 1 : e.PrinterSettings.Copies;
    sb.AppendFormat("  ATTR integer copies {0}{1}", copies, Environment.NewLine);

    sb.AppendLine("  ATTR collection media-col {");
    // 용지 크기 설정
    sb.AppendLine("    MEMBER collection media-size {");
    // .NET은 용지 크기를 나타내기 위해 인치의 1/100을 사용하고 IPP는 밀리미터의 1/1000을 요구하므로 변환이 필요합니다
    sb.AppendFormat("      MEMBER integer x-dimension {0}{1}", (int) (e.PageSettings.PaperSize.Width * 25.4),
        Environment.NewLine);
    sb.AppendFormat("      MEMBER integer y-dimension {0}{1}", (int) (e.PageSettings.PaperSize.Height * 25.4),
        Environment.NewLine);
    sb.AppendLine("    }");

    // 여백 설정
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

    // ipptool 작업 파일 생성
    File.WriteAllText(jobFile, sb.ToString());

    // 작업 파일을 ipptool에 전달
    command.AppendFormat(" {0}", jobFile);

    // 준비된 ipptool 명령을 bash로 실행
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

    // 문서가 인쇄된 후 임시 작업 파일 삭제
    File.Delete(jobFile);
}
```

### 또 보기

* class [CustomPrintEventArgs](../../../aspose.pdf.printing/customprinteventargs/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


