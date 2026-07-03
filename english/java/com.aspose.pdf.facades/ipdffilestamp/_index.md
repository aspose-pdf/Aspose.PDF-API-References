---
title: IPdfFileStamp
linktitle: IPdfFileStamp
second_title: Aspose.PDF for Java API Reference
description: interface for adding stamps (watermark or background) to PDF files.
type: docs
weight: 320
url: /java/com.aspose.pdf.facades/ipdffilestamp/
---
```
public interface IPdfFileStamp
```

interface for adding stamps (watermark or background) to PDF files.

## Fields

| Field | Description |
| --- | --- |
| [POS_BOTTOM_LEFT](#POS_BOTTOM_LEFT) | Bottom left position. |
| [POS_BOTTOM_MIDDLE](#POS_BOTTOM_MIDDLE) | Bottom middle position. |
| [POS_BOTTOM_RIGHT](#POS_BOTTOM_RIGHT) | Bottom right position. |
| [POS_SIDES_LEFT](#POS_SIDES_LEFT) | Left position. |
| [POS_SIDES_RIGHT](#POS_SIDES_RIGHT) | Right position. |
| [POS_UPPER_LEFT](#POS_UPPER_LEFT) | Upper let position. |
| [POS_UPPER_MIDDLE](#POS_UPPER_MIDDLE) | Upper middle position. |
| [POS_UPPER_RIGHT](#POS_UPPER_RIGHT) | Right upper position. |

## Methods

| Method | Description |
| --- | --- |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-) | Adds footer to the pages of the document. |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-) | Adds footer to the pages of the document. |
| [addFooter](#addFooter-java.io.InputStream-float-) | Adds image as footer of the page. |
| [addFooter](#addFooter-java.io.InputStream-float-float-float-) | Adds image as footer of the page. |
| [addFooter](#addFooter-java.lang.String-float-) | Adds image as footer to the pages of the document. |
| [addFooter](#addFooter-java.lang.String-float-float-float-) | Adds image as footer of the pages. |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-) | Adds header to the page. |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-) | Adds header to the pages of file. |
| [addHeader](#addHeader-java.io.InputStream-float-) | Adds image as header on the pages. |
| [addHeader](#addHeader-java.io.InputStream-float-float-float-) | Adds image at the top of the page. |
| [addHeader](#addHeader-java.lang.String-float-) | Adds image as header to the pages of the file. |
| [addHeader](#addHeader-java.lang.String-float-float-float-) | Adds image as header on the pages. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-) | Adds page number to the page. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-) | Adds page number at the specified position on the page. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-) | Adds page number to the pages. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | Adds page number to the pages of document. |
| [addPageNumber](#addPageNumber-java.lang.String-) | Add page number to file. |
| [addPageNumber](#addPageNumber-java.lang.String-float-float-) | Adds page number at the specified position on the page. |
| [addPageNumber](#addPageNumber-java.lang.String-int-) | Adds page number to the pages. |
| [addPageNumber](#addPageNumber-java.lang.String-int-float-float-float-float-) | Adds page number to the pages of document. |
| [addStamp](#addStamp-com.aspose.pdf.facades.Stamp-) | Adds stamp to the file. |
| [close](#close--) | Closes opened files and saves changes. |
| [dispose](#dispose--) | Deprecated. |
| [getAttachmentName](#getAttachmentName--) | Gets name of attachment when result of operation is stored into HttpResponse objects as attachment. |
| [getContentDisposition](#getContentDisposition--) | Gets how content will be stored when result of operation is stored into HttpResponse object. |
| [getDocument](#getDocument--) | Gets the document PdfFileStamp is working on. |
| [getInputFile](#getInputFile--) | Gets name and path of input file. |
| [getInputStream](#getInputStream--) | Gets input stream. |
| [getKeepSecurity](#getKeepSecurity--) | Keeps security if true. |
| [getOutputFile](#getOutputFile--) | Gets name and path of output file. |
| [getOutputStream](#getOutputStream--) | Gets output stream. |
| [getPageHeight](#getPageHeight--) | Gets height of first page in souorce file. |
| [getPageNumberRotation](#getPageNumberRotation--) | Gets rotation of page number. |
| [getPageWidth](#getPageWidth--) | Gets width of first page in input file. |
| [getSaveOptions](#getSaveOptions--) | Gets save options when result is stored as HttpResponse. |
| [getStartingNumber](#getStartingNumber--) | Gets or sets starting number for first page in input file. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Sets name of attachment when result of operation is stored into HttpResponse objects as attachment. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Sets how content will be stored when result of operation is stored into HttpResponse object. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Sets PDF file format. |
| [setInputFile](#setInputFile-java.lang.String-) | Sets name and path of input file. |
| [setInputStream](#setInputStream-java.io.InputStream-) | Sets input stream. |
| [setKeepSecurity](#setKeepSecurity-boolean-) | Set Keep Security |
| [setOutputFile](#setOutputFile-java.lang.String-) | Sets name and path of output file. |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | Sets or sets output stream. |
| [setPageNumberRotation](#setPageNumberRotation-float-) | Sets rotation of page number. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Sets save options when result is stored as HttpResponse. |
| [setStartingNumber](#setStartingNumber-int-) | Sets starting number for first page in input file. |

### POS_BOTTOM_LEFT {#POS_BOTTOM_LEFT}
```
static final int POS_BOTTOM_LEFT
```

Bottom left position.

### POS_BOTTOM_MIDDLE {#POS_BOTTOM_MIDDLE}
```
static final int POS_BOTTOM_MIDDLE
```

Bottom middle position.

### POS_BOTTOM_RIGHT {#POS_BOTTOM_RIGHT}
```
static final int POS_BOTTOM_RIGHT
```

Bottom right position.

### POS_SIDES_LEFT {#POS_SIDES_LEFT}
```
static final int POS_SIDES_LEFT
```

Left position.

### POS_SIDES_RIGHT {#POS_SIDES_RIGHT}
```
static final int POS_SIDES_RIGHT
```

Right position.

### POS_UPPER_LEFT {#POS_UPPER_LEFT}
```
static final int POS_UPPER_LEFT
```

Upper let position.

### POS_UPPER_MIDDLE {#POS_UPPER_MIDDLE}
```
static final int POS_UPPER_MIDDLE
```

Upper middle position.

### POS_UPPER_RIGHT {#POS_UPPER_RIGHT}
```
static final int POS_UPPER_RIGHT
```

Right upper position.

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-}
Adds footer to the pages of the document.

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-}
Adds footer to the pages of the document.

### addFooter {#addFooter-java.io.InputStream-float-}
Adds image as footer of the page.

### addFooter {#addFooter-java.io.InputStream-float-float-float-}
Adds image as footer of the page.

### addFooter {#addFooter-java.lang.String-float-}
Adds image as footer to the pages of the document.

### addFooter {#addFooter-java.lang.String-float-float-float-}
Adds image as footer of the pages.

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-}
Adds header to the page.

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-}
Adds header to the pages of file.

### addHeader {#addHeader-java.io.InputStream-float-}
Adds image as header on the pages.

### addHeader {#addHeader-java.io.InputStream-float-float-float-}
Adds image at the top of the page.

### addHeader {#addHeader-java.lang.String-float-}
Adds image as header to the pages of the file.

### addHeader {#addHeader-java.lang.String-float-float-float-}
Adds image as header on the pages.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-}
Adds page number to the page.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-}
Adds page number at the specified position on the page.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-}
Adds page number to the pages.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
Adds page number to the pages of document.

### addPageNumber {#addPageNumber-java.lang.String-}
Add page number to file.

### addPageNumber {#addPageNumber-java.lang.String-float-float-}
Adds page number at the specified position on the page.

### addPageNumber {#addPageNumber-java.lang.String-int-}
Adds page number to the pages.

### addPageNumber {#addPageNumber-java.lang.String-int-float-float-float-float-}
Adds page number to the pages of document.

### addStamp {#addStamp-com.aspose.pdf.facades.Stamp-}
Adds stamp to the file.

### close {#close--}
```
void close()
```

Closes opened files and saves changes.

### dispose {#dispose--}
```
@Deprecated void dispose()
```

Deprecated.

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

Gets name of attachment when result of operation is stored into HttpResponse objects as attachment.

**Returns:**
String value

### getContentDisposition {#getContentDisposition--}
```
ContentDisposition getContentDisposition()
```

Gets how content will be stored when result of operation is stored into HttpResponse object.

**Returns:**
ContentDisposition element

### getDocument {#getDocument--}
```
IDocument getDocument()
```

Gets the document PdfFileStamp is working on.

**Returns:**
IDocument object

### getInputFile {#getInputFile--}
```
String getInputFile()
```

Gets name and path of input file.

**Returns:**
String object

### getInputStream {#getInputStream--}
```
InputStream getInputStream()
```

Gets input stream.

**Returns:**
InputStream object

### getKeepSecurity {#getKeepSecurity--}
```
boolean getKeepSecurity()
```

Keeps security if true.

**Returns:**
boolean value

### getOutputFile {#getOutputFile--}
```
String getOutputFile()
```

Gets name and path of output file.

**Returns:**
String object

### getOutputStream {#getOutputStream--}
```
OutputStream getOutputStream()
```

Gets output stream.

**Returns:**
OutputStream object

### getPageHeight {#getPageHeight--}
```
float getPageHeight()
```

Gets height of first page in souorce file.

**Returns:**
float value

### getPageNumberRotation {#getPageNumberRotation--}
```
float getPageNumberRotation()
```

Gets rotation of page number.

**Returns:**
float value

### getPageWidth {#getPageWidth--}
```
float getPageWidth()
```

Gets width of first page in input file.

**Returns:**
float value

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

Gets save options when result is stored as HttpResponse.

**Returns:**
SaveOptions object

### getStartingNumber {#getStartingNumber--}
```
int getStartingNumber()
```

Gets or sets starting number for first page in input file.

**Returns:**
int value

### setAttachmentName {#setAttachmentName-java.lang.String-}
Sets name of attachment when result of operation is stored into HttpResponse objects as attachment.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Sets how content will be stored when result of operation is stored into HttpResponse object.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Sets PDF file format.

### setInputFile {#setInputFile-java.lang.String-}
Sets name and path of input file.

### setInputStream {#setInputStream-java.io.InputStream-}
Sets input stream.

### setKeepSecurity {#setKeepSecurity-boolean-}
```
void setKeepSecurity(boolean value)
```

Set Keep Security

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setOutputFile {#setOutputFile-java.lang.String-}
Sets name and path of output file.

### setOutputStream {#setOutputStream-java.io.OutputStream-}
Sets or sets output stream.

### setPageNumberRotation {#setPageNumberRotation-float-}
```
void setPageNumberRotation(float value)
```

Sets rotation of page number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | float value |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Sets save options when result is stored as HttpResponse.

### setStartingNumber {#setStartingNumber-int-}
```
void setStartingNumber(int value)
```

Sets starting number for first page in input file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |
