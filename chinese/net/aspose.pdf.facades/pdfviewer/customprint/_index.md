---
title: "PdfViewer.CustomPrint"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfViewer 事件。发生在打印开始之前，允许提供自定义打印处理程序以取代默认处理程序"
type: docs
weight: 200
url: /zh/net/aspose.pdf.facades/pdfviewer/customprint/
---
## PdfViewer.CustomPrint event

在打印开始之前发生，可提供自定义打印处理程序以替代默认处理程序。

```csharp
public event EventHandler<CustomPrintEventArgs> CustomPrint;
```

## 示例

此示例演示了如何在 Linux 系统上使用 Aspose.PDF 进行打印。以下代码主要针对在 Linux 系统上使用 Aspose.PDF 打印。Windows 系统的用户可以继续使用默认的 PdfViewer 打印实现，而无需提供 CustomPrint 处理程序。

### Prerequisites

1. 在打印服务器系统上应安装并配置 CUPS：
* sudo apt update && apt install cups
* sudo service cups start
* if you're going to print documents on the same system where the Aspose.PDF-enabled app is running, you won't need additional CUPS configuration. If you need to print from a different system, please refer to the CUPS documentation on how to allow access to print server via the network.
2. 可以使用 CUPS Web 界面设置打印机。也可以选择使用虚拟 PDF 打印机：
* sudo apt install printer-driver-cups-pdf
* sudo service cups restart
* please make sure that the virtual PDF printer appeared in the list of available printers in the CUPS web interface (at http://localhost:631/printers/ with default CUPS settings)
3. 如果您的客户端系统（运行 Aspose.PDF 支持的应用程序的系统）与打印服务器不同，则需要在该系统上也安装并运行 CUPS：
* sudo apt update && apt install cups
* sudo service cups start

### How to print a document using the lp command

```csharp
var docPath = dataDir + "input.pdf";
var viewer = new PdfViewer();
viewer.BindPdf(docPath);

// 设置一个自定义打印处理程序，该程序构建 lp 命令并使用 bash 运行
viewer.CustomPrint += ViewerOnCustomPrintLp;

// 将文档发送到通过 printer-driver-cups-pdf 包安装的虚拟 PDF 打印机
var ps = new PrinterSettings
{
    PrinterName = "PDF"
};
var pgs = ps.DefaultPageSettings;
pgs.PaperSize = PaperSizes.A4;

// 文档将使用提供的打印处理程序进行打印
viewer.PrintDocumentWithSettings(pgs, ps);
viewer.Close();

// 自定义打印处理程序
private void ViewerOnCustomPrintLp(object sender, CustomPrintEventArgs e)
{
    var sb = new StringBuilder("lp ");
    // 设置要打印的打印机名称
    sb.AppendFormat("-d {0} ", e.PrinterSettings.PrinterName);

    // 设置副本数量
    if (e.PrinterSettings.Copies > 0)
    {
        sb.AppendFormat("-n {0} ", e.PrinterSettings.Copies);
    }

    // 设置要打印的页面范围
    if (e.PrinterSettings.PrintRange == PrintRange.SomePages)
    {
        sb.AppendFormat("-P {0}-{1} ", e.PrinterSettings.FromPage, e.PrinterSettings.ToPage);
    }

    // 设置纸张尺寸
    sb.AppendFormat("-o media={0} ", e.PageSettings.PaperSize.Kind.ToString("G").ToLower());

    // 如果需要，设置横向方向
    if (e.PageSettings.Landscape)
    {
        sb.Append("-o orientation-requested=4 ");
    }

    // 设置打印机分辨率
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

    // 如果需要，设置双面打印
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

    // 要打印的文件名
    sb.AppendFormat("-- {0} ", e.FileName);

    // 使用 bash 运行准备好的 lp 命令
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

// 设置自定义打印处理程序，该处理程序构建 ipptool 作业文件并使用 bash 运行 ipptool
viewer.CustomPrint += ViewerOnCustomPrintIpptool;

// 将文档发送到通过 printer-driver-cups-pdf 包安装的虚拟 PDF 打印机
var ps = new PrinterSettings
{
    PrinterUri = new Uri("ipp://localhost/printers/PDF");
};
var pgs = ps.DefaultPageSettings;
pgs.PaperSize = PaperSizes.A4;

// 文档将使用提供的打印处理程序进行打印
viewer.PrintDocumentWithSettings(pgs, ps);
viewer.Close();

// 自定义打印处理程序
private void ViewerOnCustomPrintIpptool(object sender, CustomPrintEventArgs e)
{
    var command = new StringBuilder("ipptool -tv ");

    // 要打印的文件名
    command.AppendFormat("-f {0} ", e.FileName);

    // 设置要打印的打印机 URI
    command.Append(e.PrinterSettings.PrinterUri);

    // 获取 ipptool 作业文件的临时文件名
    var jobFile = Path.GetTempFileName();

    var sb = new StringBuilder();
    sb.AppendLine("{");

    // 设置作业名称和作业类型
    sb.AppendLine("  NAME \"Print file using Print-Job\"");
    sb.AppendLine("  OPERATION Print-Job");

    // 设置默认作业设置
    sb.AppendLine("  GROUP operation-attributes-tag");
    sb.AppendLine("  ATTR charset attributes-charset utf-8");
    sb.AppendLine("  ATTR language attributes-natural-language en");
    sb.AppendLine("  ATTR uri printer-uri $uri");
    sb.AppendLine("  ATTR name requesting-user-name $user");
    sb.AppendLine("  ATTR mimeMediaType document-format $filetype");

    sb.AppendLine("  GROUP job-attributes-tag");

    // 设置副本数量
    var copies = e.PrinterSettings.Copies < 1 ? 1 : e.PrinterSettings.Copies;
    sb.AppendFormat("  ATTR integer copies {0}{1}", copies, Environment.NewLine);

    sb.AppendLine("  ATTR collection media-col {");
    // 设置纸张尺寸
    sb.AppendLine("    MEMBER collection media-size {");
    // .NET 使用每英寸的百分之一来表示纸张尺寸，而 IPP 需要每毫米的千分之一——需要进行转换
    sb.AppendFormat("      MEMBER integer x-dimension {0}{1}", (int) (e.PageSettings.PaperSize.Width * 25.4),
        Environment.NewLine);
    sb.AppendFormat("      MEMBER integer y-dimension {0}{1}", (int) (e.PageSettings.PaperSize.Height * 25.4),
        Environment.NewLine);
    sb.AppendLine("    }");

    // 设置页边距
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

    // 创建 ipptool 作业文件
    File.WriteAllText(jobFile, sb.ToString());

    // 将作业文件传递给 ipptool
    command.AppendFormat(" {0}", jobFile);

    // 使用 bash 运行准备好的 ipptool 命令
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

    // 文档打印完成后删除临时作业文件
    File.Delete(jobFile);
}
```

### 另请参见

* class [CustomPrintEventArgs](../../../aspose.pdf.printing/customprinteventargs/)
* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


