---
title: "PdfConverter"
linktitle: "PdfConverter"
second_title: "Aspose.PDF for Java API 参考"
description: "表示一个类，用于将 PDF 文件的每一页转换为图像，当前支持 BMP、JPEG、PNG 和 TIFF。支持的 PDF 内容包括：图片、表单、注释。"
type: docs
weight: 390
url: /zh/java/com.aspose.pdf.facades/pdfconverter/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.PdfConverter, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.PdfConverter

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public final class PdfConverter extends Facade
```

表示用于将 PDF 文件的每页转换为图像的类，现已支持 BMP、JPEG、PNG 和 TIFF。支持的 PDF 内容包括：图片、表单、注释。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfConverter](#PdfConverter--) | 初始化新的 {@code PdfConverter} 对象。 |
| [PdfConverter](#PdfConverter-com.aspose.pdf.IDocument-) | 初始化新的 {@code PdfConverter} 对象。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.Document-) | 将 PDF 文档绑定到 {@link PdfConverter} 实例以进行后续处理。 |
| [bindPdf](#bindPdf-java.io.InputStream-) | 绑定一个 Pdf 流以进行转换。 |
| [bindPdf](#bindPdf-java.lang.String-) | 绑定一个 Pdf 文件进行转换。 |
| [close](#close--) | 关闭 PdfConverter 实例并释放资源。 |
| [convertPageToPNGMemoryStream](#convertPageToPNGMemoryStream-com.aspose.pdf.Page-) | 仅供内部使用 |
| [dispose](#dispose--) | 关闭 PdfConverter 实例并释放资源。此方法已过时，请改用 close()。 |
| [doConvert](#doConvert--) | <p> 执行一些将 pdf 文档转换为图像的初始工作。 </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.doConvert(); String prefix = "D:\\\\Test\\\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix); imageCount++; } </pre> |
| [getCoordinateType](#getCoordinateType--) | 获取页面坐标类型（Media/Crop 框）。默认使用 CropBox 值。 |
| [getEndPage](#getEndPage--) | 获取要转换的结束位置。 |
| [getFormPresentationMode](#getFormPresentationMode--) | 获取表单呈现模式。 |
| [getNextImage](#getNextImage-java.io.OutputStream-) | 将图像保存到流，使用默认图像格式 - jpeg。 |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-) | 将图像保存到流，使用指定的图像格式。 |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-double-double-int-) | 将图像保存到流，使用给定的图像格式、尺寸和质量。 |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-) | 将图像保存到流，使用指定的图像格式和质量。 |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-) | 将图像保存到流，使用给定的图像格式、尺寸和质量。 |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-int-) | 将图像保存到流，使用给定的图像格式、尺寸和质量。 |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-) | 将图像保存到流，使用指定的页面尺寸。 |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-) | 将图像保存到流，使用指定的页面尺寸。 |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-) | 将图像保存到流，使用指定的页面尺寸、图像格式和质量。 |
| [getNextImage](#getNextImage-java.lang.String-) | 将图像保存到文件，使用默认图像格式 - jpeg。 |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-) | <p> 将图像保存到文件，使用给定的图像格式。 </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.DoConvert(); String prefix = @"D:\\Test\\"; String suffix = ".png"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Png); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-double-double-int-) | <p> 将图像保存到文件，使用给定的图像格式、图像尺寸和质量。 </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); String prefix = @"D:\\Test\\"; String suffix = ".jpg"; int imageCount = 1; float pixelX=800f; float pixelY=600f; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-) | 将图像保存到文件，使用指定的图像格式和质量。 |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-) | <p> 将图像保存到文件，使用给定的图像格式和尺寸。 </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.DoConvert(); String prefix = "D:\\\\Test\\\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-int-) | <p> 将图像保存到文件，使用给定的图像格式、尺寸和质量。 </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); String prefix = @"D:\\Test\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-) | 将图像保存到文件，使用给定的页面尺寸和默认的图像格式 - jpeg。 |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-) | 将图像保存到文件，使用给定的页面尺寸和图像格式。 |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-) | 将图像保存到文件，使用给定的页面尺寸、图像格式和质量。 |
| [getPageCount](#getPageCount--) | 获取页面计数。 |
| [getPassword](#getPassword--) | 获取文档 OwnerPassword。 |
| [getRenderingOptions](#getRenderingOptions--) | 获取渲染选项。 |
| [getResolution](#getResolution--) | 获取转换过程中的分辨率。分辨率越高，转换速度越慢。默认值为 150。 |
| [getStartPage](#getStartPage--) | 获取要转换的起始位置。最小值为 1。 |
| [getUserPassword](#getUserPassword--) | 获取文档 UserPassword。 |
| [hasNextImage](#hasNextImage--) | 指示 PDF 文件是否还有更多图像。 |
| [isShowHiddenAreas](#isShowHiddenAreas--) | 获取控制页面隐藏区域可见性的标志。此方法已弃用。 |
| [mergeImages](#mergeImages-java.util.List-com.aspose.pdf.ImageFormat-com.aspose.pdf.facades.ImageMergeMode-java.lang.Integer-java.lang.Integer-) | 将图像流列表合并为一个图像流。 |
| [mergeImagesAsTiff](#mergeImagesAsTiff-java.util.List-) | 将 TIFF 流列表合并为一个多帧 TIFF 流。 |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-) | 将 PDF 文档的每页转换为图像，并将图像保存到单个 TIFF 流中。 |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.CompressionType-) | 将 PDF 文档的每页转换为图像，并将图像保存到单个 TIFF 文件中。 |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-) | 将 PDF 文档的每页转换为具有指定尺寸的图像，并将图像保存到单个 TIFF 流中。 |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.CompressionType-) | 将 PDF 文档的每页转换为具有指定尺寸的图像，并将图像保存到单个 TIFF 流中。 |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-) | 将 PDF 文档的每页转换为具有指定尺寸的图像，并将图像保存到单个 TIFF 流中。 |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | 将 PDF 文档的每页转换为具有指定尺寸的图像，并将图像保存到单个 TIFF 流中。 |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-) | 将 PDF 文档的每页转换为具有页面尺寸的图像，并将图像保存到单个 TIFF 流中。 |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | 将 PDF 文档的每页转换为具有页面尺寸的图像，并将图像保存到单个 TIFF 流中。 |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-) | 将 PDF 文档的每页转换为图像，并将图像保存到单个 TIFF 流中。 |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | 将 PDF 文档的每页转换为图像，并将图像保存到单个 TIFF 流中。 |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-) | <p> 将 PDF 文档的每页转换为图像，并将图像保存到单个 TIFF 文件中。 </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\\Test\\test.tiff"); </pre> |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.CompressionType-) | <p> 将 PDF 文档的每页转换为图像，并将图像保存到单个 TIFF 文件中。 </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\\Test\\test.tiff"); </pre> |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-) | 将 PDF 文档的每页转换为具有指定尺寸的图像，并将图像保存到单个 TIFF 文件中。 |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.CompressionType-) | 将 PDF 文档的每页转换为具有指定尺寸的图像，并将图像保存到单个 TIFF 文件中。 |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-) | 将 PDF 文档的每页转换为具有指定尺寸的图像，并将图像保存到单个 TIFF 文件中。 |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | 将 PDF 文档的每页转换为具有指定尺寸的图像，并将图像保存到单个 TIFF 文件中。 |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-) | 将 PDF 文档的每页转换为具有页面尺寸的图像，并将图像保存到单个 TIFF 文件中。 |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | 将 PDF 文档的每页转换为具有页面尺寸的图像，并将图像保存到单个 TIFF 文件中。 |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-) | 将 PDF 文档的每页转换为图像，并将图像保存到单个 TIFF 文件中。 |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | 将 PDF 文档的每页转换为图像，并将图像保存到单个 TIFF 文件中。 |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.io.OutputStream-) | 将 PDF 文档的每页转换为图像，并将图像保存到单个 TIFF ClassF 流中。 |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.io.OutputStream-int-int-) | 将 PDF 文档的每页转换为图像，并将图像保存到单个 TIFF ClassF 流中。 |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.io.OutputStream-com.aspose.pdf.PageSize-) | 将 PDF 文档的每页转换为图像，并将图像保存到单个 TIFF ClassF 流中。 |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.lang.String-) | <p> 将 PDF 文档的每页转换为图像，并将图像保存到单个 TIFF ClassF 文件中。 </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.doConvert(); converter.saveAsTIFFClassF("D:\\\\Test\\\\test.tiff"); </pre> |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.lang.String-int-int-) | <p> 将 PDF 文档的每页转换为图像，并将图像保存为单个 TIFF ClassF 文件。 </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@\"D:\\\\Test\\\\test.pdf\"); converter.doConvert(); converter.saveAsTIFFClassF(@\"D:\\\\Test\\\\test.tiff\",204,196); </pre> |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.lang.String-com.aspose.pdf.PageSize-) | 将 PDF 文档的每页转换为图像，并将图像保存为单个 TIFF ClassF 文件。 |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | 设置页面坐标类型（Media/Crop 框）。默认使用 CropBox 值。 |
| [setEndPage](#setEndPage-int-) | 设置要转换的结束位置。 在调用 setStartPage(int) 之前使用 setEndPage(int)。 |
| [setFormPresentationMode](#setFormPresentationMode-int-) | 设置表单呈现模式。 |
| [setPassword](#setPassword-java.lang.String-) | 设置文档的 OwnerPassword。 |
| [setRangeOfPages](#setRangeOfPages-int-int-) | 设置要转换的页面范围。 |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | 设置渲染选项。 |
| [setResolution](#setResolution-com.aspose.pdf.devices.Resolution-) | 设置转换期间的分辨率。分辨率越高，转换速度越慢。默认值为 150。 |
| [setShowHiddenAreas](#setShowHiddenAreas-boolean-) | 已弃用。 |
| [setStartPage](#setStartPage-int-) | 设置要转换的起始位置。最小值为 1。 在调用 setStartPage(int) 之前使用 setEndPage(int)。 |
| [setUserPassword](#setUserPassword-java.lang.String-) | 设置文档的 UserPassword。 |

### PdfConverter {#PdfConverter--}
```
public PdfConverter()
```

初始化新的 {@code PdfConverter} 对象。

### PdfConverter {#PdfConverter-com.aspose.pdf.IDocument-}
初始化新的 {@code PdfConverter} 对象。

### bindPdf {#bindPdf-com.aspose.pdf.Document-}
将 PDF 文档绑定到 {@link PdfConverter} 实例以进行后续处理。

### bindPdf {#bindPdf-java.io.InputStream-}
绑定一个 Pdf 流以进行转换。

### bindPdf {#bindPdf-java.lang.String-}
绑定一个 Pdf 文件进行转换。

### close {#close--}
```
public void close()
```

关闭 PdfConverter 实例并释放资源。

### convertPageToPNGMemoryStream {#convertPageToPNGMemoryStream-com.aspose.pdf.Page-}
仅供内部使用

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

关闭 PdfConverter 实例并释放资源。此方法已过时，请改用 close()。

### doConvert {#doConvert--}
```
public void doConvert()
```

<p> 进行将 PDF 文档转换为图像的初始工作。 </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(\"D:\\\\Test\\\\test.pdf\"); converter.doConvert(); String prefix = \"D:\\\\Test\\\\\"; String suffix = \".jpg\"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix); imageCount++; } </pre>

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

获取页面坐标类型（Media/Crop 框）。默认使用 CropBox 值。

**Returns:**
PageCoordinateType 元素 @see PageCoordinateType

### getEndPage {#getEndPage--}
```
public int getEndPage()
```

获取要转换的结束位置。

**Returns:**
int 值

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

获取表单呈现模式。

**Returns:**
表单呈现模式。 @see FormPresentationMode

### getNextImage {#getNextImage-java.io.OutputStream-}
将图像保存到流，使用默认图像格式 - jpeg。

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-}
将图像保存到流，使用指定的图像格式。

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-double-double-int-}
将图像保存到流，使用给定的图像格式、尺寸和质量。

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-}
将图像保存到流，使用指定的图像格式和质量。

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-}
将图像保存到流，使用给定的图像格式、尺寸和质量。

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-int-}
将图像保存到流，使用给定的图像格式、尺寸和质量。

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-}
将图像保存到流，使用指定的页面尺寸。

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-}
将图像保存到流，使用指定的页面尺寸。

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-}
将图像保存到流，使用指定的页面尺寸、图像格式和质量。

### getNextImage {#getNextImage-java.lang.String-}
将图像保存到文件，使用默认图像格式 - jpeg。

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-}
<p> 将图像保存为指定的图像格式的文件。 </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@\"D:\\Test\\test.pdf\"); converter.DoConvert(); String prefix = @\"D:\\Test\\\"; String suffix = \".png\"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Png); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-double-double-int-}
<p> 将图像保存为指定的图像格式、尺寸和质量的文件。 </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@\"D:\\Test\\test.pdf\"); converter.doConvert(); String prefix = @\"D:\\Test\\\"; String suffix = \".jpg\"; int imageCount = 1; float pixelX=800f; float pixelY=600f; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-}
将图像保存到文件，使用指定的图像格式和质量。

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-}
<p> 将图像保存为指定的图像格式和尺寸的文件。 </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(\"D:\\\\Test\\\\test.pdf\"); converter.DoConvert(); String prefix = \"D:\\\\Test\\\\\"; String suffix = \".jpg\"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-int-}
<p> 将图像保存为指定的图像格式、尺寸和质量的文件。 </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@\"D:\\Test\\test.pdf\"); converter.doConvert(); String prefix = @\"D:\\Test\\\"; String suffix = \".jpg\"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-}
将图像保存到文件，使用给定的页面尺寸和默认的图像格式 - jpeg。

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-}
将图像保存到文件，使用给定的页面尺寸和图像格式。

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-}
将图像保存到文件，使用给定的页面尺寸、图像格式和质量。

### getPageCount {#getPageCount--}
```
public int getPageCount()
```

获取页面计数。

**Returns:**
int 值

### getPassword {#getPassword--}
```
public String getPassword()
```

获取文档 OwnerPassword。

**Returns:**
字符串值

### getRenderingOptions {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```

获取渲染选项。

**Returns:**
渲染选项。

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

获取转换过程中的分辨率。分辨率越高，转换速度越慢。默认值为 150。

**Returns:**
Resolution 元素

### getStartPage {#getStartPage--}
```
public int getStartPage()
```

获取要转换的起始位置。最小值为 1。

**Returns:**
int 值

### getUserPassword {#getUserPassword--}
```
public String getUserPassword()
```

获取文档 UserPassword。

**Returns:**
字符串值

### hasNextImage {#hasNextImage--}
```
public boolean hasNextImage()
```

指示 PDF 文件是否还有更多图像。

**Returns:**
是否可以获取更多图像，若可以返回 true，否则返回 false。

### isShowHiddenAreas {#isShowHiddenAreas--}
```
@Deprecated public boolean isShowHiddenAreas()
```

获取控制页面隐藏区域可见性的标志。此方法已弃用。

**Returns:**
布尔值

### mergeImages {#mergeImages-java.util.List-com.aspose.pdf.ImageFormat-com.aspose.pdf.facades.ImageMergeMode-java.lang.Integer-java.lang.Integer-}
将图像流列表合并为一个图像流。

### mergeImagesAsTiff {#mergeImagesAsTiff-java.util.List-}
将 TIFF 流列表合并为一个多帧 TIFF 流。

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-}
将 PDF 文档的每页转换为图像，并将图像保存到单个 TIFF 流中。

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.CompressionType-}
将 PDF 文档的每页转换为图像，并将图像保存到单个 TIFF 文件中。

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-}
将 PDF 文档的每页转换为具有指定尺寸的图像，并将图像保存到单个 TIFF 流中。

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.CompressionType-}
将 PDF 文档的每页转换为具有指定尺寸的图像，并将图像保存到单个 TIFF 流中。

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-}
将 PDF 文档的每页转换为具有指定尺寸的图像，并将图像保存到单个 TIFF 流中。

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
将 PDF 文档的每页转换为具有指定尺寸的图像，并将图像保存到单个 TIFF 流中。

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-}
将 PDF 文档的每页转换为具有页面尺寸的图像，并将图像保存到单个 TIFF 流中。

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
将 PDF 文档的每页转换为具有页面尺寸的图像，并将图像保存到单个 TIFF 流中。

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-}
将 PDF 文档的每页转换为图像，并将图像保存到单个 TIFF 流中。

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
将 PDF 文档的每页转换为图像，并将图像保存到单个 TIFF 流中。

### saveAsTIFF {#saveAsTIFF-java.lang.String-}
<p> 将 PDF 文档的每页转换为图像，并将图像保存为单个 TIFF 文件。 </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@\"D:\\Test\\test.pdf\"); converter.doConvert(); converter.saveAsTIFF(@\"D:\\Test\\test.tiff\"); </pre>

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.CompressionType-}
<p> 将 PDF 文档的每页转换为图像，并将图像保存为单个 TIFF 文件。 </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@\"D:\\Test\\test.pdf\"); converter.doConvert(); converter.saveAsTIFF(@\"D:\\Test\\test.tiff\"); </pre>

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-}
将 PDF 文档的每页转换为具有指定尺寸的图像，并将图像保存到单个 TIFF 文件中。

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.CompressionType-}
将 PDF 文档的每页转换为具有指定尺寸的图像，并将图像保存到单个 TIFF 文件中。

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-}
将 PDF 文档的每页转换为具有指定尺寸的图像，并将图像保存到单个 TIFF 文件中。

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
将 PDF 文档的每页转换为具有指定尺寸的图像，并将图像保存到单个 TIFF 文件中。

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-}
将 PDF 文档的每页转换为具有页面尺寸的图像，并将图像保存到单个 TIFF 文件中。

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
将 PDF 文档的每页转换为具有页面尺寸的图像，并将图像保存到单个 TIFF 文件中。

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-}
将 PDF 文档的每页转换为图像，并将图像保存到单个 TIFF 文件中。

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
将 PDF 文档的每页转换为图像，并将图像保存到单个 TIFF 文件中。

### saveAsTIFFClassF {#saveAsTIFFClassF-java.io.OutputStream-}
将 PDF 文档的每页转换为图像，并将图像保存到单个 TIFF ClassF 流中。

### saveAsTIFFClassF {#saveAsTIFFClassF-java.io.OutputStream-int-int-}
将 PDF 文档的每页转换为图像，并将图像保存到单个 TIFF ClassF 流中。

### saveAsTIFFClassF {#saveAsTIFFClassF-java.io.OutputStream-com.aspose.pdf.PageSize-}
将 PDF 文档的每页转换为图像，并将图像保存到单个 TIFF ClassF 流中。

### saveAsTIFFClassF {#saveAsTIFFClassF-java.lang.String-}
<p> 将 PDF 文档的每页转换为图像，并将图像保存为单个 TIFF ClassF 文件。 </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(\"D:\\\\Test\\\\test.pdf\"); converter.doConvert(); converter.saveAsTIFFClassF(\"D:\\\\Test\\\\test.tiff\"); </pre>

### saveAsTIFFClassF {#saveAsTIFFClassF-java.lang.String-int-int-}
<p> 将 PDF 文档的每页转换为图像，并将图像保存为单个 TIFF ClassF 文件。 </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@\"D:\\Test\\test.pdf\"); converter.doConvert(); converter.saveAsTIFFClassF(@\"D:\\Test\\test.tiff\",204,196); </pre>

### saveAsTIFFClassF {#saveAsTIFFClassF-java.lang.String-com.aspose.pdf.PageSize-}
将 PDF 文档的每页转换为图像，并将图像保存为单个 TIFF ClassF 文件。

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
设置页面坐标类型（Media/Crop 框）。默认使用 CropBox 值。

### setEndPage {#setEndPage-int-}
```
public void setEndPage(int value)
```

设置要转换的结束位置。 在调用 setStartPage(int) 之前使用 setEndPage(int)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

设置表单呈现模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 表单呈现模式。 @see FormPresentationMode |

### setPassword {#setPassword-java.lang.String-}
设置文档的 OwnerPassword。

### setRangeOfPages {#setRangeOfPages-int-int-}
```
public void setRangeOfPages(int startPage, int EndPage)
```

设置要转换的页面范围。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startPage |  | int 值 |
| EndPage |  | int 值 |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
设置渲染选项。

### setResolution {#setResolution-com.aspose.pdf.devices.Resolution-}
设置转换期间的分辨率。分辨率越高，转换速度越慢。默认值为 150。

### setShowHiddenAreas {#setShowHiddenAreas-boolean-}
```
@Deprecated public void setShowHiddenAreas(boolean value)
```

已弃用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  |  |

### setStartPage {#setStartPage-int-}
```
public void setStartPage(int value)
```

设置要转换的起始位置。最小值为 1。 在调用 setStartPage(int) 之前使用 setEndPage(int)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setUserPassword {#setUserPassword-java.lang.String-}
设置文档的 UserPassword。
