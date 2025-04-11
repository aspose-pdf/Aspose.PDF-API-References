---
title: Class PdfViewer
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfViewer 类。表示一个用于查看或打印 PDF 的类
type: docs
weight: 4630
url: /zh/net/aspose.pdf.facades/pdfviewer/
---
## PdfViewer 类

表示一个用于查看或打印 PDF 的类。

```csharp
public sealed class PdfViewer : IFacade
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PdfViewer](pdfviewer/#constructor)() | 初始化新的 `PdfViewer` 对象。 |
| [PdfViewer](pdfviewer/#constructor_1)(Document) | 初始化新的 `PdfViewer` 对象。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AutoResize](../../aspose.pdf.facades/pdfviewer/autoresize/) { get; set; } | 获取或设置一个布尔值，指示文件是否以优化大小打印。如果为 false，则不进行页面缩放打印。如果为 true，则以适合可打印区域的比例进行打印。 |
| [AutoRotate](../../aspose.pdf.facades/pdfviewer/autorotate/) { get; set; } | 获取或设置一个布尔值，指示文件是否以自动旋转方式打印 |
| [AutoRotateMode](../../aspose.pdf.facades/pdfviewer/autorotatemode/) { get; set; } | 获取或设置一个 AutoRotateMode 值，指示旋转方向 |
| [CoordinateType](../../aspose.pdf.facades/pdfviewer/coordinatetype/) { get; set; } | 获取或设置页面坐标类型（媒体/裁剪框）。默认使用 CropBox 值。 |
| [FormPresentationMode](../../aspose.pdf.facades/pdfviewer/formpresentationmode/) { get; set; } | 获取或设置表单呈现模式。 |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfviewer/horizontalalignment/) { get; set; } | 获取或设置一个值，指示水平对齐方式 |
| [PageCount](../../aspose.pdf.facades/pdfviewer/pagecount/) { get; } | 获取当前 PDF 文件的页面数量。 |
| [Password](../../aspose.pdf.facades/pdfviewer/password/) { get; set; } | 获取或设置输入文档密码。 |
| [PrintAsGrayscale](../../aspose.pdf.facades/pdfviewer/printasgrayscale/) { get; set; } | 获取或设置一个布尔值，指示页面是否以灰度打印。默认值为 false。 |
| [PrintAsImage](../../aspose.pdf.facades/pdfviewer/printasimage/) { get; set; } | 设置或获取 PdfViewer 以图像形式打印的模式。 |
| [PrinterJobName](../../aspose.pdf.facades/pdfviewer/printerjobname/) { get; set; } | 获取或设置文档在打印时在打印队列中的名称。默认值为文件名。 |
| [PrintPageDialog](../../aspose.pdf.facades/pdfviewer/printpagedialog/) { get; set; } | 获取或设置一个布尔值，指示在打印时是否生成页面编号对话框。 |
| [PrintStatus](../../aspose.pdf.facades/pdfviewer/printstatus/) { get; } | 获取打印作业的结果。如果成功则为 null；否则为异常对象。 |
| [RenderingOptions](../../aspose.pdf.facades/pdfviewer/renderingoptions/) { get; set; } | 获取或设置渲染选项。 |
| [Resolution](../../aspose.pdf.facades/pdfviewer/resolution/) { get; set; } | 获取或设置查看和打印时的分辨率。分辨率越高，速度越慢。默认值为 150。 |
| [ScaleFactor](../../aspose.pdf.facades/pdfviewer/scalefactor/) { get; set; } | 获取或设置一个浮点值，指示缩放因子。默认值为 1.0。 |
| [UseIntermidiateImage](../../aspose.pdf.facades/pdfviewer/useintermidiateimage/) { get; set; } | 获取/设置在文件模式下打印时将 PDF 页面转换为中间 PNG 文件的使用。输出文件大小重要时使用。 |
| [VerticalAlignment](../../aspose.pdf.facades/pdfviewer/verticalalignment/) { get; set; } | 获取或设置一个值，指示垂直对齐方式 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf)(Document) | 初始化外观。 |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf_1)(Stream) | 初始化外观。 |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf_2)(string) | 初始化外观。 |
| [Close](../../aspose.pdf.facades/pdfviewer/close/)() | 关闭外观。 |
| [DecodeAllPages](../../aspose.pdf.facades/pdfviewer/decodeallpages/)() | 获取当前 PDF 文件的页面。 |
| [DecodePage](../../aspose.pdf.facades/pdfviewer/decodepage/)(int) | 解码一个 PDF 文件的页面。 |
| [Dispose](../../aspose.pdf.facades/pdfviewer/dispose/)() | 释放外观资源。 |
| [GetDefaultPageSettings](../../aspose.pdf.facades/pdfviewer/getdefaultpagesettings/)() | 获取默认页面设置。 |
| [GetDefaultPrinterSettings](../../aspose.pdf.facades/pdfviewer/getdefaultprintersettings/)() | 获取默认打印机设置。 |
| [PrintDocument](../../aspose.pdf.facades/pdfviewer/printdocument/)() | 使用默认打印机打印 PDF 文档。 |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings/#printdocumentwithsettings_1)(PrinterSettings) | 使用打印机设置打印 PDF 文档。输出页面大小将适合文档的第一页大小。 |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings/#printdocumentwithsettings)(PageSettings, PrinterSettings) | 使用设置打印 PDF 文档。如果文档大小与页面大小不符，将扩展以适合页面大小。 |
| [PrintDocumentWithSetup](../../aspose.pdf.facades/pdfviewer/printdocumentwithsetup/)() | 使用设置对话框打印 PDF 文档。通过对话框选择打印机。 |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf)(Stream) | 打开并打印大型 PDF 流。如果您的 PDF 文件有数百页或更多，或其大小超过 3 MB，建议使用此方法以获得更好的性能。 |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_3)(string) | 打开并打印大型 PDF 文件。如果您的 PDF 文件有数百页或更多，或其大小超过 3 MB，建议使用此方法以获得更好的性能。 |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_2)(Stream, PrinterSettings) | 打开并打印具有指定打印机设置的大型 PDF 流。如果您的 PDF 文件有数百页或更多，或其大小超过 3 MB，建议使用此方法以获得更好的性能。 |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_5)(string, PrinterSettings) | 打开并打印具有指定打印机设置的大型 PDF 文件。如果您的 PDF 文件有数百页或更多，或其大小超过 3 MB，建议使用此方法以获得更好的性能。 |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_1)(Stream, PageSettings, PrinterSettings) | 打开并打印具有指定页面设置和打印机设置的大型 PDF 流。如果您的 PDF 文件有数百页或更多，或其大小超过 3 MB，建议使用此方法以获得更好的性能。 |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_4)(string, PageSettings, PrinterSettings) | 打开并打印具有指定页面设置和打印机设置的大型 PDF 文件。如果您的 PDF 文件有数百页或更多，或其大小超过 3 MB，建议使用此方法以获得更好的性能。 |
| [Save](../../aspose.pdf.facades/pdfviewer/save/#save)(Stream) | 将结果 PDF 文档保存到流。 |
| [Save](../../aspose.pdf.facades/pdfviewer/save/#save_1)(string) | 将结果 PDF 文档保存到文件。 |

## 事件

| 名称 | 描述 |
| --- | --- |
| event [CustomPrint](../../aspose.pdf.facades/pdfviewer/customprint/) | 在打印开始之前发生，并允许提供自定义打印处理程序，而不是默认处理程序。 |
| event [EndPage](../../aspose.pdf.facades/pdfviewer/endpage/) | 在 PdfViewer 中打印页面结束时发生。 |
| event [EndPrint](../../aspose.pdf.facades/pdfviewer/endprint/) | 添加/移除对最后一页打印事件的订阅。 |
| event [PdfQueryPageSettings](../../aspose.pdf.facades/pdfviewer/pdfquerypagesettings/) | 添加/移除对最后一页打印事件的订阅。 |
| event [StartPage](../../aspose.pdf.facades/pdfviewer/startpage/) | 在页面开始打印之前发生。 |

### 另请参阅

* interface [IFacade](../ifacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)