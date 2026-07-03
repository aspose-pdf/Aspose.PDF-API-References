---
title: PdfConverter
second_title: Aspose.PDF for Java API Reference
description: Represents a class to convert a pdf file's each page to images, supporting BMP, JPEG, PNG and TIFF now. Supported content in pdfs: pictures, form, comment.
type: docs
weight: 390
url: /java/com.aspose.pdf.facades/pdfconverter/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.PdfConverter, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.PdfConverter

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public final class PdfConverter extends Facade
```

Represents a class to convert a pdf file's each page to images, supporting BMP, JPEG, PNG and TIFF now. Supported content in pdfs: pictures, form, comment.

## Constructors

| Constructor | Description |
| --- | --- |
| [PdfConverter](#PdfConverter--) | Initializes new {@code PdfConverter} object. |
| [PdfConverter](#PdfConverter-com.aspose.pdf.IDocument-) | Initializes new {@code PdfConverter} object. |

## Methods

| Method | Description |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.Document-) | Binds a PDF document to the {@link PdfConverter} instance for further processing. |
| [bindPdf](#bindPdf-java.io.InputStream-) | Binds a Pdf Stream for convert. |
| [bindPdf](#bindPdf-java.lang.String-) | Binds a Pdf file for converting. |
| [close](#close--) | Close the instance of PdfConverter and release the resources. |
| [convertPageToPNGMemoryStream](#convertPageToPNGMemoryStream-com.aspose.pdf.Page-) | For internal usage only |
| [dispose](#dispose--) | Close the instance of PdfConverter and release the resources. This method is obsolete, use close() instead. |
| [doConvert](#doConvert--) | <p> Do some initial works for converting a pdf document to images. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.doConvert(); String prefix = "D:\\\\Test\\\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix); imageCount++; } </pre> |
| [getCoordinateType](#getCoordinateType--) | Gets the page coordinate type (Media/Crop boxes). CropBox value is used by default. |
| [getEndPage](#getEndPage--) | Gets end position which you want to convert. |
| [getFormPresentationMode](#getFormPresentationMode--) | Gets form presentation mode. |
| [getNextImage](#getNextImage-java.io.OutputStream-) | Saves image to stream with default image format - jpeg. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-) | Saves image to stream with given image format. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-double-double-int-) | Saves image to stream with the givin image format, size and quality. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-) | Saves image to stream with given image format and quality. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-) | Saves image to stream with the givin image format, size and quality. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-int-) | Saves image to stream with the givin image format, dimensions and quality. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-) | Saves image to stream with given page size. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-) | Saves image to stream with given page size. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-) | Saves image to stream with given page size, image format and quality. |
| [getNextImage](#getNextImage-java.lang.String-) | Saves image to file with default image format - jpeg. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-) | <p> Saves image to file with the givin image format. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.DoConvert(); String prefix = @"D:\\Test\\"; String suffix = ".png"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Png); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-double-double-int-) | <p> Saves image to file with the givin image format, image size, and quality. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); String prefix = @"D:\\Test\\"; String suffix = ".jpg"; int imageCount = 1; float pixelX=800f; float pixelY=600f; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-) | Saves image to file with given image format and quality. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-) | <p> Saves image to file with the given image format and dimensions. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.DoConvert(); String prefix = "D:\\\\Test\\\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-int-) | <p> Saves image to file with the given image format, dimensions and quality. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); String prefix = @"D:\\Test\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-) | Saves image to file with ith given page size and default image format - jpeg. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-) | Saves image to file with given page size and image format. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-) | Saves image to file with given page size, image format and quality. |
| [getPageCount](#getPageCount--) | Gets the page count. |
| [getPassword](#getPassword--) | Gets document OwnerPassword. |
| [getRenderingOptions](#getRenderingOptions--) | Gets rendering options. |
| [getResolution](#getResolution--) | Gets resolution during converting. The higher resolution, the slower converting speed. The default value is 150. |
| [getStartPage](#getStartPage--) | Gets start position which you want to convert. The minimal value is 1. |
| [getUserPassword](#getUserPassword--) | Gets document UserPassword. |
| [hasNextImage](#hasNextImage--) | Indicates whether the pdf file has more images or not. |
| [isShowHiddenAreas](#isShowHiddenAreas--) | Gets flag that controls visibility of hidden areas on the page. Method is Deprecated. |
| [mergeImages](#mergeImages-java.util.List-com.aspose.pdf.ImageFormat-com.aspose.pdf.facades.ImageMergeMode-java.lang.Integer-java.lang.Integer-) | Merges list of image streams as one image stream. |
| [mergeImagesAsTiff](#mergeImagesAsTiff-java.util.List-) | Merges list of tiff streams as one multiple frames tiff stream. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-) | Converts each pages of a pdf document to images and saves images to a single TIFF stream. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.CompressionType-) | Converts each pages of a pdf document to images and saves images to a single TIFF file. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.CompressionType-) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-) | Converts each pages of a pdf document to images with page size and saves images to a single TIFF stream. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | Converts each pages of a pdf document to images with page size and saves images to a single TIFF stream. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-) | Converts each pages of a pdf document to images and saves images to a single TIFF stream. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Converts each pages of a pdf document to images and saves images to a single TIFF stream. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-) | <p> Converts each pages of a pdf document to images and saves images to a single TIFF file. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\\Test\\test.tiff"); </pre> |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.CompressionType-) | <p> Converts each pages of a pdf document to images and saves images to a single TIFF file. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\\Test\\test.tiff"); </pre> |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.CompressionType-) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-) | Converts each pages of a pdf document to images with page size and saves images to a single TIFF file. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | Converts each pages of a pdf document to images with page size and saves images to a single TIFF file. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-) | Converts each pages of a pdf document to images with and saves images to a single TIFF file. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Converts each pages of a pdf document to images with and saves images to a single TIFF file. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.io.OutputStream-) | Converts each pages of a pdf document to images and save images to a single TIFF ClassF stream. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.io.OutputStream-int-int-) | Converts each pages of a pdf document to images and save images to a single TIFF ClassF stream. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.io.OutputStream-com.aspose.pdf.PageSize-) | Converts each pages of a pdf document to images and save images to a single TIFF ClassF stream. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.lang.String-) | <p> Converts each pages of a pdf document to images and save images to a single TIFF ClassF file. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.doConvert(); converter.saveAsTIFFClassF("D:\\\\Test\\\\test.tiff"); </pre> |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.lang.String-int-int-) | <p> Converts each pages of a pdf document to images and save images to a single TIFF ClassF file. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); converter.saveAsTIFFClassF(@"D:\\Test\\test.tiff",204,196); </pre> |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.lang.String-com.aspose.pdf.PageSize-) | Converts each pages of a pdf document to images and save images to a single TIFF ClassF file. |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | Sets the page coordinate type (Media/Crop boxes). CropBox value is used by default. |
| [setEndPage](#setEndPage-int-) | Sets end position which you want to convert. use setEndPage(int) before setStartPage(int) |
| [setFormPresentationMode](#setFormPresentationMode-int-) | Sets form presentation mode. |
| [setPassword](#setPassword-java.lang.String-) | Sets document OwnerPassword. |
| [setRangeOfPages](#setRangeOfPages-int-int-) | Sets range of pages between of which you want to convert. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Sets rendering options. |
| [setResolution](#setResolution-com.aspose.pdf.devices.Resolution-) | Sets resolution during converting. The higher resolution, the slower converting speed. The default value is 150. |
| [setShowHiddenAreas](#setShowHiddenAreas-boolean-) | Deprecated. |
| [setStartPage](#setStartPage-int-) | Sets start position which you want to convert. The minimal value is 1. use setEndPage(int) before setStartPage(int) |
| [setUserPassword](#setUserPassword-java.lang.String-) | Sets document UserPassword. |

### PdfConverter {#PdfConverter--}
```
public PdfConverter()
```

Initializes new {@code PdfConverter} object.

### PdfConverter {#PdfConverter-com.aspose.pdf.IDocument-}
Initializes new {@code PdfConverter} object.

### bindPdf {#bindPdf-com.aspose.pdf.Document-}
Binds a PDF document to the {@link PdfConverter} instance for further processing.

### bindPdf {#bindPdf-java.io.InputStream-}
Binds a Pdf Stream for convert.

### bindPdf {#bindPdf-java.lang.String-}
Binds a Pdf file for converting.

### close {#close--}
```
public void close()
```

Close the instance of PdfConverter and release the resources.

### convertPageToPNGMemoryStream {#convertPageToPNGMemoryStream-com.aspose.pdf.Page-}
For internal usage only

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Close the instance of PdfConverter and release the resources. This method is obsolete, use close() instead.

### doConvert {#doConvert--}
```
public void doConvert()
```

<p> Do some initial works for converting a pdf document to images. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\Test\\test.pdf"); converter.doConvert(); String prefix = "D:\\Test\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix); imageCount++; } </pre>

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

Gets the page coordinate type (Media/Crop boxes). CropBox value is used by default.

**Returns:**
PageCoordinateType element @see PageCoordinateType

### getEndPage {#getEndPage--}
```
public int getEndPage()
```

Gets end position which you want to convert.

**Returns:**
int value

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

Gets form presentation mode.

**Returns:**
form presentation mode. @see FormPresentationMode

### getNextImage {#getNextImage-java.io.OutputStream-}
Saves image to stream with default image format - jpeg.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-}
Saves image to stream with given image format.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-double-double-int-}
Saves image to stream with the givin image format, size and quality.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-}
Saves image to stream with given image format and quality.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-}
Saves image to stream with the givin image format, size and quality.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-int-}
Saves image to stream with the givin image format, dimensions and quality.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-}
Saves image to stream with given page size.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-}
Saves image to stream with given page size.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-}
Saves image to stream with given page size, image format and quality.

### getNextImage {#getNextImage-java.lang.String-}
Saves image to file with default image format - jpeg.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-}
<p> Saves image to file with the givin image format. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.DoConvert(); String prefix = @"D:\Test\"; String suffix = ".png"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Png); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-double-double-int-}
<p> Saves image to file with the givin image format, image size, and quality. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); String prefix = @"D:\Test\"; String suffix = ".jpg"; int imageCount = 1; float pixelX=800f; float pixelY=600f; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-}
Saves image to file with given image format and quality.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-}
<p> Saves image to file with the given image format and dimensions. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\Test\\test.pdf"); converter.DoConvert(); String prefix = "D:\\Test\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-int-}
<p> Saves image to file with the given image format, dimensions and quality. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); String prefix = @"D:\Test\"; String suffix = ".jpg"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-}
Saves image to file with ith given page size and default image format - jpeg.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-}
Saves image to file with given page size and image format.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-}
Saves image to file with given page size, image format and quality.

### getPageCount {#getPageCount--}
```
public int getPageCount()
```

Gets the page count.

**Returns:**
int value

### getPassword {#getPassword--}
```
public String getPassword()
```

Gets document OwnerPassword.

**Returns:**
String value

### getRenderingOptions {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```

Gets rendering options.

**Returns:**
rendering options.

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

Gets resolution during converting. The higher resolution, the slower converting speed. The default value is 150.

**Returns:**
Resolution element

### getStartPage {#getStartPage--}
```
public int getStartPage()
```

Gets start position which you want to convert. The minimal value is 1.

**Returns:**
int value

### getUserPassword {#getUserPassword--}
```
public String getUserPassword()
```

Gets document UserPassword.

**Returns:**
String value

### hasNextImage {#hasNextImage--}
```
public boolean hasNextImage()
```

Indicates whether the pdf file has more images or not.

**Returns:**
Can get more images or not, true if can, or false.

### isShowHiddenAreas {#isShowHiddenAreas--}
```
@Deprecated public boolean isShowHiddenAreas()
```

Gets flag that controls visibility of hidden areas on the page. Method is Deprecated.

**Returns:**
boolean value

### mergeImages {#mergeImages-java.util.List-com.aspose.pdf.ImageFormat-com.aspose.pdf.facades.ImageMergeMode-java.lang.Integer-java.lang.Integer-}
Merges list of image streams as one image stream.

### mergeImagesAsTiff {#mergeImagesAsTiff-java.util.List-}
Merges list of tiff streams as one multiple frames tiff stream.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-}
Converts each pages of a pdf document to images and saves images to a single TIFF stream.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.CompressionType-}
Converts each pages of a pdf document to images and saves images to a single TIFF file.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-}
Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.CompressionType-}
Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-}
Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-}
Converts each pages of a pdf document to images with page size and saves images to a single TIFF stream.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
Converts each pages of a pdf document to images with page size and saves images to a single TIFF stream.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-}
Converts each pages of a pdf document to images and saves images to a single TIFF stream.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Converts each pages of a pdf document to images and saves images to a single TIFF stream.

### saveAsTIFF {#saveAsTIFF-java.lang.String-}
<p> Converts each pages of a pdf document to images and saves images to a single TIFF file. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\Test\test.tiff"); </pre>

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.CompressionType-}
<p> Converts each pages of a pdf document to images and saves images to a single TIFF file. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\Test\test.tiff"); </pre>

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-}
Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file.

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.CompressionType-}
Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file.

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-}
Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file.

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-}
Converts each pages of a pdf document to images with page size and saves images to a single TIFF file.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
Converts each pages of a pdf document to images with page size and saves images to a single TIFF file.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-}
Converts each pages of a pdf document to images with and saves images to a single TIFF file.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Converts each pages of a pdf document to images with and saves images to a single TIFF file.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.io.OutputStream-}
Converts each pages of a pdf document to images and save images to a single TIFF ClassF stream.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.io.OutputStream-int-int-}
Converts each pages of a pdf document to images and save images to a single TIFF ClassF stream.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.io.OutputStream-com.aspose.pdf.PageSize-}
Converts each pages of a pdf document to images and save images to a single TIFF ClassF stream.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.lang.String-}
<p> Converts each pages of a pdf document to images and save images to a single TIFF ClassF file. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\Test\\test.pdf"); converter.doConvert(); converter.saveAsTIFFClassF("D:\\Test\\test.tiff"); </pre>

### saveAsTIFFClassF {#saveAsTIFFClassF-java.lang.String-int-int-}
<p> Converts each pages of a pdf document to images and save images to a single TIFF ClassF file. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); converter.saveAsTIFFClassF(@"D:\Test\test.tiff",204,196); </pre>

### saveAsTIFFClassF {#saveAsTIFFClassF-java.lang.String-com.aspose.pdf.PageSize-}
Converts each pages of a pdf document to images and save images to a single TIFF ClassF file.

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
Sets the page coordinate type (Media/Crop boxes). CropBox value is used by default.

### setEndPage {#setEndPage-int-}
```
public void setEndPage(int value)
```

Sets end position which you want to convert. use setEndPage(int) before setStartPage(int)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

Sets form presentation mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | form presentation mode. @see FormPresentationMode |

### setPassword {#setPassword-java.lang.String-}
Sets document OwnerPassword.

### setRangeOfPages {#setRangeOfPages-int-int-}
```
public void setRangeOfPages(int startPage, int EndPage)
```

Sets range of pages between of which you want to convert.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startPage |  | int value |
| EndPage |  | int value |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
Sets rendering options.

### setResolution {#setResolution-com.aspose.pdf.devices.Resolution-}
Sets resolution during converting. The higher resolution, the slower converting speed. The default value is 150.

### setShowHiddenAreas {#setShowHiddenAreas-boolean-}
```
@Deprecated public void setShowHiddenAreas(boolean value)
```

Deprecated.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  |  |

### setStartPage {#setStartPage-int-}
```
public void setStartPage(int value)
```

Sets start position which you want to convert. The minimal value is 1. use setEndPage(int) before setStartPage(int)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setUserPassword {#setUserPassword-java.lang.String-}
Sets document UserPassword.
