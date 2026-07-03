---
title: PdfFileMend
linktitle: PdfFileMend
second_title: Aspose.PDF for Java API Reference
description: Represents a class for adding texts and images on the pages of existing PDF document.
type: docs
weight: 500
url: /java/com.aspose.pdf.facades/pdffilemend/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileMend, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileMend, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileMend

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileMend extends SaveableFacade
```

Represents a class for adding texts and images on the pages of existing PDF document.

## Constructors

| Constructor | Description |
| --- | --- |
| [PdfFileMend](#PdfFileMend--) | Constructor. |
| [PdfFileMend](#PdfFileMend-com.aspose.pdf.IDocument-) | Constructor. |
| [PdfFileMend](#PdfFileMend-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-) | Constructor. |
| [PdfFileMend](#PdfFileMend-com.aspose.pdf.IDocument-java.lang.String-) | Constructor. |
| [PdfFileMend](#PdfFileMend-java.io.InputStream-java.io.OutputStream-) | Constructor. |
| [PdfFileMend](#PdfFileMend-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | Constructor. |
| [PdfFileMend](#PdfFileMend-java.lang.String-java.lang.String-) | Constructor. |

## Methods

| Method | Description |
| --- | --- |
| [addImage](#addImage-java.io.InputStream-int:A-float-float-float-float-) | <p> Adds image to the specified pages of PDF document at specified coordinates. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.io.InputStream-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> Adds image to the specified pages of PDF document at specified coordinates. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre> |
| [addImage](#addImage-java.io.InputStream-int-float-float-float-float-) | <p> Adds image to the specified page of PDF document at specified coordinates. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.io.InputStream-int-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> Adds image to the specified page of PDF document at specified coordinates. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int:A-float-float-float-float-) | <p> Adds image to the specified pages of PDF document at specified coordinates. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> Adds image to the specified pages of PDF document at specified coordinates. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int-float-float-float-float-) | <p> Adds image to the specified page of PDF document at specified coordinates. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> Adds image to the specified page of PDF document at specified coordinates. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre> |
| [addText](#addText-com.aspose.pdf.facades.FormattedText-java.lang.Integer:A-float-float-float-float-) | Not implemented. |
| [addText](#addText-com.aspose.pdf.facades.FormattedText-int-float-float-) | Not implemented. |
| [addText](#addText-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | Not implemented. |
| [close](#close--) | Closes PdfFileMend object. |
| [dispose](#dispose--) | Closes PdfFileMend object. This method is obsolete, use close() instead. |
| [getDocument](#getDocument--) | Gets the document {@code PdfFileMend} is working on. |
| [getInputFile](#getInputFile--) | Gets the input file. |
| [getInputStream](#getInputStream--) | Gets the input stream. |
| [getOutputFile](#getOutputFile--) | Gets the output file. |
| [getOutputStream](#getOutputStream--) | Gets the output stream. |
| [getTextPositioningMode](#getTextPositioningMode--) | Gets text positioning strategy. {@code PositioningMode} Default mode is Legacy. |
| [getWrapMode](#getWrapMode--) | Gets word wrapping algorithm. |
| [save](#save-java.io.OutputStream-) | Saves the PDF document to the specified file. |
| [save](#save-java.lang.String-) | Saves the PDF document to the specified file. |
| [setInputFile](#setInputFile-java.lang.String-) | Deprecated. |
| [setInputStream](#setInputStream-java.io.InputStream-) | Sets the input stream. |
| [setOutputFile](#setOutputFile-java.lang.String-) | Sets the output file. |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | This method is Deprecated. Use Save(outputStream) method for getting facade results. |
| [setTextPositioningMode](#setTextPositioningMode-int-) | Sets text positioning strategy. {@code PositioningMode} Default mode is Legacy. |
| [setWordWrap](#setWordWrap-boolean-) | Sets a bool value that indicates word wrap in AddText methods. If the value is true, the text in FormattedText will word wrap. By defalt, the value is false. |
| [setWrapMode](#setWrapMode-int-) | Sets word wrapping algorithm. |

### PdfFileMend {#PdfFileMend--}
```
public PdfFileMend()
```

Constructor.

### PdfFileMend {#PdfFileMend-com.aspose.pdf.IDocument-}
Constructor.

### PdfFileMend {#PdfFileMend-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-}
Constructor.

### PdfFileMend {#PdfFileMend-com.aspose.pdf.IDocument-java.lang.String-}
Constructor.

### PdfFileMend {#PdfFileMend-java.io.InputStream-java.io.OutputStream-}
Constructor.

### PdfFileMend {#PdfFileMend-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
Constructor.

### PdfFileMend {#PdfFileMend-java.lang.String-java.lang.String-}
Constructor.

### addImage {#addImage-java.io.InputStream-int:A-float-float-float-float-}
<p> Adds image to the specified pages of PDF document at specified coordinates. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.io.InputStream-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> Adds image to the specified pages of PDF document at specified coordinates. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre>

### addImage {#addImage-java.io.InputStream-int-float-float-float-float-}
<p> Adds image to the specified page of PDF document at specified coordinates. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.io.InputStream-int-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> Adds image to the specified page of PDF document at specified coordinates. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int:A-float-float-float-float-}
<p> Adds image to the specified pages of PDF document at specified coordinates. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> Adds image to the specified pages of PDF document at specified coordinates. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int-float-float-float-float-}
<p> Adds image to the specified page of PDF document at specified coordinates. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> Adds image to the specified page of PDF document at specified coordinates. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre>

### addText {#addText-com.aspose.pdf.facades.FormattedText-java.lang.Integer:A-float-float-float-float-}
Not implemented.

### addText {#addText-com.aspose.pdf.facades.FormattedText-int-float-float-}
Not implemented.

### addText {#addText-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
Not implemented.

### close {#close--}
```
public void close()
```

Closes PdfFileMend object.

### dispose {#dispose--}
```
public void dispose()
```

Closes PdfFileMend object. This method is obsolete, use close() instead.

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Gets the document {@code PdfFileMend} is working on.

**Returns:**
IDocument object

### getInputFile {#getInputFile--}
```
@Deprecated public String getInputFile()
```

Gets the input file.

**Returns:**
String value

### getInputStream {#getInputStream--}
```
public InputStream getInputStream()
```

Gets the input stream.

**Returns:**
input stream.

### getOutputFile {#getOutputFile--}
```
@Deprecated public String getOutputFile()
```

Gets the output file.

**Returns:**
String value

### getOutputStream {#getOutputStream--}
```
@Deprecated public OutputStream getOutputStream()
```

Gets the output stream.

**Returns:**
output stream.

### getTextPositioningMode {#getTextPositioningMode--}
```
public int getTextPositioningMode()
```

Gets text positioning strategy. {@code PositioningMode} Default mode is Legacy.

**Returns:**
PositioningMode element @see PositioningMode

### getWrapMode {#getWrapMode--}
```
public int getWrapMode()
```

Gets word wrapping algorithm.

**Returns:**
WordWrapMode value @see WordWrapMode

### save {#save-java.io.OutputStream-}
Saves the PDF document to the specified file.

### save {#save-java.lang.String-}
Saves the PDF document to the specified file.

### setInputFile {#setInputFile-java.lang.String-}
Deprecated.

### setInputStream {#setInputStream-java.io.InputStream-}
Sets the input stream.

### setOutputFile {#setOutputFile-java.lang.String-}
Sets the output file.

### setOutputStream {#setOutputStream-java.io.OutputStream-}
This method is Deprecated. Use Save(outputStream) method for getting facade results.

### setTextPositioningMode {#setTextPositioningMode-int-}
```
public void setTextPositioningMode(int value)
```

Sets text positioning strategy. {@code PositioningMode} Default mode is Legacy.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | PositioningMode element @see PositioningMode |

### setWordWrap {#setWordWrap-boolean-}
```
public void setWordWrap(boolean value)
```

Sets a bool value that indicates word wrap in AddText methods. If the value is true, the text in FormattedText will word wrap. By defalt, the value is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setWrapMode {#setWrapMode-int-}
```
public void setWrapMode(int value)
```

Sets word wrapping algorithm.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | WordWrapMode element @see WordWrapMode |
