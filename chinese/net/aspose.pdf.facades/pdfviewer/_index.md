---
title: PdfViewer
second_title: Aspose.PDF for .NET API 参考
description: 表示查看或打印 pdf 的类
type: docs
weight: 2640
url: /zh/net/aspose.pdf.facades/pdfviewer/
---
## PdfViewer class

表示查看或打印 pdf 的类。

```csharp
public sealed class PdfViewer : IFacade
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [PdfViewer](pdfviewer#constructor)() | 初始化新的[`PdfViewer`](../pdfviewer)对象. |
| [PdfViewer](pdfviewer#constructor_1)(Document) | 初始化新的[`PdfViewer`](../pdfviewer)对象. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AutoResize](../../aspose.pdf.facades/pdfviewer/autoresize) { get; set; } | 获取或设置一个布尔值，指示文件是否以优化大小打印。  如果是错误的打印页面，没有页面缩放。 如果是正确的打印页面，可以缩放以适合可打印区域。 |
| [AutoRotate](../../aspose.pdf.facades/pdfviewer/autorotate) { get; set; } | 获取或设置一个布尔值，指示文件是否使用自动旋转打印 |
| [AutoRotateMode](../../aspose.pdf.facades/pdfviewer/autorotatemode) { get; set; } | 获取或设置指示旋转方向的 AutoRotateMode 值 |
| [CoordinateType](../../aspose.pdf.facades/pdfviewer/coordinatetype) { get; set; } | 获取或设置页面坐标类型（媒体/裁剪框）。默认使用 CropBox 值。 |
| [FormPresentationMode](../../aspose.pdf.facades/pdfviewer/formpresentationmode) { get; set; } | 获取或设置表单展示模式。 |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfviewer/horizontalalignment) { get; set; } | 获取或设置一个表示水平对齐的值 |
| [PageCount](../../aspose.pdf.facades/pdfviewer/pagecount) { get; } | 获取当前 Pdf 文件的页数。 |
| [Password](../../aspose.pdf.facades/pdfviewer/password) { get; set; } | 获取或设置输入文档密码。 |
| [PrintAsGrayscale](../../aspose.pdf.facades/pdfviewer/printasgrayscale) { get; set; } | 获取或设置一个布尔值，指示页面是否打印为灰度。默认为假。 |
| [PrintAsImage](../../aspose.pdf.facades/pdfviewer/printasimage) { get; set; } | 设置或获取 PdfViewer 打印为图像的模式。 |
| [PrinterJobName](../../aspose.pdf.facades/pdfviewer/printerjobname) { get; set; } | 获取或设置打印文档时打印机队列中的文档名称。默认值为文件名。 |
| [PrintPageDialog](../../aspose.pdf.facades/pdfviewer/printpagedialog) { get; set; } | 获取或设置一个布尔值，指示打印时是否产生页码对话框。 |
| [PrintStatus](../../aspose.pdf.facades/pdfviewer/printstatus) { get; } | 获取打印作业的结果。如果成功则为空；否则，异常对象. |
| [RenderingOptions](../../aspose.pdf.facades/pdfviewer/renderingoptions) { get; set; } | 获取或设置渲染选项。 |
| [Resolution](../../aspose.pdf.facades/pdfviewer/resolution) { get; set; } | 在查看和打印期间获取或设置分辨率。分辨率越高，速度越慢。默认值为 150. |
| [ScaleFactor](../../aspose.pdf.facades/pdfviewer/scalefactor) { get; set; } | 获取或设置表示比例因子的浮点值。默认值为 1.0. |
| [UseIntermidiateImage](../../aspose.pdf.facades/pdfviewer/useintermidiateimage) { get; set; } | 获取/设置在文件模式下打印期间将pdf页面转换为中间png文件的使用。当输出文件的大小很重要时使用它。 |
| [VerticalAlignment](../../aspose.pdf.facades/pdfviewer/verticalalignment) { get; set; } | 获取或设置一个表示垂直对齐的值 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf#bindpdf)(Document) | 初始化外观。 |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf#bindpdf_1)(Stream) | 初始化外观。 |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf#bindpdf_2)(string) | 初始化外观。 |
| [Close](../../aspose.pdf.facades/pdfviewer/close)() | 关闭门面。 |
| [DecodeAllPages](../../aspose.pdf.facades/pdfviewer/decodeallpages)() | 获取当前pdf文件的页面。 |
| [DecodePage](../../aspose.pdf.facades/pdfviewer/decodepage)(int) | 解码一个 Pdf 文件的一页。 |
| [Dispose](../../aspose.pdf.facades/pdfviewer/dispose)() | 处理门面资源。 |
| [GetDefaultPageSettings](../../aspose.pdf.facades/pdfviewer/getdefaultpagesettings)() | 获取默认页面设置。 |
| [GetDefaultPrinterSettings](../../aspose.pdf.facades/pdfviewer/getdefaultprintersettings)() | 获取默认打印机设置。 |
| [PrintDocument](../../aspose.pdf.facades/pdfviewer/printdocument)() | 使用默认打印机打印 Pdf 文档。 |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings#printdocumentwithsettings_1)(PrinterSettings) | 使用打印机设置打印 Pdf 文档。输出页面大小将适合文档首页大小。 |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings#printdocumentwithsettings)(PageSettings, PrinterSettings) | 打印带有设置的 Pdf 文档。如果文档大小与页面大小不兼容，pdf.kit 将扩展它以适应页面大小。 |
| [PrintDocumentWithSetup](../../aspose.pdf.facades/pdfviewer/printdocumentwithsetup)() | 打印带有设置对话框的 Pdf 文档。使用对话框选择打印机。 |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf)(Stream) | 打开并打印一个大的 Pdf 流。如果您的 Pdf 文件有数百页或更多或它的大小是 超过 3 MB，建议使用此方法以获得更好的性能。 |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf_3)(string) | 打开并打印一个大的 Pdf 文件。如果您的 Pdf 文件有数百页或更多或它的大小是 超过 3 MB，建议使用此方法以获得更好的性能。 |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf_2)(Stream, PrinterSettings) | 打开并打印具有指定打印机设置的大型 Pdf 流。如果您的 Pdf 文件有数百 页或更多或它的大小超过 3 MB，建议使用此方法以获得更好的性能。 |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf_5)(string, PrinterSettings) | 打开并打印具有指定打印机设置的大型 Pdf 文件。如果您的 Pdf 文件有数百 页或更多或它的大小超过 3 MB，建议使用此方法以获得更好的性能。 |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf_1)(Stream, PageSettings, PrinterSettings) | 打开并打印具有指定页面设置和打印机设置的大型 Pdf 流。如果您的 Pdf 文件有数百页或更多或它的大小超过 3 MB，建议使用此方法 获得更好的性能。 |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf_4)(string, PageSettings, PrinterSettings) | 打开并打印具有指定页面设置和打印机设置的大型 Pdf 文件。如果您的 Pdf 文件有数百页或更多或它的大小超过 3 MB，建议使用此方法 获得更好的性能。 |
| [Save](../../aspose.pdf.facades/pdfviewer/save#save)(Stream) | 将结果 PDF 文档保存到流中。 |
| [Save](../../aspose.pdf.facades/pdfviewer/save#save_1)(string) | 将结果 PDF 文档保存到文件中。 |

### 也可以看看

* interface [IFacade](../ifacade)
* 命名空间 [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
