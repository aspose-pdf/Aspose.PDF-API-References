---
title: PdfViewer.CustomPrint
second_title: Aspose.PDF for .NET API Reference
description: PdfViewer 事件。在打印开始之前发生，并允许提供自定义打印处理程序，而不是默认的处理程序
type: docs
weight: 200
url: /zh/net/aspose.pdf.facades/pdfviewer/customprint/
---
## PdfViewer.CustomPrint 事件

在打印开始之前发生，并允许提供自定义打印处理程序，而不是默认的处理程序。

```csharp
public event EventHandler<CustomPrintEventArgs> CustomPrint;
```

## 示例

该示例演示如何在 Linux 系统上从 Aspose.PDF 打印。以下代码主要针对在 Linux 系统上从 Aspose.PDF 打印。Windows 系统的用户可以继续使用默认的 PdfViewer 打印实现，而无需提供 CustomPrint 处理程序。

### 前提条件

1. 在打印服务器系统上，应该安装并配置 CUPS：
* sudo apt update && apt install cups
* sudo service cups start
* 如果您打算在与运行 Aspose.PDF 应用程序相同的系统上打印文档，则无需额外的 CUPS 配置。如果您需要从不同的系统打印，请参考 CUPS 文档以了解如何通过网络允许访问打印服务器。
2. 可以使用 CUPS Web 界面设置打印机。可选地，您可以使用虚拟 PDF 打印机：
* sudo apt install printer-driver-cups-pdf
* sudo service cups restart
* 请确保虚拟 PDF 打印机出现在 CUPS Web 界面中可用打印机的列表中（在 http://localhost:631/printers/ 处，使用默认 CUPS 设置）
3. 如果您的客户端系统（运行 Aspose.PDF 应用程序的系统）与打印服务器不同，您还需要在该系统上安装并运行 CUPS：
* sudo apt update && apt install cups
* sudo service cups start

### 如何使用 lp 命令打印文档

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

### 如何使用 ipptool 打印文档

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

### 另见

* class [CustomPrintEventArgs](../../../aspose.pdf.printing/customprinteventargs/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)