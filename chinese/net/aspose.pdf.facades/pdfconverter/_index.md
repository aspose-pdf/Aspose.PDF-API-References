---
title: Class PdfConverter
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfConverter 类。表示一个将 pdf 文件的每一页转换为图像的类，支持 BMP、JPEG、PNG 和 TIFF。支持的 pdf 内容：图片、表单、注释。
type: docs
weight: 4440
url: /zh/net/aspose.pdf.facades/pdfconverter/
---
## PdfConverter 类

表示一个将 pdf 文件的每一页转换为图像的类，支持 BMP、JPEG、PNG 和 TIFF。支持的 pdf 内容：图片、表单、注释。

```csharp
public sealed class PdfConverter : Facade
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PdfConverter](pdfconverter/#constructor)() | 初始化新的 `PdfConverter` 对象。 |
| [PdfConverter](pdfconverter/#constructor_1)(Document) | 基于 *document* 初始化新的 `PdfConverter` 对象。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CoordinateType](../../aspose.pdf.facades/pdfconverter/coordinatetype/) { get; set; } | 获取或设置页面坐标类型（媒体/裁剪框）。默认使用 CropBox 值。 |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 获取正在处理的文档外观。 |
| [EndPage](../../aspose.pdf.facades/pdfconverter/endpage/) { get; set; } | 获取或设置要转换的结束位置。 |
| [FormPresentationMode](../../aspose.pdf.facades/pdfconverter/formpresentationmode/) { get; set; } | 获取或设置表单呈现模式。 |
| [PageCount](../../aspose.pdf.facades/pdfconverter/pagecount/) { get; } | 获取页面数量。 |
| [Password](../../aspose.pdf.facades/pdfconverter/password/) { get; set; } | 获取或设置文档的 OwnerPassword。 |
| [RenderingOptions](../../aspose.pdf.facades/pdfconverter/renderingoptions/) { get; set; } | 获取或设置渲染选项。 |
| [Resolution](../../aspose.pdf.facades/pdfconverter/resolution/) { get; set; } | 获取或设置转换时的分辨率。分辨率越高，转换速度越慢。默认值为 150。 |
| [StartPage](../../aspose.pdf.facades/pdfconverter/startpage/) { get; set; } | 获取或设置要转换的起始位置。最小值为 1。 |
| [UserPassword](../../aspose.pdf.facades/pdfconverter/userpassword/) { get; set; } | 获取或设置文档的 UserPassword。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | 初始化外观。 |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf_1)(Stream) | 绑定用于转换的 Pdf 流。 |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf_2)(string) | 绑定用于转换的 Pdf 文件。 |
| override [Close](../../aspose.pdf.facades/pdfconverter/close/)() | 关闭 PdfConverter 实例并释放资源。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | 处理外观。 |
| [DoConvert](../../aspose.pdf.facades/pdfconverter/doconvert/)() | 为将 pdf 文档转换为图像执行一些初始工作。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage)(Stream) | 将图像保存到流，默认图像格式为 jpeg。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_9)(string) | 将图像保存到文件，默认图像格式为 jpeg。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_4)(Stream, ImageFormat) | 将图像保存到流，使用给定的图像格式。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_1)(Stream, PageSize) | 将图像保存到流，使用给定的页面大小。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_13)(string, ImageFormat) | 将图像保存到文件，使用给定的图像格式。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_10)(string, PageSize) | 将图像保存到文件，使用给定的页面大小和默认图像格式 - jpeg。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_6)(Stream, ImageFormat, int) | 将图像保存到流，使用给定的图像格式和质量。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_2)(Stream, PageSize, ImageFormat) | 将图像保存到流，使用给定的页面大小。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_15)(string, ImageFormat, int) | 将图像保存到文件，使用给定的图像格式和质量。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_11)(string, PageSize, ImageFormat) | 将图像保存到文件，使用给定的页面大小和图像格式。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_7)(Stream, ImageFormat, int, int) | 将图像保存到流，使用给定的图像格式、大小和质量。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_3)(Stream, PageSize, ImageFormat, int) | 将图像保存到流，使用给定的页面大小、图像格式和质量。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_16)(string, ImageFormat, int, int) | 将图像保存到文件，使用给定的图像格式和尺寸。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_12)(string, PageSize, ImageFormat, int) | 将图像保存到文件，使用给定的页面大小、图像格式和质量。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_5)(Stream, ImageFormat, double, double, int) | 将图像保存到流，使用给定的图像格式、大小和质量。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_8)(Stream, ImageFormat, int, int, int) | 将图像保存到流，使用给定的图像格式、尺寸和质量。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_14)(string, ImageFormat, double, double, int) | 将图像保存到文件，使用给定的图像格式、图像大小和质量。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_17)(string, ImageFormat, int, int, int) | 将图像保存到文件，使用给定的图像格式、尺寸和质量。 |
| [HasNextImage](../../aspose.pdf.facades/pdfconverter/hasnextimage/)() | 指示 pdf 文件是否还有更多图像。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff)(Stream) | 将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF 流中。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_10)(string) | 将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF 文件中。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_1)(Stream, CompressionType) | 将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF 文件中。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_4)(Stream, PageSize) | 将 pdf 文档的每一页转换为图像并使用页面大小将图像保存到单个 TIFF 流中。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_2)(Stream, TiffSettings) | 将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF 流中。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_11)(string, CompressionType) | 将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF 文件中。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_14)(string, PageSize) | 将 pdf 文档的每一页转换为图像并使用页面大小将图像保存到单个 TIFF 文件中。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_12)(string, TiffSettings) | 将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF 文件中。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_6)(Stream, int, int) | 将 pdf 文档的每一页转换为图像并使用尺寸将图像保存到单个 TIFF 流中。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_5)(Stream, PageSize, TiffSettings) | 将 pdf 文档的每一页转换为图像并使用页面大小将图像保存到单个 TIFF 流中。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_3)(Stream, TiffSettings, IIndexBitmapConverter) | 将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF 流中。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_16)(string, int, int) | 将 pdf 文档的每一页转换为图像并使用尺寸将图像保存到单个 TIFF 文件中。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_15)(string, PageSize, TiffSettings) | 将 pdf 文档的每一页转换为图像并使用页面大小将图像保存到单个 TIFF 文件中。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_13)(string, TiffSettings, IIndexBitmapConverter) | 将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF 文件中。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_7)(Stream, int, int, CompressionType) | 将 pdf 文档的每一页转换为图像并使用尺寸将图像保存到单个 TIFF 流中。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_8)(Stream, int, int, TiffSettings) | 将 pdf 文档的每一页转换为图像并使用尺寸将图像保存到单个 TIFF 流中。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_17)(string, int, int, CompressionType) | 将 pdf 文档的每一页转换为图像并使用尺寸将图像保存到单个 TIFF 文件中。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_18)(string, int, int, TiffSettings) | 将 pdf 文档的每一页转换为图像并使用尺寸将图像保存到单个 TIFF 文件中。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_9)(Stream, int, int, TiffSettings, IIndexBitmapConverter) | 将 pdf 文档的每一页转换为图像并使用尺寸将图像保存到单个 TIFF 流中。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_19)(string, int, int, TiffSettings, IIndexBitmapConverter) | 将 pdf 文档的每一页转换为图像并使用尺寸将图像保存到单个 TIFF 文件中。 |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf)(Stream) | 将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF ClassF 流中。 |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_3)(string) | 将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF ClassF 文件中。 |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_1)(Stream, PageSize) | 将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF ClassF 流中。 |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_4)(string, PageSize) | 将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF ClassF 文件中。 |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_2)(Stream, int, int) | 将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF ClassF 流中。 |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_5)(string, int, int) | 将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF ClassF 文件中。 |
| static [MergeImages](../../aspose.pdf.facades/pdfconverter/mergeimages/)(List&lt;Stream&gt;, ImageFormat, ImageMergeMode, int?, int?) | 将图像流列表合并为一个图像流。支持 Png/jpg/tiff 输出格式，如果使用不支持的格式，输出流默认编码为 Jpeg。 |
| static [MergeImagesAsTiff](../../aspose.pdf.facades/pdfconverter/mergeimagesastiff/)(List&lt;Stream&gt;) | 将 tiff 流列表合并为一个多帧 tiff 流。 |

### 另请参阅

* 类 [Facade](../facade/)
* 命名空间 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../)