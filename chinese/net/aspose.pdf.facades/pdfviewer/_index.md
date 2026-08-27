---
title: "类 PdfViewer"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Facades.PdfViewer 类。表示用于查看或打印 pdf 的类。"
type: docs
weight: 4750
url: /zh/net/aspose.pdf.facades/pdfviewer/
---
## PdfViewer class

表示用于查看或打印 pdf 的类。

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
| [AutoResize](../../aspose.pdf.facades/pdfviewer/autoresize/) { get; set; } | 获取或设置一个 bool 值，指示文件是否以优化大小打印。如果为 false，则在不进行页面缩放的情况下打印页面；如果为 true，则在缩放以适应可打印区域的情况下打印页面。 |
| [AutoRotate](../../aspose.pdf.facades/pdfviewer/autorotate/) { get; set; } | 获取或设置一个 bool 值，指示文件是否自动旋转打印。 |
| [AutoRotateMode](../../aspose.pdf.facades/pdfviewer/autorotatemode/) { get; set; } | 获取或设置一个 AutoRotateMode 值，指示旋转方向。 |
| [CoordinateType](../../aspose.pdf.facades/pdfviewer/coordinatetype/) { get; set; } | 获取或设置页面坐标类型（Media/Crop 框）。默认使用 CropBox 值。 |
| [FormPresentationMode](../../aspose.pdf.facades/pdfviewer/formpresentationmode/) { get; set; } | 获取或设置表单呈现模式。 |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfviewer/horizontalalignment/) { get; set; } | 获取或设置指示水平对齐的值。 |
| [PageCount](../../aspose.pdf.facades/pdfviewer/pagecount/) { get; } | 获取当前 Pdf 文件的页数。 |
| [Password](../../aspose.pdf.facades/pdfviewer/password/) { get; set; } | 获取或设置 input document 密码。 |
| [PrintAsGrayscale](../../aspose.pdf.facades/pdfviewer/printasgrayscale/) { get; set; } | 获取或设置一个布尔值，指示页面是否以灰度方式打印。默认值为 false。 |
| [PrintAsImage](../../aspose.pdf.facades/pdfviewer/printasimage/) { get; set; } | 设置或获取 PdfViewer 的图像打印模式。 |
| [PrinterJobName](../../aspose.pdf.facades/pdfviewer/printerjobname/) { get; set; } | 获取或设置打印机队列中 document 的名称。当 document被打印时，默认值为文件名。 |
| [PrintPageDialog](../../aspose.pdf.facades/pdfviewer/printpagedialog/) { get; set; } | 获取或设置一个布尔值，指示打印时是否生成页码对话框。 |
| [PrintStatus](../../aspose.pdf.facades/pdfviewer/printstatus/) { get; } | 获取打印作业的结果。如果成功则为 null；否则为异常对象。 |
| [RenderingOptions](../../aspose.pdf.facades/pdfviewer/renderingoptions/) { get; set; } | 获取或设置渲染选项。 |
| [Resolution](../../aspose.pdf.facades/pdfviewer/resolution/) { get; set; } | 获取或设置查看和打印时的分辨率。分辨率越高，速度越慢。默认值为 150。 |
| [ScaleFactor](../../aspose.pdf.facades/pdfviewer/scalefactor/) { get; set; } | 获取或设置指示缩放因子的浮点值。默认值为 1.0。 |
| [UseIntermidiateImage](../../aspose.pdf.facades/pdfviewer/useintermidiateimage/) { get; set; } | 获取/设置在文件模式下打印时将 pdf 页面转换为中间 png 文件的使用。当输出文件大小重要时使用它。 |
| [VerticalAlignment](../../aspose.pdf.facades/pdfviewer/verticalalignment/) { get; set; } | 获取或设置指示垂直对齐的值。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf)(Document) | 初始化 facade。 |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf_1)(Stream) | 初始化 facade。 |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf_2)(string) | 初始化 facade。 |
| [Close](../../aspose.pdf.facades/pdfviewer/close/)() | 关闭 facade。 |
| [DecodeAllPages](../../aspose.pdf.facades/pdfviewer/decodeallpages/)() | 获取当前 pdf 文件的页面。 |
| [DecodePage](../../aspose.pdf.facades/pdfviewer/decodepage/)(int) | 解码一个 Pdf 文件的页面。 |
| [Dispose](../../aspose.pdf.facades/pdfviewer/dispose/)() | 释放 facade 资源。 |
| [GetDefaultPageSettings](../../aspose.pdf.facades/pdfviewer/getdefaultpagesettings/)() | 获取默认页面设置。 |
| [GetDefaultPrinterSettings](../../aspose.pdf.facades/pdfviewer/getdefaultprintersettings/)() | 获取默认打印机设置。 |
| [PrintDocument](../../aspose.pdf.facades/pdfviewer/printdocument/)() | 使用默认打印机打印 Pdf document。 |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings/#printdocumentwithsettings_1)(PrinterSettings) | 使用打印机设置打印 Pdf document。输出页面大小将适配该 document 的首页大小。 |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings/#printdocumentwithsettings)(PageSettings, PrinterSettings) | 使用设置打印 Pdf document。如果 document 大小与页面尺寸不匹配，将扩展以适配页面尺寸。 |
| [PrintDocumentWithSetup](../../aspose.pdf.facades/pdfviewer/printdocumentwithsetup/)() | 使用设置对话框打印 Pdf document。通过对话框选择打印机。 |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf)(Stream) | 打开并打印大型 Pdf 流。如果您的 Pdf 文件有数百页或更多，或其大小超过 3 MB，建议使用此方法以获得更佳性能。 |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_3)(string) | 打开并打印大型 Pdf 文件。如果您的 Pdf 文件有数百页或更多，或其大小超过 3 MB，建议使用此方法以获得更佳性能。 |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_2)(Stream, PrinterSettings) | 打开并打印大型 Pdf 流，使用指定的打印机设置。如果您的 Pdf 文件有数百页或更多，或其大小超过 3 MB，建议使用此方法以获得更好的性能。 |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_5)(string, PrinterSettings) | 打开并打印大型 Pdf 文件，使用指定的打印机设置。如果您的 Pdf 文件有数百页或更多，或其大小超过 3 MB，建议使用此方法以获得更好的性能。 |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_1)(Stream, PageSettings, PrinterSettings) | 打开并打印大型 Pdf 流，使用指定的页面设置和打印机设置。如果您的 Pdf 文件有数百页或更多，或其大小超过 3 MB，建议使用此方法以获得更好的性能。 |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_4)(string, PageSettings, PrinterSettings) | 打开并打印大型 Pdf 文件，使用指定的页面设置和打印机设置。如果您的 Pdf 文件有数百页或更多，或其大小超过 3 MB，建议使用此方法以获得更好的性能。 |
| [Save](../../aspose.pdf.facades/pdfviewer/save/#save)(Stream) | 将结果 PDF 文档保存到流中。 |
| [Save](../../aspose.pdf.facades/pdfviewer/save/#save_1)(string) | 将结果 PDF 文档保存到文件中。 |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments)(params Document[]) | 使用默认打印机和页面设置打印多个 PDF 文档。 |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_7)(params Stream[]) | 使用默认打印机和页面设置，从提供的流中打印多个 PDF 文档。 |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_8)(params string[]) | 使用默认打印机和页面设置打印多个 PDF 文档。 |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_1)(PrinterSettings, params Document[]) | 使用指定的打印机设置打印多个 PDF 文档。 |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_5)(PrinterSettings, params Stream[]) | 使用指定的打印机设置，从提供的流中打印多个 PDF 文档。 |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_6)(PrinterSettings, params string[]) | 使用指定的打印机设置打印多个 PDF 文档。 |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_2)(PrinterSettings, PageSettings, params Document[]) | 使用指定的打印机和页面设置打印多个 PDF 文档。 |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_3)(PrinterSettings, PageSettings, params Stream[]) | 使用指定的打印机和页面设置，从提供的流中打印多个 PDF 文档。 |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_4)(PrinterSettings, PageSettings, params string[]) | 使用指定的打印机和页面设置打印多个 PDF 文档。 |

## 事件

| 名称 | 描述 |
| --- | --- |
| event [CustomPrint](../../aspose.pdf.facades/pdfviewer/customprint/) | 在打印开始之前发生，可提供自定义打印处理程序以替代默认处理程序。 |
| event [EndPage](../../aspose.pdf.facades/pdfviewer/endpage/) | 当 PdfViewer 中的页面打印结束时发生。 |
| event [EndPrint](../../aspose.pdf.facades/pdfviewer/endprint/) | 在最后一页打印事件上添加/移除订阅。 |
| event [PdfQueryPageSettings](../../aspose.pdf.facades/pdfviewer/pdfquerypagesettings/) | 在最后一页打印事件上添加/移除订阅。 |
| event [StartPage](../../aspose.pdf.facades/pdfviewer/startpage/) | 在页面开始打印之前发生。 |

### 另请参见

* interface [IFacade](../ifacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


