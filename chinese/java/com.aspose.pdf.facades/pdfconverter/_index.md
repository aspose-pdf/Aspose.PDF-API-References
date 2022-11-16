---
title: PdfConverter
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示一个类，用于将每个页面的 pdf 文件转换为现在支持 BMP JPEG PNG 和 TIFF 的图像。
type: docs
weight: 37
url: /zh/java/com.aspose.pdf.facades/pdfconverter/
---
**遗产：**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade)
```
public final class PdfConverter extends Facade
```

表示将pdf文件的每一页转换为图像的类，现在支持BMP、JPEG、PNG和TIFF。 pdf支持的内容：图片、表格、评论。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfConverter()](#PdfConverter--) | 初始化新的 PdfConverter 对象。 |
| [PdfConverter(IDocument document)](#PdfConverter-com.aspose.pdf.IDocument-) | 在文档的基础上初始化新的 PdfConverter 对象。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | 初始化门面。 |
| [bindPdf(InputStream inputStream)](#bindPdf-java.io.InputStream-) | 绑定用于转换的 Pdf 流。 |
| [bindPdf(InputStream srcStream, String password)](#bindPdf-java.io.InputStream-java.lang.String-) | 初始化门面。 |
| [bindPdf(String inputFile)](#bindPdf-java.lang.String-) | 绑定用于转换的 Pdf 文件。 |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | 初始化门面。 |
| [close()](#close--) | 关闭 PdfConverter 实例并释放资源。 |
| [convertPageToPNGMemoryStream(Page page)](#convertPageToPNGMemoryStream-com.aspose.pdf.Page-) | 仅供内部使用 |
| [dispose()](#dispose--) | 关闭 PdfConverter 实例并释放资源。 |
| [doConvert()](#doConvert--) | 做一些将 pdf 文档转换为图像的初始工作。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCoordinateType()](#getCoordinateType--) | 获取页面坐标类型（媒体/裁剪框）。 |
| [getDocument()](#getDocument--) | 获取正在处理的文档外观。 |
| [getEndPage()](#getEndPage--) | 获取要转换的结束位置。 |
| [getFormPresentationMode()](#getFormPresentationMode--) | 获取表单呈现模式。 |
| [getNextImage(OutputStream outputStream)](#getNextImage-java.io.OutputStream-) | 使用默认图像格式 - jpeg 将图像保存到流。 |
| [getNextImage(OutputStream outputStream, ImageType format)](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-) | 使用给定的图像格式将图像保存到流中。 |
| [getNextImage(OutputStream outputStream, ImageType format, double imageWidth, double imageHeight, int quality)](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-double-double-int-) | 使用给定的图像格式、大小和质量将图像保存到流中。 |
| [getNextImage(OutputStream outputStream, ImageType format, int quality)](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-) | 以给定的图像格式和质量将图像保存到流中。 |
| [getNextImage(OutputStream outputStream, ImageType format, int imageWidth, int imageHeight)](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-) | 使用给定的图像格式、大小和质量将图像保存到流中。 |
| [getNextImage(OutputStream outputStream, ImageType format, int imageWidth, int imageHeight, int quality)](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-int-) | 使用给定的图像格式、尺寸和质量将图像保存到流中。 |
| [getNextImage(OutputStream outputStream, PageSize pageSize)](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-) | 以给定的页面大小将图像保存到流中。 |
| [getNextImage(OutputStream outputStream, PageSize pageSize, ImageType format)](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-) | 以给定的页面大小将图像保存到流中。 |
| [getNextImage(OutputStream outputStream, PageSize pageSize, ImageType format, int quality)](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-) | 以给定的页面大小、图像格式和质量将图像保存到流中。 |
| [getNextImage(String outputFile)](#getNextImage-java.lang.String-) | 使用默认图像格式将图像保存到文件 - jpeg。 |
| [getNextImage(String outputFile, ImageType format)](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-) | 使用 givin 图像格式将图像保存到文件。 |
| [getNextImage(String outputFile, ImageType format, double imageWidth, double imageHeight, int quality)](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-double-double-int-) | 使用给定的图像格式、图像大小和质量将图像保存到文件。 |
| [getNextImage(String outputFile, ImageType format, int quality)](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-) | 以给定的图像格式和质量将图像保存到文件。 |
| [getNextImage(String outputFile, ImageType format, int imageWidth, int imageHeight)](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-) | 使用给定的图像格式和尺寸将图像保存到文件。 |
| [getNextImage(String outputFile, ImageType format, int imageWidth, int imageHeight, int quality)](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-int-) | 使用给定的图像格式、尺寸和质量将图像保存到文件。 |
| [getNextImage(String outputFile, PageSize pageSize)](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-) | 使用给定的页面大小和默认图像格式 - jpeg 将图像保存到文件。 |
| [getNextImage(String outputFile, PageSize pageSize, ImageType format)](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-) | 将图像保存到具有给定页面大小和图像格式的文件。 |
| [getNextImage(String outputFile, PageSize pageSize, ImageType format, int quality)](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-) | 以给定的页面大小、图像格式和质量将图像保存到文件。 |
| [getPageCount()](#getPageCount--) | 获取页数。 |
| [getPassword()](#getPassword--) | 获取文档所有者密码。 |
| [getRenderingOptions()](#getRenderingOptions--) | 获取渲染选项。 |
| [getResolution()](#getResolution--) | 在转换过程中获取分辨率。 |
| [getStartPage()](#getStartPage--) | 获取要转换的起始位置。 |
| [getUserPassword()](#getUserPassword--) | 获取文档用户密码。 |
| [hasNextImage()](#hasNextImage--) | 指示 pdf 文件是否包含更多图像。 |
| [hashCode()](#hashCode--) |  |
| [isShowHiddenAreas()](#isShowHiddenAreas--) | 获取控制页面上隐藏区域可见性的标志。 |
| [mergeImages(List<InputStream> inputImagesStreams, int outputImageFormat, int mergeMode, Integer horizontal, Integer vertical)](#mergeImages-java.util.List-java.io.InputStream--int-int-java.lang.Integer-java.lang.Integer-) | 将图像流列表合并为一个图像流。 |
| [mergeImagesAsTiff(List<InputStream> inputImagesStreams)](#mergeImagesAsTiff-java.util.List-java.io.InputStream--) | 将 tiff 流列表合并为一个多帧 tiff 流。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveAsTIFF(OutputStream outputStream)](#saveAsTIFF-java.io.OutputStream-) | 将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF 流。 |
| [saveAsTIFF(OutputStream outputStream, PageSize pageSize)](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-) | 将 pdf 文档的每一页转换为具有页面大小的图像，并将图像保存到单个 TIFF 流。 |
| [saveAsTIFF(OutputStream outputStream, PageSize pageSize, TiffSettings settings)](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | 将 pdf 文档的每一页转换为具有页面大小的图像，并将图像保存到单个 TIFF 流。 |
| [saveAsTIFF(OutputStream outputStream, TiffSettings settings)](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-) | 将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF 流。 |
| [saveAsTIFF(OutputStream outputStream, TiffSettings settings, IIndexBitmapConverter converter)](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | 将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF 流。 |
| [saveAsTIFF(OutputStream outputStream, int compressionType)](#saveAsTIFF-java.io.OutputStream-int-) | 将 pdf 文档的每一页转换为图像并将图像保存为单个 TIFF 文件。 |
| [saveAsTIFF(OutputStream outputStream, int imageWidth, int imageHeight)](#saveAsTIFF-java.io.OutputStream-int-int-) | 将 pdf 文档的每一页转换为具有尺寸的图像，并将图像保存到单个 TIFF 流。 |
| [saveAsTIFF(OutputStream outputStream, int imageWidth, int imageHeight, TiffSettings settings)](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-) | 将 pdf 文档的每一页转换为具有尺寸的图像，并将图像保存到单个 TIFF 流。 |
| [saveAsTIFF(OutputStream outputStream, int imageWidth, int imageHeight, TiffSettings settings, IIndexBitmapConverter converter)](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | 将 pdf 文档的每一页转换为具有尺寸的图像，并将图像保存到单个 TIFF 流。 |
| [saveAsTIFF(OutputStream outputStream, int imageWidth, int imageHeight, int compressionType)](#saveAsTIFF-java.io.OutputStream-int-int-int-) | 将 pdf 文档的每一页转换为具有尺寸的图像，并将图像保存到单个 TIFF 流。 |
| [saveAsTIFF(String outputFile)](#saveAsTIFF-java.lang.String-) | 将 pdf 文档的每一页转换为图像并将图像保存为单个 TIFF 文件。 |
| [saveAsTIFF(String outputFile, PageSize pageSize)](#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-) | 将 pdf 文档的每一页转换为具有页面大小的图像，并将图像保存为单个 TIFF 文件。 |
| [saveAsTIFF(String outputFile, PageSize pageSize, TiffSettings settings)](#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | 将 pdf 文档的每一页转换为具有页面大小的图像，并将图像保存为单个 TIFF 文件。 |
| [saveAsTIFF(String outputFile, TiffSettings settings)](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-) | 将 pdf 文档的每一页转换为图像，并将图像保存到单个 TIFF 文件。 |
| [saveAsTIFF(String outputFile, TiffSettings settings, IIndexBitmapConverter converter)](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | 将 pdf 文档的每一页转换为图像，并将图像保存到单个 TIFF 文件。 |
| [saveAsTIFF(String outputFile, int compressionType)](#saveAsTIFF-java.lang.String-int-) | 将 pdf 文档的每一页转换为图像并将图像保存为单个 TIFF 文件。 |
| [saveAsTIFF(String outputFile, int imageWidth, int imageHeight)](#saveAsTIFF-java.lang.String-int-int-) | 将 pdf 文档的每一页转换为具有尺寸的图像，并将图像保存为单个 TIFF 文件。 |
| [saveAsTIFF(String outputFile, int imageWidth, int imageHeight, TiffSettings settings)](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-) | 将 pdf 文档的每一页转换为具有尺寸的图像，并将图像保存为单个 TIFF 文件。 |
| [saveAsTIFF(String outputFile, int imageWidth, int imageHeight, TiffSettings settings, IIndexBitmapConverter converter)](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | 将 pdf 文档的每一页转换为具有尺寸的图像，并将图像保存为单个 TIFF 文件。 |
| [saveAsTIFF(String outputFile, int imageWidth, int imageHeight, int compressionType)](#saveAsTIFF-java.lang.String-int-int-int-) | 将 pdf 文档的每一页转换为具有尺寸的图像，并将图像保存为单个 TIFF 文件。 |
| [saveAsTIFFClassF(OutputStream outputStream)](#saveAsTIFFClassF-java.io.OutputStream-) | 将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF ClassF 流。 |
| [saveAsTIFFClassF(OutputStream outputStream, PageSize pageSize)](#saveAsTIFFClassF-java.io.OutputStream-com.aspose.pdf.PageSize-) | 将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF ClassF 流。 |
| [saveAsTIFFClassF(OutputStream outputStream, int imageWidth, int imageHeight)](#saveAsTIFFClassF-java.io.OutputStream-int-int-) | 将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF ClassF 流。 |
| [saveAsTIFFClassF(String outputFile)](#saveAsTIFFClassF-java.lang.String-) | 将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF ClassF 文件。 |
| [saveAsTIFFClassF(String outputFile, PageSize pageSize)](#saveAsTIFFClassF-java.lang.String-com.aspose.pdf.PageSize-) | 将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF ClassF 文件。 |
| [saveAsTIFFClassF(String outputFile, int imageWidth, int imageHeight)](#saveAsTIFFClassF-java.lang.String-int-int-) | 将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF ClassF 文件。 |
| [setCoordinateType(int value)](#setCoordinateType-int-) | 设置页面坐标类型（媒体/裁剪框）。 |
| [setEndPage(int value)](#setEndPage-int-) | 设置要转换的结束位置。 |
| [setFormPresentationMode(int value)](#setFormPresentationMode-int-) | 设置表单呈现模式。 |
| [setPassword(String value)](#setPassword-java.lang.String-) | 设置文档所有者密码。 |
| [setRangeOfPages(int startPage, int EndPage)](#setRangeOfPages-int-int-) | 设置要在其间转换的页面范围。 |
| [setRenderingOptions(RenderingOptions value)](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | 设置渲染选项。 |
| [setResolution(Resolution value)](#setResolution-com.aspose.pdf.devices.Resolution-) | 在转换期间设置分辨率。 |
| [setShowHiddenAreas(boolean value)](#setShowHiddenAreas-boolean-) |  |
| [setStartPage(int value)](#setStartPage-int-) | 设置要转换的起始位置。 |
| [setUserPassword(String value)](#setUserPassword-java.lang.String-) | 设置文档用户密码。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfConverter() {#PdfConverter--}
```
public PdfConverter()
```


初始化新的 PdfConverter 对象。

### PdfConverter(IDocument document) {#PdfConverter-com.aspose.pdf.IDocument-}
```
public PdfConverter(IDocument document)
```


在文档的基础上初始化新的 PdfConverter 对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | pdf文档。 |

### bindPdf(IDocument srcDoc) {#bindPdf-com.aspose.pdf.IDocument-}
```
public void bindPdf(IDocument srcDoc)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcDoc | [IDocument](../../com.aspose.pdf/idocument) | 文档对象。 |

### bindPdf(InputStream inputStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream inputStream)
```


绑定用于转换的 Pdf 流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | pdf流。 |

### bindPdf(InputStream srcStream, String password) {#bindPdf-java.io.InputStream-java.lang.String-}
```
public void bindPdf(InputStream srcStream, String password)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcStream | java.io.InputStream | PDF文件流。 |
| password | java.lang.String | PDF文档的密码。 |

### bindPdf(String inputFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String inputFile)
```


绑定用于转换的 Pdf 文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | pdf文件。 |

### bindPdf(String srcFile, String password) {#bindPdf-java.lang.String-java.lang.String-}
```
public void bindPdf(String srcFile, String password)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcFile | java.lang.String | PDF文件 |
| password | java.lang.String | PDF文档的密码。 |

### close() {#close--}
```
public void close()
```


关闭 PdfConverter 实例并释放资源。

### convertPageToPNGMemoryStream(Page page) {#convertPageToPNGMemoryStream-com.aspose.pdf.Page-}
```
public System.IO.MemoryStream convertPageToPNGMemoryStream(Page page)
```


仅供内部使用

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | 内部对象 |

**退货：**
com.aspose.ms.System.IO.MemoryStream - 内部对象
### dispose() {#dispose--}
```
public void dispose()
```


关闭 PdfConverter 实例并释放资源。

此方法已过时，请改用 close() 。

### doConvert() {#doConvert--}
```
public void doConvert()
```


做一些将 pdf 文档转换为图像的初始工作。

--------------------

```
PdfConverter converter = new PdfConverter();
  converter.bindPdf("D:\\Test\\test.pdf");
  converter.doConvert();
  String prefix = "D:\\Test\\";
  String suffix = ".jpg";
  int imageCount = 1;
  while (converter.hasNextImage())
  {
  	converter.getNextImage(prefix + imageCount + suffix);
  	imageCount++;
  }
```

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**退货：**
布尔值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getCoordinateType() {#getCoordinateType--}
```
public int getCoordinateType()
```


获取页面坐标类型（媒体/裁剪框）。默认使用 CropBox 值。

**退货：**
int - PageCoordinateType 元素
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


获取正在处理的文档外观。

**退货：**
[IDocument](../../com.aspose.pdf/idocument) IDocument 元素
### getEndPage() {#getEndPage--}
```
public int getEndPage()
```


获取要转换的结束位置。

**退货：**
int - 整数值
### getFormPresentationMode() {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```


获取表单呈现模式。

**退货：**
int - 表单呈现模式。
### getNextImage(OutputStream outputStream) {#getNextImage-java.io.OutputStream-}
```
public void getNextImage(OutputStream outputStream)
```


使用默认图像格式 - jpeg 将图像保存到流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 保存图像的流。 |

### getNextImage(OutputStream outputStream, ImageType format) {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-}
```
public void getNextImage(OutputStream outputStream, ImageType format)
```


使用给定的图像格式将图像保存到流中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 保存图像的流。 |
| format | [ImageType](../../com.aspose.pdf/imagetype) | 图片的格式。 |

### getNextImage(OutputStream outputStream, ImageType format, double imageWidth, double imageHeight, int quality) {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-double-double-int-}
```
public void getNextImage(OutputStream outputStream, ImageType format, double imageWidth, double imageHeight, int quality)
```


使用给定的图像格式、大小和质量将图像保存到流中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 保存图像的流。 |
| format | [ImageType](../../com.aspose.pdf/imagetype) | 图片的格式。 |
| imageWidth | double | 图片的宽度，单位是像素。 |
| imageHeight | double | 图像高度，单位为像素。 |
| quality | int | Jpeg 文件的质量 (0~100)，0 最低，100 最高 |

### getNextImage(OutputStream outputStream, ImageType format, int quality) {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-}
```
public void getNextImage(OutputStream outputStream, ImageType format, int quality)
```


以给定的图像格式和质量将图像保存到流中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 保存图像的流。 |
| format | [ImageType](../../com.aspose.pdf/imagetype) | 图片的格式。 |
| quality | int | Jpeg 文件的质量 (0~100)，0 最低，100 最高 |

### getNextImage(OutputStream outputStream, ImageType format, int imageWidth, int imageHeight) {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-}
```
public void getNextImage(OutputStream outputStream, ImageType format, int imageWidth, int imageHeight)
```


使用给定的图像格式、大小和质量将图像保存到流中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 保存图像的流。 |
| format | [ImageType](../../com.aspose.pdf/imagetype) | 图片的格式。 |
| imageWidth | int | 图片的宽度，单位是像素。 |
| imageHeight | int | 图像高度，单位为像素。 |

### getNextImage(OutputStream outputStream, ImageType format, int imageWidth, int imageHeight, int quality) {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-int-}
```
public void getNextImage(OutputStream outputStream, ImageType format, int imageWidth, int imageHeight, int quality)
```


使用给定的图像格式、尺寸和质量将图像保存到流中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 保存图像的流。 |
| format | [ImageType](../../com.aspose.pdf/imagetype) | 图片的格式。 |
| imageWidth | int | 图片的宽度，单位是像素。 |
| imageHeight | int | 图像高度，单位为像素。 |
| quality | int | Jpeg 文件的质量 (0~100)，0 最低，100 最高 |

### getNextImage(OutputStream outputStream, PageSize pageSize) {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-}
```
public void getNextImage(OutputStream outputStream, PageSize pageSize)
```


以给定的页面大小将图像保存到流中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 保存图像的流。 |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | 图像的页面大小。 |

### getNextImage(OutputStream outputStream, PageSize pageSize, ImageType format) {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-}
```
public void getNextImage(OutputStream outputStream, PageSize pageSize, ImageType format)
```


以给定的页面大小将图像保存到流中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 保存图像的流。 |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | 图像的页面大小。 |
| format | [ImageType](../../com.aspose.pdf/imagetype) | 图片的格式。 |

### getNextImage(OutputStream outputStream, PageSize pageSize, ImageType format, int quality) {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-}
```
public void getNextImage(OutputStream outputStream, PageSize pageSize, ImageType format, int quality)
```


以给定的页面大小、图像格式和质量将图像保存到流中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 保存图像的流。 |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | 图像的页面大小。 |
| format | [ImageType](../../com.aspose.pdf/imagetype) | 图片的格式。 |
| quality | int | Jpeg 文件的质量 (0~100)，0 最低，100 最高 |

### getNextImage(String outputFile) {#getNextImage-java.lang.String-}
```
public void getNextImage(String outputFile)
```


使用默认图像格式将图像保存到文件 - jpeg。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | java.lang.String | 保存图像的文件路径和名称。 |

### getNextImage(String outputFile, ImageType format) {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-}
```
public void getNextImage(String outputFile, ImageType format)
```


使用 givin 图像格式将图像保存到文件。

--------------------

```
PdfConverter converter = new PdfConverter();
  converter.bindPdf(@"D:\Test\test.pdf");
  converter.DoConvert();
  String prefix = @"D:\Test\";
  String suffix = ".png";
  int imageCount = 1;
  while (converter.HasNextImage())
  {
  	converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Png);
  	imageCount++;
  }
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | java.lang.String | 保存图像的文件路径和名称。 |
| format | [ImageType](../../com.aspose.pdf/imagetype) | 图片的格式。 |

### getNextImage(String outputFile, ImageType format, double imageWidth, double imageHeight, int quality) {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-double-double-int-}
```
public void getNextImage(String outputFile, ImageType format, double imageWidth, double imageHeight, int quality)
```


使用给定的图像格式、图像大小和质量将图像保存到文件。

--------------------

```
PdfConverter converter = new PdfConverter();
  converter.bindPdf(@"D:\Test\test.pdf");
  converter.doConvert();
  String prefix = @"D:\Test\";
  String suffix = ".jpg";
  int imageCount = 1;
  float pixelX=800f;
  float pixelY=600f;
  while (converter.HasNextImage())
  {
  	converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50);
  	imageCount++;
  }
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | java.lang.String | 保存图像的文件路径和名称。 |
| format | [ImageType](../../com.aspose.pdf/imagetype) | 图片的格式。 |
| imageWidth | double | 图片的宽度，单位是像素。 |
| imageHeight | double | 图片的高度，单位是像素.. |
| quality | int | Jpeg 文件的质量 (0~100)，0 最低，100 最高 |

### getNextImage(String outputFile, ImageType format, int quality) {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-}
```
public void getNextImage(String outputFile, ImageType format, int quality)
```


以给定的图像格式和质量将图像保存到文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | java.lang.String | 保存图像的文件路径和名称。 |
| format | [ImageType](../../com.aspose.pdf/imagetype) | 图片的格式。 |
| quality | int | Jpeg 文件的质量 (0~100)，0 最低，100 最高 |

### getNextImage(String outputFile, ImageType format, int imageWidth, int imageHeight) {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-}
```
public void getNextImage(String outputFile, ImageType format, int imageWidth, int imageHeight)
```


使用给定的图像格式和尺寸将图像保存到文件。

--------------------

```
PdfConverter converter = new PdfConverter();
  converter.bindPdf("D:\\Test\\test.pdf");
  converter.DoConvert();
  String prefix = "D:\\Test\\";
  String suffix = ".jpg";
  int imageCount = 1;
  while (converter.hasNextImage())
  {
  	converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000);
  	imageCount++;
  }
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | java.lang.String | 保存图像的文件路径和名称。 |
| format | [ImageType](../../com.aspose.pdf/imagetype) | 图片的格式。 |
| imageWidth | int | 图片的宽度，单位是像素。 |
| imageHeight | int | 图像高度，单位为像素。 |

### getNextImage(String outputFile, ImageType format, int imageWidth, int imageHeight, int quality) {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-int-}
```
public void getNextImage(String outputFile, ImageType format, int imageWidth, int imageHeight, int quality)
```


使用给定的图像格式、尺寸和质量将图像保存到文件。

--------------------

```
PdfConverter converter = new PdfConverter();
  converter.bindPdf(@"D:\Test\test.pdf");
  converter.doConvert();
  String prefix = @"D:\Test\";
  String suffix = ".jpg";
  int imageCount = 1;
  while (converter.HasNextImage())
  {
  	converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50);
  	imageCount++;
  }
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | java.lang.String | 保存图像的文件路径和名称。 |
| format | [ImageType](../../com.aspose.pdf/imagetype) | 图片的格式。 |
| imageWidth | int | 图片的宽度，单位是像素。 |
| imageHeight | int | 图像高度，单位为像素。 |
| quality | int | Jpeg 文件的质量 (0~100)，0 最低，100 最高 |

### getNextImage(String outputFile, PageSize pageSize) {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-}
```
public void getNextImage(String outputFile, PageSize pageSize)
```


使用给定的页面大小和默认图像格式 - jpeg 将图像保存到文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | java.lang.String | 保存图像的文件路径和名称。 |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | 图像的页面大小。 |

### getNextImage(String outputFile, PageSize pageSize, ImageType format) {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-}
```
public void getNextImage(String outputFile, PageSize pageSize, ImageType format)
```


将图像保存到具有给定页面大小和图像格式的文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | java.lang.String | 保存图像的文件路径和名称。 |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | 图像的页面大小。 |
| format | [ImageType](../../com.aspose.pdf/imagetype) | 图片的格式。 |

### getNextImage(String outputFile, PageSize pageSize, ImageType format, int quality) {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-}
```
public void getNextImage(String outputFile, PageSize pageSize, ImageType format, int quality)
```


以给定的页面大小、图像格式和质量将图像保存到文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | java.lang.String | 保存图像的文件路径和名称。 |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | 图像的页面大小。 |
| format | [ImageType](../../com.aspose.pdf/imagetype) | 图片的格式。 |
| quality | int | Jpeg 文件的质量 (0~100)，0 最低，100 最高 |

### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


获取页数。

**退货：**
int - 整数值
### getPassword() {#getPassword--}
```
public String getPassword()
```


获取文档所有者密码。

**退货：**
java.lang.String - 字符串值
### getRenderingOptions() {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```


获取渲染选项。

**退货：**
[RenderingOptions](../../com.aspose.pdf/renderingoptions) 渲染选项。
### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


在转换过程中获取分辨率。分辨率越高，转换速度越慢。默认值为 150。

**退货：**
[Resolution](../../com.aspose.pdf.devices/resolution) 分辨率元素
### getStartPage() {#getStartPage--}
```
public int getStartPage()
```


获取要转换的起始位置。最小值为 1。

**退货：**
int - 整数值
### getUserPassword() {#getUserPassword--}
```
public String getUserPassword()
```


获取文档用户密码。

**退货：**
java.lang.String - 字符串值
### hasNextImage() {#hasNextImage--}
```
public boolean hasNextImage()
```


指示 pdf 文件是否包含更多图像。

**退货：**
boolean - 是否可以获取更多图像，如果可以则为 true，否则为 false。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isShowHiddenAreas() {#isShowHiddenAreas--}
```
public boolean isShowHiddenAreas()
```


获取控制页面上隐藏区域可见性的标志。方法已弃用。

**退货：**
boolean - 布尔值
### mergeImages(List<InputStream> inputImagesStreams, int outputImageFormat, int mergeMode, Integer horizontal, Integer vertical) {#mergeImages-java.util.List-java.io.InputStream--int-int-java.lang.Integer-java.lang.Integer-}
```
public static InputStream mergeImages(List<InputStream> inputImagesStreams, int outputImageFormat, int mergeMode, Integer horizontal, Integer vertical)
```


将图像流列表合并为一个图像流。如果使用默认编码为 Jpeg 的不受支持的格式输出流，则支持 png/jpg/tiff 输出格式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputImagesStreams | java.util.List<java.io.InputStream> | 要合并的图像流列表。 |
| outputImageFormat | int | 合并流的图像输出格式。 |
| mergeMode | int | 合并模式。用于 Png/Jpg 格式。 |
| horizontal | java.lang.Integer | 为输出图像流设置画布宽度的水平比率。仅用于带有 ImageMergeMode.Center 的 Png/Jpg 格式。 |
| vertical | java.lang.Integer | 为输出图像流设置画布高度的垂直比率。仅用于带有 ImageMergeMode.Center 的 Png/Jpg 格式。 |

**退货：**
java.io.InputStream - 编码为输出图像格式的图像流。
### mergeImagesAsTiff(List<InputStream> inputImagesStreams) {#mergeImagesAsTiff-java.util.List-java.io.InputStream--}
```
public static InputStream mergeImagesAsTiff(List<InputStream> inputImagesStreams)
```


将 tiff 流列表合并为一个多帧 tiff 流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputImagesStreams | java.util.List<java.io.InputStream> | tiff 流列表。 |

**退货：**
java.io.InputStream - 多帧 tiff 流。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### saveAsTIFF(OutputStream outputStream) {#saveAsTIFF-java.io.OutputStream-}
```
public void saveAsTIFF(OutputStream outputStream)
```


将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF 流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 保存 TIFF 图像的流。 |

### saveAsTIFF(OutputStream outputStream, PageSize pageSize) {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-}
```
public void saveAsTIFF(OutputStream outputStream, PageSize pageSize)
```


将 pdf 文档的每一页转换为具有页面大小的图像，并将图像保存到单个 TIFF 流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 保存 TIFF 图像的流。 |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | 图像的页面大小。 |

### saveAsTIFF(OutputStream outputStream, PageSize pageSize, TiffSettings settings) {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
```
public void saveAsTIFF(OutputStream outputStream, PageSize pageSize, TiffSettings settings)
```


将 pdf 文档的每一页转换为具有页面大小的图像，并将图像保存到单个 TIFF 流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 保存 TIFF 图像的流。 |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | 图像的页面大小。 |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | 定义 TIFF 参数的设置对象。 |

### saveAsTIFF(OutputStream outputStream, TiffSettings settings) {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-}
```
public void saveAsTIFF(OutputStream outputStream, TiffSettings settings)
```


将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF 流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 保存 TIFF 图像的流。 |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | 定义 TIFF 参数的设置对象。 |

### saveAsTIFF(OutputStream outputStream, TiffSettings settings, IIndexBitmapConverter converter) {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
```
public void saveAsTIFF(OutputStream outputStream, TiffSettings settings, IIndexBitmapConverter converter)
```


将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF 流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 保存 TIFF 图像的流。 |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | 定义 TIFF 参数的设置对象。 |
| converter | [IIndexBitmapConverter](../../com.aspose.pdf/iindexbitmapconverter) | 外部转换器 |

### saveAsTIFF(OutputStream outputStream, int compressionType) {#saveAsTIFF-java.io.OutputStream-int-}
```
public void saveAsTIFF(OutputStream outputStream, int compressionType)
```


将 pdf 文档的每一页转换为图像并将图像保存为单个 TIFF 文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 输出流。 |
| compressionType | int | 压缩类型。 |

### saveAsTIFF(OutputStream outputStream, int imageWidth, int imageHeight) {#saveAsTIFF-java.io.OutputStream-int-int-}
```
public void saveAsTIFF(OutputStream outputStream, int imageWidth, int imageHeight)
```


将 pdf 文档的每一页转换为具有尺寸的图像，并将图像保存到单个 TIFF 流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 保存 TIFF 图像的流。 |
| imageWidth | int | 图片的宽度，单位是像素。 |
| imageHeight | int | 图像高度，单位为像素。 |

### saveAsTIFF(OutputStream outputStream, int imageWidth, int imageHeight, TiffSettings settings) {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-}
```
public void saveAsTIFF(OutputStream outputStream, int imageWidth, int imageHeight, TiffSettings settings)
```


将 pdf 文档的每一页转换为具有尺寸的图像，并将图像保存到单个 TIFF 流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 保存 TIFF 图像的流。 |
| imageWidth | int | 图片的宽度，单位是像素。 |
| imageHeight | int | 图像高度，单位为像素。 |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | 定义 TIFF 参数的设置对象。 |

### saveAsTIFF(OutputStream outputStream, int imageWidth, int imageHeight, TiffSettings settings, IIndexBitmapConverter converter) {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
```
public void saveAsTIFF(OutputStream outputStream, int imageWidth, int imageHeight, TiffSettings settings, IIndexBitmapConverter converter)
```


将 pdf 文档的每一页转换为具有尺寸的图像，并将图像保存到单个 TIFF 流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 保存 TIFF 图像的流。 |
| imageWidth | int | 图片的宽度，单位是像素。 |
| imageHeight | int | 图像高度，单位为像素。 |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | 定义 TIFF 参数的设置对象。 |
| converter | [IIndexBitmapConverter](../../com.aspose.pdf/iindexbitmapconverter) | 外部转换器 |

### saveAsTIFF(OutputStream outputStream, int imageWidth, int imageHeight, int compressionType) {#saveAsTIFF-java.io.OutputStream-int-int-int-}
```
public void saveAsTIFF(OutputStream outputStream, int imageWidth, int imageHeight, int compressionType)
```


将 pdf 文档的每一页转换为具有尺寸的图像，并将图像保存到单个 TIFF 流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 保存 TIFF 图像的流。 |
| imageWidth | int | 图片的宽度，单位是像素。 |
| imageHeight | int | 图像高度，单位为像素。 |
| compressionType | int | 压缩类型。 |

### saveAsTIFF(String outputFile) {#saveAsTIFF-java.lang.String-}
```
public void saveAsTIFF(String outputFile)
```


将 pdf 文档的每一页转换为图像并将图像保存为单个 TIFF 文件。

--------------------

```
PdfConverter converter = new PdfConverter();
  converter.bindPdf(@"D:\Test\test.pdf");
  converter.doConvert();
  converter.saveAsTIFF(@"D:\Test\test.tiff");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | java.lang.String | 保存 TIFF 图像的文件。 |

### saveAsTIFF(String outputFile, PageSize pageSize) {#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-}
```
public void saveAsTIFF(String outputFile, PageSize pageSize)
```


将 pdf 文档的每一页转换为具有页面大小的图像，并将图像保存为单个 TIFF 文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | java.lang.String | 保存 TIFF 图像的文件名 |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | 图像的页面大小。 |

### saveAsTIFF(String outputFile, PageSize pageSize, TiffSettings settings) {#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
```
public void saveAsTIFF(String outputFile, PageSize pageSize, TiffSettings settings)
```


将 pdf 文档的每一页转换为具有页面大小的图像，并将图像保存为单个 TIFF 文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | java.lang.String | 保存 TIFF 图像的文件名 |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | 图像的页面大小。 |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | 定义 TIFF 参数的设置对象。 |

### saveAsTIFF(String outputFile, TiffSettings settings) {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-}
```
public void saveAsTIFF(String outputFile, TiffSettings settings)
```


将 pdf 文档的每一页转换为图像，并将图像保存到单个 TIFF 文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | java.lang.String | 保存 TIFF 图像的文件名 |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | 设置。 |

### saveAsTIFF(String outputFile, TiffSettings settings, IIndexBitmapConverter converter) {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
```
public void saveAsTIFF(String outputFile, TiffSettings settings, IIndexBitmapConverter converter)
```


将 pdf 文档的每一页转换为图像，并将图像保存到单个 TIFF 文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | java.lang.String | 保存 TIFF 图像的文件名 |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | 设置。 |
| converter | [IIndexBitmapConverter](../../com.aspose.pdf/iindexbitmapconverter) | 外部转换器 |

### saveAsTIFF(String outputFile, int compressionType) {#saveAsTIFF-java.lang.String-int-}
```
public void saveAsTIFF(String outputFile, int compressionType)
```


将 pdf 文档的每一页转换为图像并将图像保存为单个 TIFF 文件。

--------------------

```
PdfConverter converter = new PdfConverter();
 converter.bindPdf(@"D:\Test\test.pdf");
 converter.doConvert();
 converter.saveAsTIFF(@"D:\Test\test.tiff");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | java.lang.String | 输出文件。 |
| compressionType | int | 压缩类型。 |

### saveAsTIFF(String outputFile, int imageWidth, int imageHeight) {#saveAsTIFF-java.lang.String-int-int-}
```
public void saveAsTIFF(String outputFile, int imageWidth, int imageHeight)
```


将 pdf 文档的每一页转换为具有尺寸的图像，并将图像保存为单个 TIFF 文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | java.lang.String | 保存 TIFF 图像的文件名 |
| imageWidth | int | 图片的宽度，单位是像素。 |
| imageHeight | int | 图像高度，单位为像素。 |

### saveAsTIFF(String outputFile, int imageWidth, int imageHeight, TiffSettings settings) {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-}
```
public void saveAsTIFF(String outputFile, int imageWidth, int imageHeight, TiffSettings settings)
```


将 pdf 文档的每一页转换为具有尺寸的图像，并将图像保存为单个 TIFF 文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | java.lang.String | 保存 TIFF 图像的文件名 |
| imageWidth | int | 图片的宽度，单位是像素。 |
| imageHeight | int | 图像高度，单位为像素。 |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | 定义 TIFF 参数的设置对象。 |

### saveAsTIFF(String outputFile, int imageWidth, int imageHeight, TiffSettings settings, IIndexBitmapConverter converter) {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
```
public void saveAsTIFF(String outputFile, int imageWidth, int imageHeight, TiffSettings settings, IIndexBitmapConverter converter)
```


将 pdf 文档的每一页转换为具有尺寸的图像，并将图像保存为单个 TIFF 文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | java.lang.String | 保存 TIFF 图像的文件名 |
| imageWidth | int | 图片的宽度，单位是像素。 |
| imageHeight | int | 图像高度，单位为像素。 |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | 定义 TIFF 参数的设置对象。 |
| converter | [IIndexBitmapConverter](../../com.aspose.pdf/iindexbitmapconverter) | 外部转换器 |

### saveAsTIFF(String outputFile, int imageWidth, int imageHeight, int compressionType) {#saveAsTIFF-java.lang.String-int-int-int-}
```
public void saveAsTIFF(String outputFile, int imageWidth, int imageHeight, int compressionType)
```


将 pdf 文档的每一页转换为具有尺寸的图像，并将图像保存为单个 TIFF 文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | java.lang.String | 保存 TIFF 图像的文件名 |
| imageWidth | int | 图片的宽度，单位是像素。 |
| imageHeight | int | 图像高度，单位为像素。 |
| compressionType | int | 压缩类型。 |

### saveAsTIFFClassF(OutputStream outputStream) {#saveAsTIFFClassF-java.io.OutputStream-}
```
public void saveAsTIFFClassF(OutputStream outputStream)
```


将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF ClassF 流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 保存 TIFF 图像的流。 |

### saveAsTIFFClassF(OutputStream outputStream, PageSize pageSize) {#saveAsTIFFClassF-java.io.OutputStream-com.aspose.pdf.PageSize-}
```
public void saveAsTIFFClassF(OutputStream outputStream, PageSize pageSize)
```


将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF ClassF 流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 保存 TIFF 图像的流。 |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | 图像的页面大小。 |

### saveAsTIFFClassF(OutputStream outputStream, int imageWidth, int imageHeight) {#saveAsTIFFClassF-java.io.OutputStream-int-int-}
```
public void saveAsTIFFClassF(OutputStream outputStream, int imageWidth, int imageHeight)
```


将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF ClassF 流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 保存 TIFF 图像的流。 |
| imageWidth | int | 图片的宽度，单位是像素。 |
| imageHeight | int | 图像高度，单位为像素。 |

### saveAsTIFFClassF(String outputFile) {#saveAsTIFFClassF-java.lang.String-}
```
public void saveAsTIFFClassF(String outputFile)
```


将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF ClassF 文件。

--------------------

```
PdfConverter converter = new PdfConverter();
  converter.bindPdf("D:\\Test\\test.pdf");
  converter.doConvert();
  converter.saveAsTIFFClassF("D:\\Test\\test.tiff");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | java.lang.String | 保存 TIFF 图像的流。 |

### saveAsTIFFClassF(String outputFile, PageSize pageSize) {#saveAsTIFFClassF-java.lang.String-com.aspose.pdf.PageSize-}
```
public void saveAsTIFFClassF(String outputFile, PageSize pageSize)
```


将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF ClassF 文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | java.lang.String | 保存 TIFF 图像的流。 |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | 图像的页面大小。 |

### saveAsTIFFClassF(String outputFile, int imageWidth, int imageHeight) {#saveAsTIFFClassF-java.lang.String-int-int-}
```
public void saveAsTIFFClassF(String outputFile, int imageWidth, int imageHeight)
```


将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF ClassF 文件。

--------------------

```
PdfConverter converter = new PdfConverter();
  converter.bindPdf(@"D:\Test\test.pdf");
  converter.doConvert();
  converter.saveAsTIFFClassF(@"D:\Test\test.tiff",204,196);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | java.lang.String | 保存 TIFF 图像的流。 |
| imageWidth | int | 图片的宽度，单位是像素。 |
| imageHeight | int | 图像高度，单位为像素。 |

### setCoordinateType(int value) {#setCoordinateType-int-}
```
public void setCoordinateType(int value)
```


设置页面坐标类型（媒体/裁剪框）。默认使用 CropBox 值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | PageCoordinateType 元素 |

### setEndPage(int value) {#setEndPage-int-}
```
public void setEndPage(int value)
```


设置要转换的结束位置。
在 setStartPage(int) 之前使用 setEndPage(int)

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setFormPresentationMode(int value) {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```


设置表单呈现模式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 表格呈现模式。 |

### setPassword(String value) {#setPassword-java.lang.String-}
```
public void setPassword(String value)
```


设置文档所有者密码。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setRangeOfPages(int startPage, int EndPage) {#setRangeOfPages-int-int-}
```
public void setRangeOfPages(int startPage, int EndPage)
```


设置要在其间转换的页面范围。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| startPage | int | 整数值 |
| EndPage | int | 整数值 |

### setRenderingOptions(RenderingOptions value) {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
```
public void setRenderingOptions(RenderingOptions value)
```


设置渲染选项。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [RenderingOptions](../../com.aspose.pdf/renderingoptions) | 渲染选项。 |

### setResolution(Resolution value) {#setResolution-com.aspose.pdf.devices.Resolution-}
```
public void setResolution(Resolution value)
```


在转换期间设置分辨率。分辨率越高，转换速度越慢。默认值为 150。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Resolution](../../com.aspose.pdf.devices/resolution) | 分辨率元素 |

### setShowHiddenAreas(boolean value) {#setShowHiddenAreas-boolean-}
```
public void setShowHiddenAreas(boolean value)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setStartPage(int value) {#setStartPage-int-}
```
public void setStartPage(int value)
```


设置要转换的起始位置。最小值为 1。
在 setStartPage(int) 之前使用 setEndPage(int)

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setUserPassword(String value) {#setUserPassword-java.lang.String-}
```
public void setUserPassword(String value)
```


设置文档用户密码。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
