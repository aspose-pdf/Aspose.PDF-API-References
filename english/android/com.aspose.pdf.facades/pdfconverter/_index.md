---
title: PdfConverter
second_title: Aspose.PDF for Java API Reference
description: Represents a class to convert a pdf files each page to images supporting BMP JPEG PNG and TIFF now.
type: docs
weight: 34
url: /java/com.aspose.pdf.facades/pdfconverter/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade)
```
public final class PdfConverter extends Facade
```

Represents a class to convert a pdf file's each page to images, supporting BMP, JPEG, PNG and TIFF now. Supported content in pdfs: pictures, form, comment.
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfConverter()](#PdfConverter--) | Initializes new  PdfConverter  object. |
| [PdfConverter(IDocument document)](#PdfConverter-com.aspose.pdf.IDocument-) | Initializes new  PdfConverter  object on base of the  document . |
## Methods

| Method | Description |
| --- | --- |
| [getShowHiddenAreas()](#getShowHiddenAreas--) | Gets or sets flag that controls visibility of hidden areas on the page. |
| [setShowHiddenAreas(boolean value)](#setShowHiddenAreas-boolean-) |  |
| [getRenderingOptions()](#getRenderingOptions--) | Gets or sets rendering options. |
| [setRenderingOptions(RenderingOptions value)](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) |  |
| [getFormPresentationMode()](#getFormPresentationMode--) | Gets or sets form presentation mode. |
| [setFormPresentationMode(int value)](#setFormPresentationMode-int-) |  |
| [getResolution()](#getResolution--) | Gets resolution during convertting. |
| [setResolution(Resolution value)](#setResolution-com.aspose.pdf.devices.Resolution-) | Sets resolution during convertting. |
| [getStartPage()](#getStartPage--) | Gets start position which you want to convert. |
| [setStartPage(int value)](#setStartPage-int-) | Sets start position which you want to convert. |
| [getEndPage()](#getEndPage--) | Gets end position which you want to convert. |
| [setEndPage(int value)](#setEndPage-int-) | Sets end position which you want to convert. |
| [setRangeOfPages(int startPage, int EndPage)](#setRangeOfPages-int-int-) | Sets range of pages between of which you want to convert. |
| [getPassword()](#getPassword--) | Gets document OwnerPassword. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Sets document OwnerPassword. |
| [getUserPassword()](#getUserPassword--) | Gets document UserPassword. |
| [setUserPassword(String value)](#setUserPassword-java.lang.String-) | Sets document UserPassword. |
| [getPageCount()](#getPageCount--) | Gets the page count. |
| [doConvert()](#doConvert--) | Do some initial works for converting a pdf document to images. |
| [saveAsTIFF(String outputFile)](#saveAsTIFF-java.lang.String-) | Converts each pages of a pdf document to images and saves images to a single TIFF file. |
| [saveAsTIFF(String outputFile, int compressionType)](#saveAsTIFF-java.lang.String-int-) | Converts each pages of a pdf document to images and saves images to a single TIFF file. |
| [saveAsTIFF(String outputFile, int imageWidth, int imageHeight)](#saveAsTIFF-java.lang.String-int-int-) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file. |
| [saveAsTIFF(String outputFile, PageSize pageSize)](#saveAsTIFF-java.lang.String-com.aspose.pdf.facades.PageSize-) | Converts each pages of a pdf document to images with page size and saves images to a single TIFF file. |
| [saveAsTIFF(String outputFile, PageSize pageSize, TiffSettings settings)](#saveAsTIFF-java.lang.String-com.aspose.pdf.facades.PageSize-com.aspose.pdf.devices.TiffSettings-) | Converts each pages of a pdf document to images with page size and saves images to a single TIFF file. |
| [saveAsTIFF(String outputFile, int imageWidth, int imageHeight, int compressionType)](#saveAsTIFF-java.lang.String-int-int-int-) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file. |
| [saveAsTIFF(String outputFile, int imageWidth, int imageHeight, TiffSettings settings)](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file. |
| [saveAsTIFF(String outputFile, int imageWidth, int imageHeight, TiffSettings settings, IIndexBitmapConverter converter)](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file. |
| [saveAsTIFFClassF(String outputFile, int imageWidth, int imageHeight)](#saveAsTIFFClassF-java.lang.String-int-int-) | Converts each pages of a pdf document to images and save images to a single TIFF ClassF file. |
| [saveAsTIFFClassF(String outputFile, PageSize pageSize)](#saveAsTIFFClassF-java.lang.String-com.aspose.pdf.facades.PageSize-) | Converts each pages of a pdf document to images and save images to a single TIFF ClassF file. |
| [saveAsTIFFClassF(OutputStream outputStream, int imageWidth, int imageHeight)](#saveAsTIFFClassF-java.io.OutputStream-int-int-) | Converts each pages of a pdf document to images and save images to a single TIFF ClassF stream. |
| [saveAsTIFFClassF(OutputStream outputStream, PageSize pageSize)](#saveAsTIFFClassF-java.io.OutputStream-com.aspose.pdf.facades.PageSize-) | Converts each pages of a pdf document to images and save images to a single TIFF ClassF stream. |
| [saveAsTIFF(OutputStream outputStream)](#saveAsTIFF-java.io.OutputStream-) | Converts each pages of a pdf document to images and saves images to a single TIFF stream. |
| [saveAsTIFF(OutputStream outputStream, int compressionType)](#saveAsTIFF-java.io.OutputStream-int-) | Converts each pages of a pdf document to images and saves images to a single TIFF file. |
| [saveAsTIFF(OutputStream outputStream, PageSize pageSize)](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.facades.PageSize-) | Converts each pages of a pdf document to images with page size and saves images to a single TIFF stream. |
| [saveAsTIFF(OutputStream outputStream, PageSize pageSize, TiffSettings settings)](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.facades.PageSize-com.aspose.pdf.devices.TiffSettings-) | Converts each pages of a pdf document to images with page size and saves images to a single TIFF stream. |
| [saveAsTIFF(OutputStream outputStream, int imageWidth, int imageHeight)](#saveAsTIFF-java.io.OutputStream-int-int-) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream. |
| [saveAsTIFF(OutputStream outputStream, int imageWidth, int imageHeight, int compressionType)](#saveAsTIFF-java.io.OutputStream-int-int-int-) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream. |
| [saveAsTIFF(OutputStream outputStream, int imageWidth, int imageHeight, TiffSettings settings)](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream. |
| [saveAsTIFF(OutputStream outputStream, int imageWidth, int imageHeight, TiffSettings settings, IIndexBitmapConverter converter)](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream. |
| [hasNextImage()](#hasNextImage--) | Indicates whether the pdf file has more images or not. |
| [getNextImage(String outputFile)](#getNextImage-java.lang.String-) | Saves image to file with default image format - jpeg. |
| [getNextImage(String outputFile, PageSize pageSize)](#getNextImage-java.lang.String-com.aspose.pdf.facades.PageSize-) | Saves image to file with ith given page size and default image format - jpeg. |
| [getNextImage(String outputFile, System.Drawing.Imaging.ImageFormat format)](#getNextImage-java.lang.String-com.aspose.ms.System.Drawing.Imaging.ImageFormat-) | Saves image to file with the givin image format. |
| [getNextImage(String outputFile, PageSize pageSize, System.Drawing.Imaging.ImageFormat format)](#getNextImage-java.lang.String-com.aspose.pdf.facades.PageSize-com.aspose.ms.System.Drawing.Imaging.ImageFormat-) | Saves image to file with given page size and image format. |
| [getNextImage(OutputStream outputStream)](#getNextImage-java.io.OutputStream-) | Saves image to stream with default image format - jpeg. |
| [getNextImage(OutputStream outputStream, PageSize pageSize)](#getNextImage-java.io.OutputStream-com.aspose.pdf.facades.PageSize-) | Saves image to stream with given page size. |
| [getNextImage(OutputStream outputStream, System.Drawing.Imaging.ImageFormat format)](#getNextImage-java.io.OutputStream-com.aspose.ms.System.Drawing.Imaging.ImageFormat-) | Saves image to stream with given image format. |
| [getNextImage(OutputStream outputStream, PageSize pageSize, System.Drawing.Imaging.ImageFormat format)](#getNextImage-java.io.OutputStream-com.aspose.pdf.facades.PageSize-com.aspose.ms.System.Drawing.Imaging.ImageFormat-) | Saves image to stream with given page size. |
| [getNextImage(String outputFile, System.Drawing.Imaging.ImageFormat format, int imageWidth, int imageHeight, int quality)](#getNextImage-java.lang.String-com.aspose.ms.System.Drawing.Imaging.ImageFormat-int-int-int-) | Saves image to file with the given image format, dimensions and quality. |
| [getNextImage(OutputStream outputStream, System.Drawing.Imaging.ImageFormat format, int imageWidth, int imageHeight, int quality)](#getNextImage-java.io.OutputStream-com.aspose.ms.System.Drawing.Imaging.ImageFormat-int-int-int-) | Saves image to stream with the givin image format, dimensions and quality. |
| [getNextImage(String outputFile, System.Drawing.Imaging.ImageFormat format, double imageWidth, double imageHeight, int quality)](#getNextImage-java.lang.String-com.aspose.ms.System.Drawing.Imaging.ImageFormat-double-double-int-) | Saves image to file with the givin image format, image size, and quality. |
| [getNextImage(OutputStream outputStream, System.Drawing.Imaging.ImageFormat format, double imageWidth, double imageHeight, int quality)](#getNextImage-java.io.OutputStream-com.aspose.ms.System.Drawing.Imaging.ImageFormat-double-double-int-) | Saves image to stream with the givin image format, size and quality. |
| [bindPdf(String inputFile)](#bindPdf-java.lang.String-) | Binds a Pdf file for converting. |
| [bindPdf(InputStream inputStream)](#bindPdf-java.io.InputStream-) | Binds a Pdf Stream for convert. |
| [close()](#close--) | Close the instance of PdfConverter and release the resources. |
| [saveAsTIFFClassF(String outputFile)](#saveAsTIFFClassF-java.lang.String-) | Converts each pages of a pdf document to images and save images to a single TIFF ClassF file. |
| [saveAsTIFFClassF(OutputStream outputStream)](#saveAsTIFFClassF-java.io.OutputStream-) | Converts each pages of a pdf document to images and save images to a single TIFF ClassF stream. |
| [saveAsTIFF(String outputFile, TiffSettings settings)](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-) | Converts each pages of a pdf document to images with and saves images to a single TIFF file. |
| [saveAsTIFF(String outputFile, TiffSettings settings, IIndexBitmapConverter converter)](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Converts each pages of a pdf document to images with and saves images to a single TIFF file. |
| [saveAsTIFF(OutputStream outputStream, TiffSettings settings)](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-) | Converts each pages of a pdf document to images and saves images to a single TIFF stream. |
| [saveAsTIFF(OutputStream outputStream, TiffSettings settings, IIndexBitmapConverter converter)](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Converts each pages of a pdf document to images and saves images to a single TIFF stream. |
| [getNextImage(String outputFile, System.Drawing.Imaging.ImageFormat format, int imageWidth, int imageHeight)](#getNextImage-java.lang.String-com.aspose.ms.System.Drawing.Imaging.ImageFormat-int-int-) | Saves image to file with the given image format and dimensions. |
| [getNextImage(OutputStream outputStream, System.Drawing.Imaging.ImageFormat format, int imageWidth, int imageHeight)](#getNextImage-java.io.OutputStream-com.aspose.ms.System.Drawing.Imaging.ImageFormat-int-int-) | Saves image to stream with the givin image format, size and quality. |
| [getNextImage(OutputStream outputStream, System.Drawing.Imaging.ImageFormat format, int quality)](#getNextImage-java.io.OutputStream-com.aspose.ms.System.Drawing.Imaging.ImageFormat-int-) | Saves image to stream with given image format and quality. |
| [getNextImage(OutputStream outputStream, PageSize pageSize, System.Drawing.Imaging.ImageFormat format, int quality)](#getNextImage-java.io.OutputStream-com.aspose.pdf.facades.PageSize-com.aspose.ms.System.Drawing.Imaging.ImageFormat-int-) | Saves image to stream with given page size, image format and quality. |
| [getNextImage(String outputFile, System.Drawing.Imaging.ImageFormat format, int quality)](#getNextImage-java.lang.String-com.aspose.ms.System.Drawing.Imaging.ImageFormat-int-) | Saves image to file with given image format and quality. |
| [getNextImage(String outputFile, PageSize pageSize, System.Drawing.Imaging.ImageFormat format, int quality)](#getNextImage-java.lang.String-com.aspose.pdf.facades.PageSize-com.aspose.ms.System.Drawing.Imaging.ImageFormat-int-) | Saves image to file with given page size, image format and quality. |
| [dispose()](#dispose--) |  |
### PdfConverter() {#PdfConverter--}
```
public PdfConverter()
```


Initializes new  PdfConverter  object.

### PdfConverter(IDocument document) {#PdfConverter-com.aspose.pdf.IDocument-}
```
public PdfConverter(IDocument document)
```


Initializes new  PdfConverter  object on base of the  document .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Pdf document. |

### getShowHiddenAreas() {#getShowHiddenAreas--}
```
public boolean getShowHiddenAreas()
```


Gets or sets flag that controls visibility of hidden areas on the page.

**Returns:**
boolean
### setShowHiddenAreas(boolean value) {#setShowHiddenAreas-boolean-}
```
public void setShowHiddenAreas(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRenderingOptions() {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```


Gets or sets rendering options.

**Returns:**
[RenderingOptions](../../com.aspose.pdf/renderingoptions)
### setRenderingOptions(RenderingOptions value) {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
```
public void setRenderingOptions(RenderingOptions value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RenderingOptions](../../com.aspose.pdf/renderingoptions) |  |

### getFormPresentationMode() {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```


Gets or sets form presentation mode.

**Returns:**
int
### setFormPresentationMode(int value) {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


Gets resolution during convertting. The higher resolution, the slower convertting speed. The default value is 150.

**Returns:**
[Resolution](../../com.aspose.pdf.devices/resolution)
### setResolution(Resolution value) {#setResolution-com.aspose.pdf.devices.Resolution-}
```
public void setResolution(Resolution value)
```


Sets resolution during convertting. The higher resolution, the slower convertting speed. The default value is 150.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Resolution](../../com.aspose.pdf.devices/resolution) |  |

### getStartPage() {#getStartPage--}
```
public int getStartPage()
```


Gets start position which you want to convert. The minimal value is 1.

**Returns:**
int
### setStartPage(int value) {#setStartPage-int-}
```
public void setStartPage(int value)
```


Sets start position which you want to convert. The minimal value is 1.
use setEndPage(int) before setStartPage(int)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEndPage() {#getEndPage--}
```
public int getEndPage()
```


Gets end position which you want to convert.

**Returns:**
int
### setEndPage(int value) {#setEndPage-int-}
```
public void setEndPage(int value)
```


Sets end position which you want to convert.
use setEndPage(int) before setStartPage(int)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setRangeOfPages(int startPage, int EndPage) {#setRangeOfPages-int-int-}
```
public void setRangeOfPages(int startPage, int EndPage)
```


Sets range of pages between of which you want to convert.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startPage | int |  |
| EndPage | int |  |

### getPassword() {#getPassword--}
```
public String getPassword()
```


Gets document OwnerPassword.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public void setPassword(String value)
```


Sets document OwnerPassword.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getUserPassword() {#getUserPassword--}
```
public String getUserPassword()
```


Gets document UserPassword.

**Returns:**
java.lang.String
### setUserPassword(String value) {#setUserPassword-java.lang.String-}
```
public void setUserPassword(String value)
```


Sets document UserPassword.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Gets the page count.

**Returns:**
int
### doConvert() {#doConvert--}
```
public void doConvert()
```


Do some initial works for converting a pdf document to images.

--------------------

> ```
> [C#]
>   PdfConverter converter = new PdfConverter();
>   converter.BindPdf(@"D:\Test\test.pdf");
>   converter.DoConvert();
>   String prefix = @"D:\Test\";
>   String suffix = ".jpg";
>   int imageCount = 1;
>   while (converter.HasNextImage())
>   {
>   	converter.GetNextImage(prefix + imageCount + suffix);
>   	imageCount++;
>   }
>  	
>  	[Visual Basic]
>   Dim converter As PdfConverter =  New PdfConverter() 
>   converter.BindPdf("D:\Test\test.pdf")
>   converter.DoConvert()
>   Dim prefix As String =  "D:\Test\" 
>   Dim suffix As String =  ".jpg" 
>   Dim imageCount As Integer =  1 
>   While converter.HasNextImage()
>   	converter.GetNextImage(prefix + imageCount + suffix)
>   	imageCount = imageCount + 1
>   End While
> ```

### saveAsTIFF(String outputFile) {#saveAsTIFF-java.lang.String-}
```
public void saveAsTIFF(String outputFile)
```


Converts each pages of a pdf document to images and saves images to a single TIFF file.

--------------------

> ```
> PdfConverter converter = new PdfConverter();
>   converter.bindPdf(@"D:\Test\test.pdf");
>   converter.doConvert();
>   converter.saveAsTIFF(@"D:\Test\test.tiff");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | java.lang.String | The file to save the TIFF image. |

### saveAsTIFF(String outputFile, int compressionType) {#saveAsTIFF-java.lang.String-int-}
```
public void saveAsTIFF(String outputFile, int compressionType)
```


Converts each pages of a pdf document to images and saves images to a single TIFF file.

--------------------

> ```
> PdfConverter converter = new PdfConverter();
>  converter.bindPdf(@"D:\Test\test.pdf");
>  converter.doConvert();
>  converter.saveAsTIFF(@"D:\Test\test.tiff");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | java.lang.String | The output file. |
| compressionType | int | Type of the compression. |

### saveAsTIFF(String outputFile, int imageWidth, int imageHeight) {#saveAsTIFF-java.lang.String-int-int-}
```
public void saveAsTIFF(String outputFile, int imageWidth, int imageHeight)
```


Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | java.lang.String | The file name to save the TIFF image |
| imageWidth | int | The image width, the unit is pixel. |
| imageHeight | int | The image height, the unit is pixel. |

### saveAsTIFF(String outputFile, PageSize pageSize) {#saveAsTIFF-java.lang.String-com.aspose.pdf.facades.PageSize-}
```
public void saveAsTIFF(String outputFile, PageSize pageSize)
```


Converts each pages of a pdf document to images with page size and saves images to a single TIFF file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | java.lang.String | The file name to save the TIFF image |
| pageSize | [PageSize](../../com.aspose.pdf.facades/pagesize) | The page size of the image. |

### saveAsTIFF(String outputFile, PageSize pageSize, TiffSettings settings) {#saveAsTIFF-java.lang.String-com.aspose.pdf.facades.PageSize-com.aspose.pdf.devices.TiffSettings-}
```
public void saveAsTIFF(String outputFile, PageSize pageSize, TiffSettings settings)
```


Converts each pages of a pdf document to images with page size and saves images to a single TIFF file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | java.lang.String | The file name to save the TIFF image |
| pageSize | [PageSize](../../com.aspose.pdf.facades/pagesize) | The page size of the image. |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Settings. |

### saveAsTIFF(String outputFile, int imageWidth, int imageHeight, int compressionType) {#saveAsTIFF-java.lang.String-int-int-int-}
```
public void saveAsTIFF(String outputFile, int imageWidth, int imageHeight, int compressionType)
```


Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | java.lang.String | The file name to save the TIFF image |
| imageWidth | int | The image width, the unit is pixel. |
| imageHeight | int | The image height, the unit is pixel. |
| compressionType | int | Type of the compression. |

### saveAsTIFF(String outputFile, int imageWidth, int imageHeight, TiffSettings settings) {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-}
```
public void saveAsTIFF(String outputFile, int imageWidth, int imageHeight, TiffSettings settings)
```


Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | java.lang.String | The file name to save the TIFF image |
| imageWidth | int | The image width, the unit is pixel. |
| imageHeight | int | The image height, the unit is pixel. |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Settings. |

### saveAsTIFF(String outputFile, int imageWidth, int imageHeight, TiffSettings settings, IIndexBitmapConverter converter) {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
```
public void saveAsTIFF(String outputFile, int imageWidth, int imageHeight, TiffSettings settings, IIndexBitmapConverter converter)
```


Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | java.lang.String | The file name to save the TIFF image |
| imageWidth | int | The image width, the unit is pixel. |
| imageHeight | int | The image height, the unit is pixel. |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Settings. |
| converter | [IIndexBitmapConverter](../../com.aspose.pdf/iindexbitmapconverter) | External converter |

### saveAsTIFFClassF(String outputFile, int imageWidth, int imageHeight) {#saveAsTIFFClassF-java.lang.String-int-int-}
```
public void saveAsTIFFClassF(String outputFile, int imageWidth, int imageHeight)
```


Converts each pages of a pdf document to images and save images to a single TIFF ClassF file.

--------------------

> ```
> PdfConverter converter = new PdfConverter();
>   converter.bindPdf(@"D:\Test\test.pdf");
>   converter.doConvert();
>   converter.saveAsTIFFClassF(@"D:\Test\test.tiff",204,196);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | java.lang.String | The stream to save the TIFF image. |
| imageWidth | int | The image width, the unit is pixel. |
| imageHeight | int | The image height, the unit is pixel. |

### saveAsTIFFClassF(String outputFile, PageSize pageSize) {#saveAsTIFFClassF-java.lang.String-com.aspose.pdf.facades.PageSize-}
```
public void saveAsTIFFClassF(String outputFile, PageSize pageSize)
```


Converts each pages of a pdf document to images and save images to a single TIFF ClassF file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | java.lang.String | The stream to save the TIFF image. |
| pageSize | [PageSize](../../com.aspose.pdf.facades/pagesize) | The page size of the image. |

### saveAsTIFFClassF(OutputStream outputStream, int imageWidth, int imageHeight) {#saveAsTIFFClassF-java.io.OutputStream-int-int-}
```
public void saveAsTIFFClassF(OutputStream outputStream, int imageWidth, int imageHeight)
```


Converts each pages of a pdf document to images and save images to a single TIFF ClassF stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | The stream to save the TIFF image. |
| imageWidth | int | The image width, the unit is pixel. |
| imageHeight | int | The image height, the unit is pixel. |

### saveAsTIFFClassF(OutputStream outputStream, PageSize pageSize) {#saveAsTIFFClassF-java.io.OutputStream-com.aspose.pdf.facades.PageSize-}
```
public void saveAsTIFFClassF(OutputStream outputStream, PageSize pageSize)
```


Converts each pages of a pdf document to images and save images to a single TIFF ClassF stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | The stream to save the TIFF image. |
| pageSize | [PageSize](../../com.aspose.pdf.facades/pagesize) | The page size of the image. |

### saveAsTIFF(OutputStream outputStream) {#saveAsTIFF-java.io.OutputStream-}
```
public void saveAsTIFF(OutputStream outputStream)
```


Converts each pages of a pdf document to images and saves images to a single TIFF stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | The stream to save the TIFF image. |

### saveAsTIFF(OutputStream outputStream, int compressionType) {#saveAsTIFF-java.io.OutputStream-int-}
```
public void saveAsTIFF(OutputStream outputStream, int compressionType)
```


Converts each pages of a pdf document to images and saves images to a single TIFF file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | The output stream. |
| compressionType | int | Type of the compression. |

### saveAsTIFF(OutputStream outputStream, PageSize pageSize) {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.facades.PageSize-}
```
public void saveAsTIFF(OutputStream outputStream, PageSize pageSize)
```


Converts each pages of a pdf document to images with page size and saves images to a single TIFF stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | The stream to save the TIFF image. |
| pageSize | [PageSize](../../com.aspose.pdf.facades/pagesize) | The page size of the image. |

### saveAsTIFF(OutputStream outputStream, PageSize pageSize, TiffSettings settings) {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.facades.PageSize-com.aspose.pdf.devices.TiffSettings-}
```
public void saveAsTIFF(OutputStream outputStream, PageSize pageSize, TiffSettings settings)
```


Converts each pages of a pdf document to images with page size and saves images to a single TIFF stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | The stream to save the TIFF image. |
| pageSize | [PageSize](../../com.aspose.pdf.facades/pagesize) | The page size of the image. |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Settings. |

### saveAsTIFF(OutputStream outputStream, int imageWidth, int imageHeight) {#saveAsTIFF-java.io.OutputStream-int-int-}
```
public void saveAsTIFF(OutputStream outputStream, int imageWidth, int imageHeight)
```


Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | The stream to save the TIFF image. |
| imageWidth | int | The image width, the unit is pixel. |
| imageHeight | int | The image height, the unit is pixel. |

### saveAsTIFF(OutputStream outputStream, int imageWidth, int imageHeight, int compressionType) {#saveAsTIFF-java.io.OutputStream-int-int-int-}
```
public void saveAsTIFF(OutputStream outputStream, int imageWidth, int imageHeight, int compressionType)
```


Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | The stream to save the TIFF image. |
| imageWidth | int | The image width, the unit is pixel. |
| imageHeight | int | The image height, the unit is pixel. |
| compressionType | int | Type of the compression. |

### saveAsTIFF(OutputStream outputStream, int imageWidth, int imageHeight, TiffSettings settings) {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-}
```
public void saveAsTIFF(OutputStream outputStream, int imageWidth, int imageHeight, TiffSettings settings)
```


Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | The stream to save the TIFF image. |
| imageWidth | int | The image width, the unit is pixel. |
| imageHeight | int | The image height, the unit is pixel. |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Settings. |

### saveAsTIFF(OutputStream outputStream, int imageWidth, int imageHeight, TiffSettings settings, IIndexBitmapConverter converter) {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
```
public void saveAsTIFF(OutputStream outputStream, int imageWidth, int imageHeight, TiffSettings settings, IIndexBitmapConverter converter)
```


Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | The stream to save the TIFF image. |
| imageWidth | int | The image width, the unit is pixel. |
| imageHeight | int | The image height, the unit is pixel. |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Settings. |
| converter | [IIndexBitmapConverter](../../com.aspose.pdf/iindexbitmapconverter) | External converter |

### hasNextImage() {#hasNextImage--}
```
public boolean hasNextImage()
```


Indicates whether the pdf file has more images or not.

**Returns:**
boolean - Can get more images or not, true if can, or false.
### getNextImage(String outputFile) {#getNextImage-java.lang.String-}
```
public void getNextImage(String outputFile)
```


Saves image to file with default image format - jpeg.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | java.lang.String | The file path and name to save the image. |

### getNextImage(String outputFile, PageSize pageSize) {#getNextImage-java.lang.String-com.aspose.pdf.facades.PageSize-}
```
public void getNextImage(String outputFile, PageSize pageSize)
```


Saves image to file with ith given page size and default image format - jpeg.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | java.lang.String | The file path and name to save the image. |
| pageSize | [PageSize](../../com.aspose.pdf.facades/pagesize) | The page size of the image. |

### getNextImage(String outputFile, System.Drawing.Imaging.ImageFormat format) {#getNextImage-java.lang.String-com.aspose.ms.System.Drawing.Imaging.ImageFormat-}
```
public void getNextImage(String outputFile, System.Drawing.Imaging.ImageFormat format)
```


Saves image to file with the givin image format.

--------------------

> ```
> PdfConverter converter = new PdfConverter();
>   converter.bindPdf(@"D:\Test\test.pdf");
>   converter.DoConvert();
>   String prefix = @"D:\Test\";
>   String suffix = ".png";
>   int imageCount = 1;
>   while (converter.HasNextImage())
>   {
>   	converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Png);
>   	imageCount++;
>   }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | java.lang.String | The file path and name to save the image. |
| format | com.aspose.ms.System.Drawing.Imaging.ImageFormat | The format of the image. |

### getNextImage(String outputFile, PageSize pageSize, System.Drawing.Imaging.ImageFormat format) {#getNextImage-java.lang.String-com.aspose.pdf.facades.PageSize-com.aspose.ms.System.Drawing.Imaging.ImageFormat-}
```
public void getNextImage(String outputFile, PageSize pageSize, System.Drawing.Imaging.ImageFormat format)
```


Saves image to file with given page size and image format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | java.lang.String | The file path and name to save the image. |
| pageSize | [PageSize](../../com.aspose.pdf.facades/pagesize) | The page size of the image. |
| format | com.aspose.ms.System.Drawing.Imaging.ImageFormat | The format of the image. |

### getNextImage(OutputStream outputStream) {#getNextImage-java.io.OutputStream-}
```
public void getNextImage(OutputStream outputStream)
```


Saves image to stream with default image format - jpeg.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | The stream to save the image. |

### getNextImage(OutputStream outputStream, PageSize pageSize) {#getNextImage-java.io.OutputStream-com.aspose.pdf.facades.PageSize-}
```
public void getNextImage(OutputStream outputStream, PageSize pageSize)
```


Saves image to stream with given page size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | The stream to save the image. |
| pageSize | [PageSize](../../com.aspose.pdf.facades/pagesize) | The page size of the image. |

### getNextImage(OutputStream outputStream, System.Drawing.Imaging.ImageFormat format) {#getNextImage-java.io.OutputStream-com.aspose.ms.System.Drawing.Imaging.ImageFormat-}
```
public void getNextImage(OutputStream outputStream, System.Drawing.Imaging.ImageFormat format)
```


Saves image to stream with given image format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | The stream to save the image. |
| format | com.aspose.ms.System.Drawing.Imaging.ImageFormat | The format of the image. |

### getNextImage(OutputStream outputStream, PageSize pageSize, System.Drawing.Imaging.ImageFormat format) {#getNextImage-java.io.OutputStream-com.aspose.pdf.facades.PageSize-com.aspose.ms.System.Drawing.Imaging.ImageFormat-}
```
public void getNextImage(OutputStream outputStream, PageSize pageSize, System.Drawing.Imaging.ImageFormat format)
```


Saves image to stream with given page size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | The stream to save the image. |
| pageSize | [PageSize](../../com.aspose.pdf.facades/pagesize) | The page size of the image. |
| format | com.aspose.ms.System.Drawing.Imaging.ImageFormat | The format of the image. |

### getNextImage(String outputFile, System.Drawing.Imaging.ImageFormat format, int imageWidth, int imageHeight, int quality) {#getNextImage-java.lang.String-com.aspose.ms.System.Drawing.Imaging.ImageFormat-int-int-int-}
```
public void getNextImage(String outputFile, System.Drawing.Imaging.ImageFormat format, int imageWidth, int imageHeight, int quality)
```


Saves image to file with the given image format, dimensions and quality.

--------------------

> ```
> PdfConverter converter = new PdfConverter();
>   converter.bindPdf(@"D:\Test\test.pdf");
>   converter.doConvert();
>   String prefix = @"D:\Test\";
>   String suffix = ".jpg";
>   int imageCount = 1;
>   while (converter.HasNextImage())
>   {
>   	converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50);
>   	imageCount++;
>   }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | java.lang.String | The file path and name to save the image. |
| format | com.aspose.ms.System.Drawing.Imaging.ImageFormat | The format of the image. |
| imageWidth | int | The image width, the unit is pixel. |
| imageHeight | int | The image height, the unit is pixel. |
| quality | int | The Jpeg file's quality (0~100), 0 is lowest and 100 is highest |

### getNextImage(OutputStream outputStream, System.Drawing.Imaging.ImageFormat format, int imageWidth, int imageHeight, int quality) {#getNextImage-java.io.OutputStream-com.aspose.ms.System.Drawing.Imaging.ImageFormat-int-int-int-}
```
public void getNextImage(OutputStream outputStream, System.Drawing.Imaging.ImageFormat format, int imageWidth, int imageHeight, int quality)
```


Saves image to stream with the givin image format, dimensions and quality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | The stream to save the image. |
| format | com.aspose.ms.System.Drawing.Imaging.ImageFormat | The format of the image. |
| imageWidth | int | The image width, the unit is pixel. |
| imageHeight | int | The image height, the unit is pixel. |
| quality | int | The Jpeg file's quality (0~100), 0 is lowest and 100 is highest |

### getNextImage(String outputFile, System.Drawing.Imaging.ImageFormat format, double imageWidth, double imageHeight, int quality) {#getNextImage-java.lang.String-com.aspose.ms.System.Drawing.Imaging.ImageFormat-double-double-int-}
```
public void getNextImage(String outputFile, System.Drawing.Imaging.ImageFormat format, double imageWidth, double imageHeight, int quality)
```


Saves image to file with the givin image format, image size, and quality.

--------------------

> ```
> PdfConverter converter = new PdfConverter();
>   converter.bindPdf(@"D:\Test\test.pdf");
>   converter.doConvert();
>   String prefix = @"D:\Test\";
>   String suffix = ".jpg";
>   int imageCount = 1;
>   float pixelX=800f;
>   float pixelY=600f;
>   while (converter.HasNextImage())
>   {
>   	converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50);
>   	imageCount++;
>   }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | java.lang.String | The file path and name to save the image. |
| format | com.aspose.ms.System.Drawing.Imaging.ImageFormat | The format of the image. |
| imageWidth | double | The image width, the unit is pixels. |
| imageHeight | double | The image height, the unit is pixels.. |
| quality | int | The Jpeg file's quality (0~100), 0 is lowest and 100 is highest |

### getNextImage(OutputStream outputStream, System.Drawing.Imaging.ImageFormat format, double imageWidth, double imageHeight, int quality) {#getNextImage-java.io.OutputStream-com.aspose.ms.System.Drawing.Imaging.ImageFormat-double-double-int-}
```
public void getNextImage(OutputStream outputStream, System.Drawing.Imaging.ImageFormat format, double imageWidth, double imageHeight, int quality)
```


Saves image to stream with the givin image format, size and quality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | The stream to save the image. |
| format | com.aspose.ms.System.Drawing.Imaging.ImageFormat | The format of the image. |
| imageWidth | double | The image width, the unit is pixel. |
| imageHeight | double | The image height, the unit is pixel. |
| quality | int | The Jpeg file's quality (0~100), 0 is lowest and 100 is highest |

### bindPdf(String inputFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String inputFile)
```


Binds a Pdf file for converting.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | The pdf file. |

### bindPdf(InputStream inputStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream inputStream)
```


Binds a Pdf Stream for convert.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | The pdf Stream. |

### close() {#close--}
```
public void close()
```


Close the instance of PdfConverter and release the resources.

### saveAsTIFFClassF(String outputFile) {#saveAsTIFFClassF-java.lang.String-}
```
public void saveAsTIFFClassF(String outputFile)
```


Converts each pages of a pdf document to images and save images to a single TIFF ClassF file.

--------------------

> ```
> [C#]
>   PdfConverter converter = new PdfConverter();
>   converter.bindPdf(@"D:\Test\test.pdf");
>   converter.doConvert();
>   converter.saveAsTIFFClassF(@"D:\Test\test.tiff");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | java.lang.String | The stream to save the TIFF image. |

### saveAsTIFFClassF(OutputStream outputStream) {#saveAsTIFFClassF-java.io.OutputStream-}
```
public void saveAsTIFFClassF(OutputStream outputStream)
```


Converts each pages of a pdf document to images and save images to a single TIFF ClassF stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | The stream to save the TIFF image. |

### saveAsTIFF(String outputFile, TiffSettings settings) {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-}
```
public void saveAsTIFF(String outputFile, TiffSettings settings)
```


Converts each pages of a pdf document to images with and saves images to a single TIFF file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | java.lang.String | The file name to save the TIFF image |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Settings. |

### saveAsTIFF(String outputFile, TiffSettings settings, IIndexBitmapConverter converter) {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
```
public void saveAsTIFF(String outputFile, TiffSettings settings, IIndexBitmapConverter converter)
```


Converts each pages of a pdf document to images with and saves images to a single TIFF file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | java.lang.String | The file name to save the TIFF image |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Settings. |
| converter | [IIndexBitmapConverter](../../com.aspose.pdf/iindexbitmapconverter) | External converter |

### saveAsTIFF(OutputStream outputStream, TiffSettings settings) {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-}
```
public void saveAsTIFF(OutputStream outputStream, TiffSettings settings)
```


Converts each pages of a pdf document to images and saves images to a single TIFF stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | The stream to save the TIFF image. |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Settings. |

### saveAsTIFF(OutputStream outputStream, TiffSettings settings, IIndexBitmapConverter converter) {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
```
public void saveAsTIFF(OutputStream outputStream, TiffSettings settings, IIndexBitmapConverter converter)
```


Converts each pages of a pdf document to images and saves images to a single TIFF stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | The stream to save the TIFF image. |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Settings. |
| converter | [IIndexBitmapConverter](../../com.aspose.pdf/iindexbitmapconverter) | External converter |

### getNextImage(String outputFile, System.Drawing.Imaging.ImageFormat format, int imageWidth, int imageHeight) {#getNextImage-java.lang.String-com.aspose.ms.System.Drawing.Imaging.ImageFormat-int-int-}
```
public void getNextImage(String outputFile, System.Drawing.Imaging.ImageFormat format, int imageWidth, int imageHeight)
```


Saves image to file with the given image format and dimensions.

--------------------

> ```
> PdfConverter converter = new PdfConverter();
>   converter.bindPdf(@"D:\Test\test.pdf");
>   converter.DoConvert();
>   String prefix = @"D:\Test\";
>   String suffix = ".jpg";
>   int imageCount = 1;
>   while (converter.HasNextImage())
>   {
>   	converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000);
>   	imageCount++;
>   }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | java.lang.String | The file path and name to save the image. |
| format | com.aspose.ms.System.Drawing.Imaging.ImageFormat | The format of the image. |
| imageWidth | int | The image width, the unit is pixel. |
| imageHeight | int | The image height, the unit is pixel. |

### getNextImage(OutputStream outputStream, System.Drawing.Imaging.ImageFormat format, int imageWidth, int imageHeight) {#getNextImage-java.io.OutputStream-com.aspose.ms.System.Drawing.Imaging.ImageFormat-int-int-}
```
public void getNextImage(OutputStream outputStream, System.Drawing.Imaging.ImageFormat format, int imageWidth, int imageHeight)
```


Saves image to stream with the givin image format, size and quality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | The stream to save the image. |
| format | com.aspose.ms.System.Drawing.Imaging.ImageFormat | The format of the image. |
| imageWidth | int | The image width, the unit is pixel. |
| imageHeight | int | The image height, the unit is pixel. |

### getNextImage(OutputStream outputStream, System.Drawing.Imaging.ImageFormat format, int quality) {#getNextImage-java.io.OutputStream-com.aspose.ms.System.Drawing.Imaging.ImageFormat-int-}
```
public void getNextImage(OutputStream outputStream, System.Drawing.Imaging.ImageFormat format, int quality)
```


Saves image to stream with given image format and quality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | The stream to save the image. |
| format | com.aspose.ms.System.Drawing.Imaging.ImageFormat | The format of the image. |
| quality | int | The Jpeg file's quality (0~100), 0 is lowest and 100 is highest |

### getNextImage(OutputStream outputStream, PageSize pageSize, System.Drawing.Imaging.ImageFormat format, int quality) {#getNextImage-java.io.OutputStream-com.aspose.pdf.facades.PageSize-com.aspose.ms.System.Drawing.Imaging.ImageFormat-int-}
```
public void getNextImage(OutputStream outputStream, PageSize pageSize, System.Drawing.Imaging.ImageFormat format, int quality)
```


Saves image to stream with given page size, image format and quality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | The stream to save the image. |
| pageSize | [PageSize](../../com.aspose.pdf.facades/pagesize) | The page size of the image. |
| format | com.aspose.ms.System.Drawing.Imaging.ImageFormat | The format of the image. |
| quality | int | The Jpeg file's quality (0~100), 0 is lowest and 100 is highest |

### getNextImage(String outputFile, System.Drawing.Imaging.ImageFormat format, int quality) {#getNextImage-java.lang.String-com.aspose.ms.System.Drawing.Imaging.ImageFormat-int-}
```
public void getNextImage(String outputFile, System.Drawing.Imaging.ImageFormat format, int quality)
```


Saves image to file with given image format and quality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | java.lang.String | The file path and name to save the image. |
| format | com.aspose.ms.System.Drawing.Imaging.ImageFormat | The format of the image. |
| quality | int | The Jpeg file's quality (0~100), 0 is lowest and 100 is highest |

### getNextImage(String outputFile, PageSize pageSize, System.Drawing.Imaging.ImageFormat format, int quality) {#getNextImage-java.lang.String-com.aspose.pdf.facades.PageSize-com.aspose.ms.System.Drawing.Imaging.ImageFormat-int-}
```
public void getNextImage(String outputFile, PageSize pageSize, System.Drawing.Imaging.ImageFormat format, int quality)
```


Saves image to file with given page size, image format and quality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | java.lang.String | The file path and name to save the image. |
| pageSize | [PageSize](../../com.aspose.pdf.facades/pagesize) | The page size of the image. |
| format | com.aspose.ms.System.Drawing.Imaging.ImageFormat | The format of the image. |
| quality | int | The Jpeg file's quality (0~100), 0 is lowest and 100 is highest |

### dispose() {#dispose--}
```
public void dispose()
```


Disposes the facade.

