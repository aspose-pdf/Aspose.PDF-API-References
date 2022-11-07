---
title: IPdfFileStamp
second_title: Aspose.PDF for Java API Reference
description: interface for adding stamps watermark or background to PDF files.
type: docs
weight: 63
url: /java/com.aspose.pdf.facades/ipdffilestamp/
---```
public interface IPdfFileStamp
```

interface for adding stamps (watermark or background) to PDF files.
## Fields

| Field | Description |
| --- | --- |
| [POS_BOTTOM_MIDDLE](#POS-BOTTOM-MIDDLE) | Bottom middle position. |
| [POS_BOTTOM_RIGHT](#POS-BOTTOM-RIGHT) | Bottom right position. |
| [POS_UPPER_RIGHT](#POS-UPPER-RIGHT) | Right upper position. |
| [POS_SIDES_RIGHT](#POS-SIDES-RIGHT) | Right position. |
| [POS_UPPER_MIDDLE](#POS-UPPER-MIDDLE) | Upper middle position. |
| [POS_BOTTOM_LEFT](#POS-BOTTOM-LEFT) | Bottom left position. |
| [POS_SIDES_LEFT](#POS-SIDES-LEFT) | Left position. |
| [POS_UPPER_LEFT](#POS-UPPER-LEFT) | Upper let position. |
## Methods

| Method | Description |
| --- | --- |
| [getKeepSecurity()](#getKeepSecurity--) | Keeps security if true. |
| [setKeepSecurity(boolean value)](#setKeepSecurity-boolean-) |  |
| [getInputFile()](#getInputFile--) | Gets name and path of input file. |
| [setInputFile(String value)](#setInputFile-java.lang.String-) | Sets name and path of input file. |
| [getInputStream()](#getInputStream--) | Gets input stream. |
| [setInputStream(InputStream value)](#setInputStream-java.io.InputStream-) | Sets input stream. |
| [getOutputFile()](#getOutputFile--) | Gets name and path of output file. |
| [setOutputFile(String value)](#setOutputFile-java.lang.String-) | Sets name and path of output file. |
| [getOutputStream()](#getOutputStream--) | Gets output stream. |
| [setOutputStream(OutputStream value)](#setOutputStream-java.io.OutputStream-) | Sets or sets output stream. |
| [getPageNumberRotation()](#getPageNumberRotation--) | Gets rotation of page number. |
| [setPageNumberRotation(float value)](#setPageNumberRotation-float-) | Sets rotation of page number. |
| [setConvertTo(int value)](#setConvertTo-int-) | Sets PDF file format. |
| [getPageHeight()](#getPageHeight--) | Gets height of first page in souorce file. |
| [getPageWidth()](#getPageWidth--) | Gets width of first page in input file. |
| [getStartingNumber()](#getStartingNumber--) | Gets or sets starting number for first page in input file. |
| [setStartingNumber(int value)](#setStartingNumber-int-) | Sets starting number for first page in input file. |
| [close()](#close--) | Closes opened files and saves changes. |
| [dispose()](#dispose--) |  |
| [addStamp(Stamp stamp)](#addStamp-com.aspose.pdf.facades.Stamp-) | Adds stamp to the file. |
| [addPageNumber(String formatString)](#addPageNumber-java.lang.String-) | Add page number to file. |
| [addPageNumber(FormattedText formattedText)](#addPageNumber-com.aspose.pdf.facades.FormattedText-) | Adds page number to the page. |
| [addPageNumber(String formatString, int position, float leftMargin, float rightMargin, float topMargin, float bottomMargin)](#addPageNumber-java.lang.String-int-float-float-float-float-) | Adds page number to the pages of document. |
| [addPageNumber(String formatString, float x, float y)](#addPageNumber-java.lang.String-float-float-) | Adds page number at the specified position on the page. |
| [addPageNumber(FormattedText formattedText, int position, float leftMargin, float rightMargin, float topMargin, float bottomMargin)](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | Adds page number to the pages of document. |
| [addPageNumber(FormattedText formattedText, float x, float y)](#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-) | Adds page number at the specified position on the page. |
| [addHeader(FormattedText formattedText, float topMargin)](#addHeader-com.aspose.pdf.facades.FormattedText-float-) | Adds header to the page. |
| [addHeader(FormattedText formattedText, float topMargin, float leftMargin, float rightMargin)](#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-) | Adds header to the pages of file. |
| [addFooter(FormattedText formattedText, float bottomMargin)](#addFooter-com.aspose.pdf.facades.FormattedText-float-) | Adds footer to the pages of the document. |
| [addFooter(FormattedText formattedText, float bottomMargin, float leftMargin, float rightMargin)](#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-) | Adds footer to the pages of the document. |
| [addPageNumber(String formatString, int position)](#addPageNumber-java.lang.String-int-) | Adds page number to the pages. |
| [addPageNumber(FormattedText formattedText, int position)](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-) | Adds page number to the pages. |
| [getDocument()](#getDocument--) | Gets the document  PdfFileStamp  is working on. |
| [getContentDisposition()](#getContentDisposition--) | Gets how content will be stored when result of operation is stored into HttpResponse object. |
| [setContentDisposition(int value)](#setContentDisposition-int-) | Sets how content will be stored when result of operation is stored into HttpResponse object. |
| [getSaveOptions()](#getSaveOptions--) | Gets save options when result is stored as HttpResponse. |
| [setSaveOptions(SaveOptions value)](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Sets save options when result is stored as HttpResponse. |
| [getAttachmentName()](#getAttachmentName--) | Gets name of attachment when result of operation is stored into HttpResponse objects as attachment. |
| [setAttachmentName(String value)](#setAttachmentName-java.lang.String-) | Sets name of attachment when result of operation is stored into HttpResponse objects as attachment. |
### POS_BOTTOM_MIDDLE {#POS-BOTTOM-MIDDLE}
```
public static final int POS_BOTTOM_MIDDLE
```


Bottom middle position.

### POS_BOTTOM_RIGHT {#POS-BOTTOM-RIGHT}
```
public static final int POS_BOTTOM_RIGHT
```


Bottom right position.

### POS_UPPER_RIGHT {#POS-UPPER-RIGHT}
```
public static final int POS_UPPER_RIGHT
```


Right upper position.

### POS_SIDES_RIGHT {#POS-SIDES-RIGHT}
```
public static final int POS_SIDES_RIGHT
```


Right position.

### POS_UPPER_MIDDLE {#POS-UPPER-MIDDLE}
```
public static final int POS_UPPER_MIDDLE
```


Upper middle position.

### POS_BOTTOM_LEFT {#POS-BOTTOM-LEFT}
```
public static final int POS_BOTTOM_LEFT
```


Bottom left position.

### POS_SIDES_LEFT {#POS-SIDES-LEFT}
```
public static final int POS_SIDES_LEFT
```


Left position.

### POS_UPPER_LEFT {#POS-UPPER-LEFT}
```
public static final int POS_UPPER_LEFT
```


Upper let position.

### getKeepSecurity() {#getKeepSecurity--}
```
public abstract boolean getKeepSecurity()
```


Keeps security if true. (This feature will be implemented in next versions).

**Returns:**
boolean
### setKeepSecurity(boolean value) {#setKeepSecurity-boolean-}
```
public abstract void setKeepSecurity(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getInputFile() {#getInputFile--}
```
public abstract String getInputFile()
```


Gets name and path of input file.

**Returns:**
java.lang.String
### setInputFile(String value) {#setInputFile-java.lang.String-}
```
public abstract void setInputFile(String value)
```


Sets name and path of input file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getInputStream() {#getInputStream--}
```
public abstract InputStream getInputStream()
```


Gets input stream.

**Returns:**
java.io.InputStream
### setInputStream(InputStream value) {#setInputStream-java.io.InputStream-}
```
public abstract void setInputStream(InputStream value)
```


Sets input stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.InputStream |  |

### getOutputFile() {#getOutputFile--}
```
public abstract String getOutputFile()
```


Gets name and path of output file.

**Returns:**
java.lang.String
### setOutputFile(String value) {#setOutputFile-java.lang.String-}
```
public abstract void setOutputFile(String value)
```


Sets name and path of output file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getOutputStream() {#getOutputStream--}
```
public abstract OutputStream getOutputStream()
```


Gets output stream.

**Returns:**
java.io.OutputStream
### setOutputStream(OutputStream value) {#setOutputStream-java.io.OutputStream-}
```
public abstract void setOutputStream(OutputStream value)
```


Sets or sets output stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.OutputStream |  |

### getPageNumberRotation() {#getPageNumberRotation--}
```
public abstract float getPageNumberRotation()
```


Gets rotation of page number. Rotation is in degrees. Default is 0.

**Returns:**
float
### setPageNumberRotation(float value) {#setPageNumberRotation-float-}
```
public abstract void setPageNumberRotation(float value)
```


Sets rotation of page number. Rotation is in degrees. Default is 0.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setConvertTo(int value) {#setConvertTo-int-}
```
public abstract void setConvertTo(int value)
```


Sets PDF file format. Result file will be saved in specified file format. If this property is not specified then file will be save in default PDF format without conversion.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPageHeight() {#getPageHeight--}
```
public abstract float getPageHeight()
```


Gets height of first page in souorce file.

--------------------

> ```
> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
>  System.out.println("Height = " + fileStamp.PageHeight);
>  fileStamp.close();
> ```

**Returns:**
float
### getPageWidth() {#getPageWidth--}
```
public abstract float getPageWidth()
```


Gets width of first page in input file.

--------------------

> ```
> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
>  System.out.println("Width = " + fileStamp.PageWidth);
>  fileStamp.close();
> ```

**Returns:**
float
### getStartingNumber() {#getStartingNumber--}
```
public abstract int getStartingNumber()
```


Gets or sets starting number for first page in input file. Next pages will be numbered starting from this value.

**Returns:**
int
### setStartingNumber(int value) {#setStartingNumber-int-}
```
public abstract void setStartingNumber(int value)
```


Sets starting number for first page in input file. Next pages will be numbered starting from this value. For example if StartingNumber is set to 100, document pages will have numbers 100, 101, 102...

--------------------

> ```
> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
>  fileStamp.setStartingNumber(100);
>  fileStamp.addPageNumber("Page #");
>  fileStamp.close();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### close() {#close--}
```
public abstract void close()
```


Closes opened files and saves changes. Warning. If input or output streams are specified they are not closed by Close() method.

--------------------

> ```
> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
>  // do some work...
>  stamp.close();
> ```

### dispose() {#dispose--}
```
public abstract void dispose()
```




### addStamp(Stamp stamp) {#addStamp-com.aspose.pdf.facades.Stamp-}
```
public abstract void addStamp(Stamp stamp)
```


Adds stamp to the file.

--------------------

> ```
> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
>  Stamp stamp = new com.aspose.pdf.facades.Stamp();
>  stamp.setOrigin(140, 400);
>  stamp.setImageSize(50, 50);
>  stamp.setOpacity(0.8f);
>  stamp.isBackground(true);
>  stamp.bindImage("image.jpg");
>  fileStamp.addStamp(stamp);
>  fileStamp.close();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stamp | [Stamp](../../com.aspose.pdf.facades/stamp) | Stamp object which. |

### addPageNumber(String formatString) {#addPageNumber-java.lang.String-}
```
public abstract void addPageNumber(String formatString)
```


Add page number to file. Page number text may contain \# sign which will be replaced with number of the page. Page number is placed in the bottom of the page centered horizontally.

--------------------

> ```
> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
>  fileStamp.addPageNumber("Page #");
>  fileStamp.close();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formatString | java.lang.String | Text of page number |

### addPageNumber(FormattedText formattedText) {#addPageNumber-com.aspose.pdf.facades.FormattedText-}
```
public abstract void addPageNumber(FormattedText formattedText)
```


Adds page number to the page. Page number may contain \# sign which will be replaced with page number. Page number is placed in the bottom of the page centered horizontally.

--------------------

> ```
> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
>  fileStamp.addPageNumber(new FormattedText("Page #"));
>  fileStamp.close();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | Format string for page number representes as FormattedText. |

### addPageNumber(String formatString, int position, float leftMargin, float rightMargin, float topMargin, float bottomMargin) {#addPageNumber-java.lang.String-int-float-float-float-float-}
```
public abstract void addPageNumber(String formatString, int position, float leftMargin, float rightMargin, float topMargin, float bottomMargin)
```


Adds page number to the pages of document.

--------------------

> ```
> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
>  fileStamp.addPageNumber("Page #", PdfFileStamp.PosBottomLeft, 100, 100, 200,
>  		200);
>  fileStamp.close();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formatString | java.lang.String | Format string for page number. |
| position | int | Position where page number will be placed on the page. 0-bottom middle, 1-bottom right, 2-upper right, 3 - sides right, 4 - upper middle,5 - bottom left,6 - sides left,7 - upper left. You can use the following constants: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | float | Margin on the left edge of the page. |
| rightMargin | float | Margin on the right edge of the page. |
| topMargin | float | Margin on the top edge of the page. |
| bottomMargin | float | Margin on the bottom edge of the page. |

### addPageNumber(String formatString, float x, float y) {#addPageNumber-java.lang.String-float-float-}
```
public abstract void addPageNumber(String formatString, float x, float y)
```


Adds page number at the specified position on the page.

--------------------

> ```
> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
>  fileStamp.addPageNumber(new FormattedText("Page  #"), 123, 357);
>  fileStamp.close();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formatString | java.lang.String | Format string. Format string can contain \# sign which will be replaced with page number. |
| x | float | X coordinate of page number. |
| y | float | Y coordinate of page number. |

### addPageNumber(FormattedText formattedText, int position, float leftMargin, float rightMargin, float topMargin, float bottomMargin) {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
```
public abstract void addPageNumber(FormattedText formattedText, int position, float leftMargin, float rightMargin, float topMargin, float bottomMargin)
```


Adds page number to the pages of document.

--------------------

> ```
> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
>  fileStamp.addPageNumber(new FormattedText("Page #"),
>  		PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
>  fileStamp.close();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | FormattedText object which represents page number format and properties iof the text. |
| position | int | Position where page number will be placed on the page. 0-bottom middle, 1-bottom right, 2-upper right, 3 - sides right, 4 - upper middle,5 - bottom left,6 - sides left,7 - upper left. You can use the following constants: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | float | Margin on the left edge of the page. |
| rightMargin | float | Margin on the right edge of the page. |
| topMargin | float | Margin on the top edge of the page. |
| bottomMargin | float | Margin on the bottom edge of the page. |

### addPageNumber(FormattedText formattedText, float x, float y) {#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-}
```
public abstract void addPageNumber(FormattedText formattedText, float x, float y)
```


Adds page number at the specified position on the page.

--------------------

> ```
> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
>  fileStamp.addPageNumber(new FormattedText("Page  #"), 123, 357);
>  fileStamp.close();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | Formatted text which represents page number format and properties of the text. Format string can contain \# sign which will be replaced with page number. |
| x | float | X coordinate of page number. |
| y | float | Y coordinate of page number. |

### addHeader(FormattedText formattedText, float topMargin) {#addHeader-com.aspose.pdf.facades.FormattedText-float-}
```
public abstract void addHeader(FormattedText formattedText, float topMargin)
```


Adds header to the page.

--------------------

> ```
> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
>  fileStamp.addHeader(new FormattedText("Head of the page"), 50);
>  fileStamp.close();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | Text for header and properties of the text. |
| topMargin | float | Margin on the top of page. |

### addHeader(FormattedText formattedText, float topMargin, float leftMargin, float rightMargin) {#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-}
```
public abstract void addHeader(FormattedText formattedText, float topMargin, float leftMargin, float rightMargin)
```


Adds header to the pages of file.

--------------------

> ```
> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
>  stamp.addHeader(new FormattedText("Head of the page"), 10, 50, 50);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | Formatted text object which contains page text and its properties. |
| topMargin | float | Margin on the top of the page. |
| leftMargin | float | Margin on the left of the page. |
| rightMargin | float | Margin on the right of the page. |

### addFooter(FormattedText formattedText, float bottomMargin) {#addFooter-com.aspose.pdf.facades.FormattedText-float-}
```
public abstract void addFooter(FormattedText formattedText, float bottomMargin)
```


Adds footer to the pages of the document.

--------------------

> ```
> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
>  stamp.addFooter(new FormattedText("Foot of the page"), 10);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | FormattedText object which contains text of the footer and text properties. |
| bottomMargin | float | Margin at the top of page. |

### addFooter(FormattedText formattedText, float bottomMargin, float leftMargin, float rightMargin) {#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-}
```
public abstract void addFooter(FormattedText formattedText, float bottomMargin, float leftMargin, float rightMargin)
```


Adds footer to the pages of the document.

--------------------

> ```
> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
>  stamp.addFooter(new FormattedText("Foot of the page"), 10, 50, 50);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | FormattedText object which contains footer text and text properties. |
| bottomMargin | float | Margin at the bottom of the page. |
| leftMargin | float | Margin at the left side of the page. |
| rightMargin | float | Margin at the right side of the page. |

### addPageNumber(String formatString, int position) {#addPageNumber-java.lang.String-int-}
```
public abstract void addPageNumber(String formatString, int position)
```


Adds page number to the pages.

--------------------

> ```
> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
>  fileStamp.addPageNumber("Page #", PdfFileStamp.PosUpperRight);
>  fileStamp.close();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formatString | java.lang.String | Format of the page number. This text may contain \# which will be replaced with page number. |
| position | int | Position where page number will be placed on the page. 0-bottom middle, 1-bottom right, 2-upper right, 3 - sides right, 4 - upper middle,5 - bottom left,6 - sides left,7 - upper left. You can use the following constants: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

### addPageNumber(FormattedText formattedText, int position) {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-}
```
public abstract void addPageNumber(FormattedText formattedText, int position)
```


Adds page number to the pages.

--------------------

> ```
> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
>  fileStamp.addPageNumber("Page #", PdfFileStamp.PosUpperRight);
>  fileStamp.close();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | FormattedText object which contains format of the page number and text properties. This text may contain \# which will be replaced with page number. |
| position | int | Position where page number will be placed on the page. 0-bottom middle, 1-bottom right, 2-upper right, 3 - sides right, 4 - upper middle,5 - bottom left,6 - sides left,7 - upper left. You can use the following constants: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

### getDocument() {#getDocument--}
```
public abstract IDocument getDocument()
```


Gets the document  PdfFileStamp  is working on.

**Returns:**
[IDocument](../../com.aspose.pdf/idocument)
### getContentDisposition() {#getContentDisposition--}
```
public abstract int getContentDisposition()
```


Gets how content will be stored when result of operation is stored into HttpResponse object. Possible value: inline / attachment. Default: inline.

**Returns:**
int
### setContentDisposition(int value) {#setContentDisposition-int-}
```
public abstract void setContentDisposition(int value)
```


Sets how content will be stored when result of operation is stored into HttpResponse object. Possible value: inline / attachment. Default: inline.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSaveOptions() {#getSaveOptions--}
```
public abstract SaveOptions getSaveOptions()
```


Gets save options when result is stored as HttpResponse. Default value: PdfSaveOptions.

**Returns:**
[SaveOptions](../../com.aspose.pdf/saveoptions)
### setSaveOptions(SaveOptions value) {#setSaveOptions-com.aspose.pdf.SaveOptions-}
```
public abstract void setSaveOptions(SaveOptions value)
```


Sets save options when result is stored as HttpResponse. Default value: PdfSaveOptions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SaveOptions](../../com.aspose.pdf/saveoptions) |  |

### getAttachmentName() {#getAttachmentName--}
```
public abstract String getAttachmentName()
```


Gets name of attachment when result of operation is stored into HttpResponse objects as attachment.

**Returns:**
java.lang.String
### setAttachmentName(String value) {#setAttachmentName-java.lang.String-}
```
public abstract void setAttachmentName(String value)
```


Sets name of attachment when result of operation is stored into HttpResponse objects as attachment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

