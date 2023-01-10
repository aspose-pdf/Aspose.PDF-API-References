---
title: PdfFileMend
second_title: Aspose.PDF for Java API Reference
description: Represents a class for adding texts and images on the pages of existing PDF document.
type: docs
weight: 42
url: /java/com.aspose.pdf.facades/pdffilemend/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade)
```
public final class PdfFileMend extends SaveableFacade
```

Represents a class for adding texts and images on the pages of existing PDF document.
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfFileMend()](#PdfFileMend--) | Constructor. |
| [PdfFileMend(String inputFileName, String outputFileName)](#PdfFileMend-java.lang.String-java.lang.String-) | Constructor. |
| [PdfFileMend(InputStream inputStream, OutputStream outputStream)](#PdfFileMend-java.io.InputStream-java.io.OutputStream-) | Constructor. |
| [PdfFileMend(System.IO.Stream inputStream, System.IO.Stream outputStream)](#PdfFileMend-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | Constructor. |
| [PdfFileMend(IDocument document)](#PdfFileMend-com.aspose.pdf.IDocument-) | Initializes new  PdfFileMend  object on base of the  document . |
| [PdfFileMend(IDocument document, String outputFileName)](#PdfFileMend-com.aspose.pdf.IDocument-java.lang.String-) | Initializes new  PdfFileMend  object on base of the  document . |
| [PdfFileMend(IDocument document, System.IO.Stream outputStream)](#PdfFileMend-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-) | Initializes new  PdfFileMend  object on base of the  document . |
## Methods

| Method | Description |
| --- | --- |
| [getInputStream()](#getInputStream--) | Gets the input stream. |
| [setInputStream(InputStream value)](#setInputStream-java.io.InputStream-) | Sets the input stream. |
| [getOutputStream()](#getOutputStream--) | Gets the output stream. |
| [setOutputStream(OutputStream value)](#setOutputStream-java.io.OutputStream-) | This method is Deprecated. |
| [getInputFile()](#getInputFile--) | Gets the input file. |
| [setInputFile(String value)](#setInputFile-java.lang.String-) |  |
| [getOutputFile()](#getOutputFile--) | Gets the output file. |
| [setOutputFile(String value)](#setOutputFile-java.lang.String-) | Sets the output file. |
| [setWordWrap(boolean value)](#setWordWrap-boolean-) | Sets a bool value that indicates word wrap in AddText methods. |
| [getWrapMode()](#getWrapMode--) | Gets word wrapping algorithm. |
| [setWrapMode(int value)](#setWrapMode-int-) | Sets word wrapping algorithm. |
| [getTextPositioningMode()](#getTextPositioningMode--) | Gets text positioning strategy. |
| [setTextPositioningMode(int value)](#setTextPositioningMode-int-) | Sets text positioning strategy. |
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
| [addText(FormattedText text, Integer[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)](#addText-com.aspose.pdf.facades.FormattedText-java.lang.Integer---float-float-float-float-) | Not implemented. |
| [close()](#close--) | Closes PdfFileMend object. |
| [dispose()](#dispose--) | Closes PdfFileMend object. |
| [save(String destFile)](#save-java.lang.String-) | Saves the PDF document to the specified file. |
| [save(OutputStream destStream)](#save-java.io.OutputStream-) | Saves the PDF document to the specified file. |
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

Obsolete("Use constructor without destination.")

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFileName | java.lang.String | Input PDF file name. |
| outputFileName | java.lang.String | Output PDF file name. |

### PdfFileMend(InputStream inputStream, OutputStream outputStream) {#PdfFileMend-java.io.InputStream-java.io.OutputStream-}
```
public PdfFileMend(InputStream inputStream, OutputStream outputStream)
```


Constructor. Obsolete("Use constructor without destination.")

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input PDF stream. |
| outputStream | java.io.OutputStream | Output PDF stream. |

### PdfFileMend(System.IO.Stream inputStream, System.IO.Stream outputStream) {#PdfFileMend-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public PdfFileMend(System.IO.Stream inputStream, System.IO.Stream outputStream)
```


Constructor.

Obsolete("Use constructor without destination.")

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

Obsolete("Use constructor without destination.")

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

Obsolete("Use constructor without destination.")

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Pdf document. |
| outputStream | com.aspose.ms.System.IO.Stream | Output PDF stream. |

### getInputStream() {#getInputStream--}
```
public InputStream getInputStream()
```


Gets the input stream.

**Returns:**
java.io.InputStream - input stream.
### setInputStream(InputStream value) {#setInputStream-java.io.InputStream-}
```
public void setInputStream(InputStream value)
```


Sets the input stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.InputStream | input stream. |

### getOutputStream() {#getOutputStream--}
```
public OutputStream getOutputStream()
```


Gets the output stream.

**Returns:**
java.io.OutputStream - output stream.
### setOutputStream(OutputStream value) {#setOutputStream-java.io.OutputStream-}
```
public void setOutputStream(OutputStream value)
```


This method is Deprecated. Use Save(outputStream) method for getting facade results.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.OutputStream | output stream. |

### getInputFile() {#getInputFile--}
```
public String getInputFile()
```


Gets the input file.

**Returns:**
java.lang.String - String value
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


Gets the output file.

**Returns:**
java.lang.String - String value
### setOutputFile(String value) {#setOutputFile-java.lang.String-}
```
public void setOutputFile(String value)
```


Sets the output file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setWordWrap(boolean value) {#setWordWrap-boolean-}
```
public void setWordWrap(boolean value)
```


Sets a bool value that indicates word wrap in AddText methods. If the value is true, the text in FormattedText will word wrap. By defalt, the value is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Gets word wrapping algorithm.

**Returns:**
int - WordWrapMode value
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Sets word wrapping algorithm.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | WordWrapMode element |

### getTextPositioningMode() {#getTextPositioningMode--}
```
public int getTextPositioningMode()
```


Gets text positioning strategy.  PositioningMode  Default mode is Legacy.

**Returns:**
int - PositioningMode element
### setTextPositioningMode(int value) {#setTextPositioningMode-int-}
```
public void setTextPositioningMode(int value)
```


Sets text positioning strategy.  PositioningMode  Default mode is Legacy.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | PositioningMode element |

### addImage(InputStream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY) {#addImage-java.io.InputStream-int-float-float-float-float-}
```
public boolean addImage(InputStream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)
```


Adds image to the specified page of PDF document at specified coordinates.

--------------------

```
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
 InputStream stream = new FileInputStream("picture.jpg"))
 mendor.addImage(stream, 1, 10, 10, 100, 100);
 mendor.close();
```

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

```
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
 InputStream stream = new FileInputStream("picture.jpg"))
 mendor.addImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
 mendor.close();
```

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

```
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
 InputStream stream = new FileInputStream("picture.jpg")
     mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100);
 mendor.close();
```

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

```
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
 InputStream stream = new FileInputStream("picture.jpg")
     mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
 mendor.close();
```

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

```
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
 mendor.addImage("picture.jpg", 1, 10, 10, 100, 100);
 mendor.close();
```

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

```
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
 mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
 mendor.close();
```

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

```
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
 mendor.addImage("picture.jpg", 1, 10, 10, 100, 100);
 mendor.close();
```

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

```
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
 mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
 mendor.close();
```

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
| text | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | FormattedText object. |
| pageNum | int | Page number. |
| lowerLeftX | float | Lower left X coordinate. |
| lowerLeftY | float | Lower left Y coordinate. |

**Returns:**
boolean - True in case text was successfully added.
### addText(FormattedText text, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY) {#addText-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
```
public boolean addText(FormattedText text, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)
```


Not implemented.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | FormattedText object. |
| pageNum | int | Page number. |
| lowerLeftX | float | Lower left X coordinate. |
| lowerLeftY | float | Lower left Y coordinate. |
| upperRightX | float | Upper right X coordinate. |
| upperRightY | float | Upper right Y coordinate. |

**Returns:**
boolean - True in case text was successfully added.
### addText(FormattedText text, Integer[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY) {#addText-com.aspose.pdf.facades.FormattedText-java.lang.Integer---float-float-float-float-}
```
public boolean addText(FormattedText text, Integer[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)
```


Not implemented.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | FormattedText object. |
| pageNums | java.lang.Integer[] | Page numbers array. |
| lowerLeftX | float | Lower left X coordinate. |
| lowerLeftY | float | Lower left Y coordinate. |
| upperRightX | float | Upper right X coordinate. |
| upperRightY | float | Upper right Y coordinate. |

**Returns:**
boolean - True in case text was successfully added.
### close() {#close--}
```
public void close()
```


Closes PdfFileMend object.

### dispose() {#dispose--}
```
public void dispose()
```


Closes PdfFileMend object. This method is obsolete, use close() instead.

### save(String destFile) {#save-java.lang.String-}
```
public void save(String destFile)
```


Saves the PDF document to the specified file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destFile | java.lang.String | The destination file. |

### save(OutputStream destStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destStream)
```


Saves the PDF document to the specified file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destStream | java.io.OutputStream | The destination stream. |

### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


Gets the document  PdfFileMend  is working on.

**Returns:**
[IDocument](../../com.aspose.pdf/idocument) - IDocument object
