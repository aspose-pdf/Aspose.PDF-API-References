---
title: PdfFileMend
second_title: Aspose.PDF for Java API Reference
description: Represents a class for adding texts and images on the pages of existing PDF document.
type: docs
weight: 38
url: /java/com.aspose.pdf.facades/pdffilemend/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade)
```
public final class PdfFileMend extends SaveableFacade
```

Represents a class for adding texts and images on the pages of existing PDF document.
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfFileMend()](#PdfFileMend--) | Constructor. |
| [PdfFileMend(String inputFileName, String outputFileName)](#PdfFileMend-java.lang.String-java.lang.String-) | Constructor. |
| [PdfFileMend(FileInputStream inputStream, FileOutputStream outputStream)](#PdfFileMend-java.io.FileInputStream-java.io.FileOutputStream-) | Constructor. |
| [PdfFileMend(System.IO.Stream inputStream, FileOutputStream outputStream)](#PdfFileMend-com.aspose.ms.System.IO.Stream-java.io.FileOutputStream-) |  |
| [PdfFileMend(System.IO.Stream inputStream, System.IO.Stream outputStream)](#PdfFileMend-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | Constructor. |
| [PdfFileMend(IDocument document)](#PdfFileMend-com.aspose.pdf.IDocument-) | Initializes new  PdfFileMend  object on base of the  document . |
| [PdfFileMend(IDocument document, String outputFileName)](#PdfFileMend-com.aspose.pdf.IDocument-java.lang.String-) | Initializes new  PdfFileMend  object on base of the  document . |
| [PdfFileMend(IDocument document, System.IO.Stream outputStream)](#PdfFileMend-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-) | Initializes new  PdfFileMend  object on base of the  document . |
## Methods

| Method | Description |
| --- | --- |
| [getInputStream()](#getInputStream--) |  |
| [setInputStream(InputStream value)](#setInputStream-java.io.InputStream-) |  |
| [getOutputStream()](#getOutputStream--) |  |
| [setOutputStream(OutputStream value)](#setOutputStream-java.io.OutputStream-) |  |
| [getInputFile()](#getInputFile--) | Sets the input file. |
| [setInputFile(String value)](#setInputFile-java.lang.String-) |  |
| [getOutputFile()](#getOutputFile--) | Sets the output file. |
| [setOutputFile(String value)](#setOutputFile-java.lang.String-) | Sets the output file. |
| [setOutputStream(System.IO.Stream value)](#setOutputStream-com.aspose.ms.System.IO.Stream-) | Sets the output stream. |
| [isWordWrap(boolean value)](#isWordWrap-boolean-) | Sets a bool value that indicates word wrap in AddText methods. |
| [getWrapMode()](#getWrapMode--) | Sets or gets word wrapping algorithm. |
| [setWrapMode(int value)](#setWrapMode-int-) |  |
| [getTextPositioningMode()](#getTextPositioningMode--) | Sets or gets text positioning strategy. |
| [setTextPositioningMode(int value)](#setTextPositioningMode-int-) |  |
| [addImage(InputStream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)](#addImage-java.io.InputStream-int-float-float-float-float-) | Adds image to the specified page of PDF document at specified coordinates. |
| [addImage(InputStream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, CompositingParameters compositingParameters)](#addImage-java.io.InputStream-int-float-float-float-float-com.aspose.pdf.CompositingParameters-) | Adds image to the specified page of PDF document at specified coordinates. |
| [addImage(InputStream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)](#addImage-java.io.InputStream-int---float-float-float-float-) | Adds image to the specified pages of PDF document at specified coordinates. |
| [addImage(InputStream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, CompositingParameters compositingParameters)](#addImage-java.io.InputStream-int---float-float-float-float-com.aspose.pdf.CompositingParameters-) | Adds image to the specified pages of PDF document at specified coordinates. |
| [addImage(String imageName, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)](#addImage-java.lang.String-int-float-float-float-float-) | Adds image to the specified page of PDF document at specified coordinates. |
| [addImage(String imageName, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, CompositingParameters compositingParameters)](#addImage-java.lang.String-int-float-float-float-float-com.aspose.pdf.CompositingParameters-) | Adds image to the specified page of PDF document at specified coordinates. |
| [addImage(String imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)](#addImage-java.lang.String-int---float-float-float-float-) | Adds image to the specified pages of PDF document at specified coordinates. |
| [addImage(String imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, CompositingParameters compositingParameters)](#addImage-java.lang.String-int---float-float-float-float-com.aspose.pdf.CompositingParameters-) | Adds image to the specified pages of PDF document at specified coordinates. |
| [addText(FormattedText text, int pageNum, float lowerLeftX, float lowerLeftY)](#addText-com.aspose.pdf.facades.FormattedText-int-float-float-) | Not implemented. |
| [addText(FormattedText text, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)](#addText-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | Not implemented. |
| [addText(FormattedText text, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)](#addText-com.aspose.pdf.facades.FormattedText-int---float-float-float-float-) | Not implemented. |
| [close()](#close--) | Closes PdfFileMend object. |
| [dispose()](#dispose--) |  |
| [save(String destFile)](#save-java.lang.String-) |  |
| [save(OutputStream destStream)](#save-java.io.OutputStream-) |  |
| [getDocument()](#getDocument--) | Gets the document  PdfFileMend  is working on. |
### PdfFileMend() {#PdfFileMend--}
```
public PdfFileMend()
```


Constructor.

### PdfFileMend(String inputFileName, String outputFileName) {#PdfFileMend-java.lang.String-java.lang.String-}
```
public PdfFileMend(String inputFileName, String outputFileName)
```


Constructor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFileName | java.lang.String | Input PDF file name. |
| outputFileName | java.lang.String | Output PDF file name. |

### PdfFileMend(FileInputStream inputStream, FileOutputStream outputStream) {#PdfFileMend-java.io.FileInputStream-java.io.FileOutputStream-}
```
public PdfFileMend(FileInputStream inputStream, FileOutputStream outputStream)
```


Constructor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.FileInputStream | Input PDF stream. |
| outputStream | java.io.FileOutputStream | Output PDF stream. |

### PdfFileMend(System.IO.Stream inputStream, FileOutputStream outputStream) {#PdfFileMend-com.aspose.ms.System.IO.Stream-java.io.FileOutputStream-}
```
public PdfFileMend(System.IO.Stream inputStream, FileOutputStream outputStream)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | com.aspose.ms.System.IO.Stream |  |
| outputStream | java.io.FileOutputStream |  |

### PdfFileMend(System.IO.Stream inputStream, System.IO.Stream outputStream) {#PdfFileMend-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public PdfFileMend(System.IO.Stream inputStream, System.IO.Stream outputStream)
```


Constructor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | com.aspose.ms.System.IO.Stream | Input PDF stream. |
| outputStream | com.aspose.ms.System.IO.Stream | Output PDF stream. |

### PdfFileMend(IDocument document) {#PdfFileMend-com.aspose.pdf.IDocument-}
```
public PdfFileMend(IDocument document)
```


Initializes new  PdfFileMend  object on base of the  document .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Pdf document. |

### PdfFileMend(IDocument document, String outputFileName) {#PdfFileMend-com.aspose.pdf.IDocument-java.lang.String-}
```
public PdfFileMend(IDocument document, String outputFileName)
```


Initializes new  PdfFileMend  object on base of the  document .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Pdf document. |
| outputFileName | java.lang.String | Output PDF file name. |

### PdfFileMend(IDocument document, System.IO.Stream outputStream) {#PdfFileMend-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-}
```
public PdfFileMend(IDocument document, System.IO.Stream outputStream)
```


Initializes new  PdfFileMend  object on base of the  document .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Pdf document. |
| outputStream | com.aspose.ms.System.IO.Stream |  |

### getInputStream() {#getInputStream--}
```
public InputStream getInputStream()
```




**Returns:**
java.io.InputStream
### setInputStream(InputStream value) {#setInputStream-java.io.InputStream-}
```
public void setInputStream(InputStream value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.InputStream |  |

### getOutputStream() {#getOutputStream--}
```
public OutputStream getOutputStream()
```




**Returns:**
java.io.OutputStream
### setOutputStream(OutputStream value) {#setOutputStream-java.io.OutputStream-}
```
public void setOutputStream(OutputStream value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.OutputStream |  |

### getInputFile() {#getInputFile--}
```
public String getInputFile()
```


Sets the input file.

**Returns:**
java.lang.String
### setInputFile(String value) {#setInputFile-java.lang.String-}
```
public void setInputFile(String value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getOutputFile() {#getOutputFile--}
```
public String getOutputFile()
```


Sets the output file.

**Returns:**
java.lang.String
### setOutputFile(String value) {#setOutputFile-java.lang.String-}
```
public void setOutputFile(String value)
```


Sets the output file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setOutputStream(System.IO.Stream value) {#setOutputStream-com.aspose.ms.System.IO.Stream-}
```
public void setOutputStream(System.IO.Stream value)
```


Sets the output stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.IO.Stream |  |

### isWordWrap(boolean value) {#isWordWrap-boolean-}
```
public void isWordWrap(boolean value)
```


Sets a bool value that indicates word wrap in AddText methods. If the value is true, the text in FormattedText will word wrap. By defalt, the value is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Sets or gets word wrapping algorithm. See WordWrapMode and IsWordWrap.

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTextPositioningMode() {#getTextPositioningMode--}
```
public int getTextPositioningMode()
```


Sets or gets text positioning strategy.  PositioningMode  Default mode is Legacy.

**Returns:**
int
### setTextPositioningMode(int value) {#setTextPositioningMode-int-}
```
public void setTextPositioningMode(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### addImage(InputStream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY) {#addImage-java.io.InputStream-int-float-float-float-float-}
```
public boolean addImage(InputStream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)
```


Adds image to the specified page of PDF document at specified coordinates.

--------------------

> ```
> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
>  Stream stream = File.OpenRead("picture.jpg"))
>  mendor.addImage(stream, 1, 10, 10, 100, 100);
>  mendor.close();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | java.io.InputStream | Input image stream. |
| pageNum | int | The number of page that will receive the image. |
| lowerLeftX | float | The lower left x of image rectangle. |
| lowerLeftY | float | The lower left y of image rectangle. |
| upperRightX | float | The upper right x of image rectangle. |
| upperRightY | float | The upper right y of image rectangle. |

**Returns:**
boolean - True if success false otherwise.
### addImage(InputStream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, CompositingParameters compositingParameters) {#addImage-java.io.InputStream-int-float-float-float-float-com.aspose.pdf.CompositingParameters-}
```
public boolean addImage(InputStream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```


Adds image to the specified page of PDF document at specified coordinates.

--------------------

> ```
> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
>  Stream stream = File.OpenRead("picture.jpg"))
>  mendor.addImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
>  mendor.close();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | java.io.InputStream | Input image stream. |
| pageNum | int | The number of page that will receive the image. |
| lowerLeftX | float | The lower left x of image rectangle. |
| lowerLeftY | float | The lower left y of image rectangle. |
| upperRightX | float | The upper right x of image rectangle. |
| upperRightY | float | The upper right y of image rectangle. |
| compositingParameters | [CompositingParameters](../../com.aspose.pdf/compositingparameters) | The graphics compositing parameters for the image. |

**Returns:**
boolean - True if success false otherwise.
### addImage(InputStream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY) {#addImage-java.io.InputStream-int---float-float-float-float-}
```
public boolean addImage(InputStream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)
```


Adds image to the specified pages of PDF document at specified coordinates.

--------------------

> ```
> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
>  using (Stream stream = File.OpenRead("picture.jpg"))
>  {
>      mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100);
>  }
>  mendor.close();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | java.io.InputStream | Input image stream. |
| pageNums | int[] | The numbers of pages that will receive the image. |
| lowerLeftX | float | The lower left x of image rectangle. |
| lowerLeftY | float | The lower left y of image rectangle. |
| upperRightX | float | The upper right x of image rectangle. |
| upperRightY | float | The upper right y of image rectangle. |

**Returns:**
boolean - True if success false otherwise.
### addImage(InputStream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, CompositingParameters compositingParameters) {#addImage-java.io.InputStream-int---float-float-float-float-com.aspose.pdf.CompositingParameters-}
```
public boolean addImage(InputStream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```


Adds image to the specified pages of PDF document at specified coordinates.

--------------------

> ```
> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
>  using (Stream stream = File.OpenRead("picture.jpg"))
>  {
>      mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
>  }
>  mendor.close();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | java.io.InputStream | Input image stream. |
| pageNums | int[] | The numbers of pages that will receive the image. |
| lowerLeftX | float | The lower left x of image rectangle. |
| lowerLeftY | float | The lower left y of image rectangle. |
| upperRightX | float | The upper right x of image rectangle. |
| upperRightY | float | The upper right y of image rectangle. |
| compositingParameters | [CompositingParameters](../../com.aspose.pdf/compositingparameters) | The graphics compositing parameters for the images. |

**Returns:**
boolean - True if success false otherwise.
### addImage(String imageName, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY) {#addImage-java.lang.String-int-float-float-float-float-}
```
public boolean addImage(String imageName, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)
```


Adds image to the specified page of PDF document at specified coordinates.

--------------------

> ```
> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
>  mendor.addImage("picture.jpg", 1, 10, 10, 100, 100);
>  mendor.close();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageName | java.lang.String | The path of input image file. |
| pageNum | int | The number of page that will receive the image. |
| lowerLeftX | float | The lower left x of image rectangle. |
| lowerLeftY | float | The lower left y of image rectangle. |
| upperRightX | float | The upper right x of image rectangle. |
| upperRightY | float | The upper right y of image rectangle. |

**Returns:**
boolean - True if success false otherwise.
### addImage(String imageName, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, CompositingParameters compositingParameters) {#addImage-java.lang.String-int-float-float-float-float-com.aspose.pdf.CompositingParameters-}
```
public boolean addImage(String imageName, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```


Adds image to the specified page of PDF document at specified coordinates.

--------------------

> ```
> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
>  mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
>  mendor.close();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageName | java.lang.String | The path of input image file. |
| pageNum | int | The number of page that will receive the image. |
| lowerLeftX | float | The lower left x of image rectangle. |
| lowerLeftY | float | The lower left y of image rectangle. |
| upperRightX | float | The upper right x of image rectangle. |
| upperRightY | float | The upper right y of image rectangle. |
| compositingParameters | [CompositingParameters](../../com.aspose.pdf/compositingparameters) | The graphics compositing parameters for the images. |

**Returns:**
boolean - True if success false otherwise.
### addImage(String imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY) {#addImage-java.lang.String-int---float-float-float-float-}
```
public boolean addImage(String imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)
```


Adds image to the specified pages of PDF document at specified coordinates.

--------------------

> ```
> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
>  mendor.addImage("picture.jpg", 1, 10, 10, 100, 100);
>  mendor.close();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageName | java.lang.String | The path of input image file. |
| pageNums | int[] | The numbers of pages that will receive the image. |
| lowerLeftX | float | The lower left x of image rectangle. |
| lowerLeftY | float | The lower left y of image rectangle. |
| upperRightX | float | The upper right x of image rectangle. |
| upperRightY | float | The upper right y of image rectangle. |

**Returns:**
boolean - True if success false otherwise.
### addImage(String imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, CompositingParameters compositingParameters) {#addImage-java.lang.String-int---float-float-float-float-com.aspose.pdf.CompositingParameters-}
```
public boolean addImage(String imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```


Adds image to the specified pages of PDF document at specified coordinates.

--------------------

> ```
> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
>  mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
>  mendor.close();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageName | java.lang.String | The path of input image file. |
| pageNums | int[] | The numbers of pages that will receive the image. |
| lowerLeftX | float | The lower left x of image rectangle. |
| lowerLeftY | float | The lower left y of image rectangle. |
| upperRightX | float | The upper right x of image rectangle. |
| upperRightY | float | The upper right y of image rectangle. |
| compositingParameters | [CompositingParameters](../../com.aspose.pdf/compositingparameters) | The graphics compositing parameters for the images. |

**Returns:**
boolean - True if success false otherwise.
### addText(FormattedText text, int pageNum, float lowerLeftX, float lowerLeftY) {#addText-com.aspose.pdf.facades.FormattedText-int-float-float-}
```
public boolean addText(FormattedText text, int pageNum, float lowerLeftX, float lowerLeftY)
```


Not implemented.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | [FormattedText](../../com.aspose.pdf.facades/formattedtext) |  |
| pageNum | int |  |
| lowerLeftX | float |  |
| lowerLeftY | float |  |

**Returns:**
boolean - 
### addText(FormattedText text, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY) {#addText-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
```
public boolean addText(FormattedText text, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)
```


Not implemented.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | [FormattedText](../../com.aspose.pdf.facades/formattedtext) |  |
| pageNum | int |  |
| lowerLeftX | float |  |
| lowerLeftY | float |  |
| upperRightX | float |  |
| upperRightY | float |  |

**Returns:**
boolean - 
### addText(FormattedText text, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY) {#addText-com.aspose.pdf.facades.FormattedText-int---float-float-float-float-}
```
public boolean addText(FormattedText text, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)
```


Not implemented.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | [FormattedText](../../com.aspose.pdf.facades/formattedtext) |  |
| pageNums | int[] |  |
| lowerLeftX | float |  |
| lowerLeftY | float |  |
| upperRightX | float |  |
| upperRightY | float |  |

**Returns:**
boolean - 
### close() {#close--}
```
public void close()
```


Closes PdfFileMend object.

### dispose() {#dispose--}
```
public void dispose()
```


Disposes the facade.

### save(String destFile) {#save-java.lang.String-}
```
public void save(String destFile)
```


Saves the result PDF document to file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destFile | java.lang.String |  |

### save(OutputStream destStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destStream)
```


Saves the result PDF document to stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destStream | java.io.OutputStream |  |

### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


Gets the document  PdfFileMend  is working on.

**Returns:**
[IDocument](../../com.aspose.pdf/idocument)
