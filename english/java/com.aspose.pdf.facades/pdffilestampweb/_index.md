---
title: PdfFileStampWeb
second_title: Aspose.PDF for Java API Reference
description: Class for adding stamps (watermark or background) to PDF files. Enable to work with HttpServletResponse.
type: docs
weight: 550
url: /java/com.aspose.pdf.facades/pdffilestampweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileStampWeb, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileStampWeb, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileStampWeb

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IPdfFileStamp, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileStampWeb extends SaveableFacade implements IPdfFileStamp
```

Class for adding stamps (watermark or background) to PDF files. Enable to work with HttpServletResponse.

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

## Constructors

| Constructor | Description |
| --- | --- |
| [PdfFileStampWeb](#PdfFileStampWeb--) | <p> Constructor of the PdfFileStamp. Input file and output file may be specified via corresponding properties. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-com.aspose.pdf.IDocument-) | <p> Constructor of the PdfFileStamp. Input file and output file may be specified via corresponding properties. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Constructor of the PdfFileStamp. Input file and output file may be specified via corresponding properties. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-com.aspose.pdf.IDocument-java.lang.String-) | <p> Constructor of the PdfFileStamp. Input file and output file may be specified via corresponding properties. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-) | <p> Constructor of the PdfFileStamp. Input file and output file may be specified via corresponding properties. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.io.InputStream-java.io.OutputStream-) | <p> Constructor of the PdfFileStamp. Input file and output file may be specified via corresponding properties. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.io.InputStream-java.io.OutputStream-boolean-) | <p> Constructor of the PdfFileStamp. Input file and output file may be specified via corresponding properties. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.lang.String-javax.servlet.http.HttpServletResponse-) | <p> Constructor of the PdfFileStamp. Input file and output file may be specified via corresponding properties. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.lang.String-java.lang.String-) | <p> Constructor of the PdfFileStamp. Input file and output file may be specified via corresponding properties. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.lang.String-java.lang.String-boolean-) | <p> Constructor of the PdfFileStamp. Input file and output file may be specified via corresponding properties. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |

## Methods

| Method | Description |
| --- | --- |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-) | <p> Adds footer to the pages of the document. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addFooter(new FormattedText("Foot of the page"), 10); </pre> |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-) | <p> Adds footer to the pages of the document. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addFooter(new FormattedText("Foot of the page"), 10, 50, 50); </pre> |
| [addFooter](#addFooter-java.io.InputStream-float-) | <p> Adds image as footer of the page. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter(input, 50); fileStamp.close(); </pre> |
| [addFooter](#addFooter-java.io.InputStream-float-float-float-) | <p> Adds image as footer of the page. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter(input, 50, 50, 50); fileStamp.close(); </pre> |
| [addFooter](#addFooter-java.lang.String-float-) | <p> Adds image as footer to the pages of the document. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); fileStamp.addFooter("image.jpg", 50); fileStamp.close(); </pre> |
| [addFooter](#addFooter-java.lang.String-float-float-float-) | Adds image as footer of the pages. |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-) | <p> Adds header to the page. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addHeader(new FormattedText("Head of the page"), 50); fileStamp.close(); </pre> |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-) | <p> Adds header to the pages of file. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addHeader(new FormattedText("Head of the page"), 10, 50, 50); </pre> |
| [addHeader](#addHeader-java.io.InputStream-float-) | <p> Adds image as header on the pages. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addHeader(input, 50); fileStamp.close(); </pre> |
| [addHeader](#addHeader-java.io.InputStream-float-float-float-) | <p> Adds image at the top of the page. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addHeader(input, 50, 100, 100); fileStamp.close(); </pre> |
| [addHeader](#addHeader-java.lang.String-float-) | <p> Adds image as header to the pages of the file. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); fileStamp.addHeader("image.jpg", 50); fileStamp.close(); </pre> |
| [addHeader](#addHeader-java.lang.String-float-float-float-) | <p> Adds image as header on the pages. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); fileStamp.addHeader("image.jpg", 50, 100, 100); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-) | <p> Adds page number to the page. Page number may contain # sign which will be replaced with page number. Page number is placed in the bottom of the page centered horizontally. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #")); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-) | <p> Adds page number at the specified position on the page. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), 123, 357); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-) | <p> Adds page number to the pages. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.PosUpperRight); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | <p> Adds page number to the pages of document. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), PdfFileStamp.POS_BOTTOM_LEFT, 100, 100, 200, 200); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-) | <p> Add page number to file. Page number text may contain # sign which will be replaced with number of the page. Page number is placed in the bottom of the page centered horizontally. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #"); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-float-float-) | <p> Adds page number at the specified position on the page. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), 123, 357); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-int-) | <p> Adds page number to the pages. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.PosUpperRight); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-int-float-float-float-float-) | <p> Adds page number to the pages of document. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.POS_BOTTOM_LEFT, 100, 100, 200, 200); fileStamp.close(); </pre> |
| [addStamp](#addStamp-com.aspose.pdf.facades.Stamp-) | <p> Adds stamp to the file. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new com.aspose.pdf.facades.Stamp(); stamp.setOrigin(140, 400); stamp.setImageSize(50, 50); stamp.setOpacity ( 0.8f); stamp.isBackground ( true); stamp.bindImage("image.jpg"); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [close](#close--) | <p> Closes opened files and saves changes. Warning. If input or output streams are specified they are not closed by Close() method. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); //do some work... stamp.close(); </pre> |
| [dispose](#dispose--) | Deprecated. |
| [getAttachmentName](#getAttachmentName--) | Gets name of attachment when result of operation is stored into HttpResponse objects as attachment. |
| [getContentDisposition](#getContentDisposition--) | Gets how content will be stored when result of operation is stored into HttpResponse object. Possible value: inline / attachment. Default: inline. |
| [getInputFile](#getInputFile--) | Gets name and path of input file. |
| [getInputStream](#getInputStream--) | Gets input stream. |
| [getKeepSecurity](#getKeepSecurity--) | Keeps security if true. (This feature will be implemented in next versions). |
| [getNumberingStyle](#getNumberingStyle--) | Gets or sets pabge numbering style. |
| [getOptimizeSize](#getOptimizeSize--) | Gets or sets optimization flag. |
| [getOutputFile](#getOutputFile--) | Gets name and path of output file. |
| [getOutputStream](#getOutputStream--) | Gets output stream. |
| [getPageHeight](#getPageHeight--) | <p> Gets height of first page in source file. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); System.out.println("Height = " + fileStamp.getPageHeight()); fileStamp.close(); </pre> |
| [getPageNumberRotation](#getPageNumberRotation--) | Gets rotation of page number. Rotation is in degrees. Default is 0. |
| [getPageWidth](#getPageWidth--) | <p> Gets width of first page in input file. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); System.out.println("Width = " + fileStamp.getPageWidth()); fileStamp.close(); </pre> |
| [getResponse](#getResponse--) | Gets Response object where result of operation will be stored. |
| [getSaveOptions](#getSaveOptions--) | Gets save options when result is stored as HttpResponse. Default value: PdfSaveOptions. |
| [getStampId](#getStampId--) | Stamp ID of next added stamp (including page headers/hooters/page numbers). |
| [getStartingNumber](#getStartingNumber--) | Gets or sets starting number for first page in input file. Next pages will be numbered starting from this value. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Sets name of attachment when result of operation is stored into HttpResponse objects as attachment. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Sets how content will be stored when result of operation is stored into HttpResponse object. Possible value: inline / attachment. Default: inline. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Sets PDF file format. Result file will be saved in specified file format. If this property is not specified then file will be save in default PDF format without conversion. |
| [setInputFile](#setInputFile-java.lang.String-) | Sets name and path of input file. |
| [setInputStream](#setInputStream-java.io.InputStream-) | Sets input stream. |
| [setKeepSecurity](#setKeepSecurity-boolean-) | Keeps security if true. (This feature will be implemented in next versions). |
| [setNumberingStyle](#setNumberingStyle-com.aspose.pdf.NumberingStyle-) | Gets or sets pabge numbering style. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Gets or sets optimization flag. |
| [setOutputFile](#setOutputFile-java.lang.String-) | Sets name and path of output file. |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | Sets or sets output stream. |
| [setPageNumberRotation](#setPageNumberRotation-float-) | Sets rotation of page number. Rotation is in degrees. Default is 0. |
| [setResponse](#setResponse-javax.servlet.http.HttpServletResponse-) | Sets Response object where result of operation will be stored. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Sets save options when result is stored as HttpResponse. Default value: PdfSaveOptions. |
| [setStampId](#setStampId-int-) | Stamp ID of next added stamp (including page headers/hooters/page numbers). |
| [setStartingNumber](#setStartingNumber-int-) | <p> Sets starting number for first page in input file. Next pages will be numbered starting from this value. For example if StartingNumber is set to 100, document pages will have numbers 100, 101, 102... </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.setStartingNumber( 100); fileStamp.addPageNumber("Page #"); fileStamp.close(); </pre> |

### POS_BOTTOM_LEFT {#POS_BOTTOM_LEFT}
```
public static final int POS_BOTTOM_LEFT
```

Bottom left position.

### POS_BOTTOM_MIDDLE {#POS_BOTTOM_MIDDLE}
```
public static final int POS_BOTTOM_MIDDLE
```

Bottom middle position.

### POS_BOTTOM_RIGHT {#POS_BOTTOM_RIGHT}
```
public static final int POS_BOTTOM_RIGHT
```

Bottom right position.

### POS_SIDES_LEFT {#POS_SIDES_LEFT}
```
public static final int POS_SIDES_LEFT
```

Left position.

### POS_SIDES_RIGHT {#POS_SIDES_RIGHT}
```
public static final int POS_SIDES_RIGHT
```

Right position.

### POS_UPPER_LEFT {#POS_UPPER_LEFT}
```
public static final int POS_UPPER_LEFT
```

Upper let position.

### POS_UPPER_MIDDLE {#POS_UPPER_MIDDLE}
```
public static final int POS_UPPER_MIDDLE
```

Upper middle position.

### POS_UPPER_RIGHT {#POS_UPPER_RIGHT}
```
public static final int POS_UPPER_RIGHT
```

Right upper position.

### PdfFileStampWeb {#PdfFileStampWeb--}
```
public PdfFileStampWeb()
```

<p> Constructor of the PdfFileStamp. Input file and output file may be specified via corresponding properties. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-com.aspose.pdf.IDocument-}
<p> Constructor of the PdfFileStamp. Input file and output file may be specified via corresponding properties. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Constructor of the PdfFileStamp. Input file and output file may be specified via corresponding properties. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-com.aspose.pdf.IDocument-java.lang.String-}
<p> Constructor of the PdfFileStamp. Input file and output file may be specified via corresponding properties. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-}
<p> Constructor of the PdfFileStamp. Input file and output file may be specified via corresponding properties. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.io.InputStream-java.io.OutputStream-}
<p> Constructor of the PdfFileStamp. Input file and output file may be specified via corresponding properties. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.io.InputStream-java.io.OutputStream-boolean-}
<p> Constructor of the PdfFileStamp. Input file and output file may be specified via corresponding properties. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.lang.String-javax.servlet.http.HttpServletResponse-}
<p> Constructor of the PdfFileStamp. Input file and output file may be specified via corresponding properties. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.lang.String-java.lang.String-}
<p> Constructor of the PdfFileStamp. Input file and output file may be specified via corresponding properties. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.lang.String-java.lang.String-boolean-}
<p> Constructor of the PdfFileStamp. Input file and output file may be specified via corresponding properties. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-}
<p> Adds footer to the pages of the document. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addFooter(new FormattedText("Foot of the page"), 10); </pre>

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-}
<p> Adds footer to the pages of the document. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addFooter(new FormattedText("Foot of the page"), 10, 50, 50); </pre>

### addFooter {#addFooter-java.io.InputStream-float-}
<p> Adds image as footer of the page. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter(input, 50); fileStamp.close(); </pre>

### addFooter {#addFooter-java.io.InputStream-float-float-float-}
<p> Adds image as footer of the page. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter(input, 50, 50, 50); fileStamp.close(); </pre>

### addFooter {#addFooter-java.lang.String-float-}
<p> Adds image as footer to the pages of the document. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); fileStamp.addFooter("image.jpg", 50); fileStamp.close(); </pre>

### addFooter {#addFooter-java.lang.String-float-float-float-}
Adds image as footer of the pages.

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-}
<p> Adds header to the page. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addHeader(new FormattedText("Head of the page"), 50); fileStamp.close(); </pre>

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-}
<p> Adds header to the pages of file. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addHeader(new FormattedText("Head of the page"), 10, 50, 50); </pre>

### addHeader {#addHeader-java.io.InputStream-float-}
<p> Adds image as header on the pages. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addHeader(input, 50); fileStamp.close(); </pre>

### addHeader {#addHeader-java.io.InputStream-float-float-float-}
<p> Adds image at the top of the page. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addHeader(input, 50, 100, 100); fileStamp.close(); </pre>

### addHeader {#addHeader-java.lang.String-float-}
<p> Adds image as header to the pages of the file. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); fileStamp.addHeader("image.jpg", 50); fileStamp.close(); </pre>

### addHeader {#addHeader-java.lang.String-float-float-float-}
<p> Adds image as header on the pages. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); fileStamp.addHeader("image.jpg", 50, 100, 100); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-}
<p> Adds page number to the page. Page number may contain # sign which will be replaced with page number. Page number is placed in the bottom of the page centered horizontally. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #")); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-}
<p> Adds page number at the specified position on the page. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), 123, 357); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-}
<p> Adds page number to the pages. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.PosUpperRight); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
<p> Adds page number to the pages of document. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), PdfFileStamp.POS_BOTTOM_LEFT, 100, 100, 200, 200); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-}
<p> Add page number to file. Page number text may contain # sign which will be replaced with number of the page. Page number is placed in the bottom of the page centered horizontally. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #"); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-float-float-}
<p> Adds page number at the specified position on the page. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), 123, 357); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-int-}
<p> Adds page number to the pages. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.PosUpperRight); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-int-float-float-float-float-}
<p> Adds page number to the pages of document. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.POS_BOTTOM_LEFT, 100, 100, 200, 200); fileStamp.close(); </pre>

### addStamp {#addStamp-com.aspose.pdf.facades.Stamp-}
<p> Adds stamp to the file. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new com.aspose.pdf.facades.Stamp(); stamp.setOrigin(140, 400); stamp.setImageSize(50, 50); stamp.setOpacity ( 0.8f); stamp.isBackground ( true); stamp.bindImage("image.jpg"); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### close {#close--}
```
public void close()
```

<p> Closes opened files and saves changes. Warning. If input or output streams are specified they are not closed by Close() method. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); //do some work... stamp.close(); </pre>

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Deprecated.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Gets name of attachment when result of operation is stored into HttpResponse objects as attachment.

**Returns:**
string object

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

Gets how content will be stored when result of operation is stored into HttpResponse object. Possible value: inline / attachment. Default: inline.

**Returns:**
ContentDisposition element

### getInputFile {#getInputFile--}
```
public String getInputFile()
```

Gets name and path of input file.

**Returns:**
String object

### getInputStream {#getInputStream--}
```
public InputStream getInputStream()
```

Gets input stream.

**Returns:**
InputStream object

### getKeepSecurity {#getKeepSecurity--}
```
public boolean getKeepSecurity()
```

Keeps security if true. (This feature will be implemented in next versions).

**Returns:**
boolean value

### getNumberingStyle {#getNumberingStyle--}
```
public NumberingStyle getNumberingStyle()
```

Gets or sets pabge numbering style.

**Returns:**
NumberingStyle element

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

Gets or sets optimization flag.

**Returns:**
boolean value

### getOutputFile {#getOutputFile--}
```
public String getOutputFile()
```

Gets name and path of output file.

**Returns:**
String object

### getOutputStream {#getOutputStream--}
```
public OutputStream getOutputStream()
```

Gets output stream.

**Returns:**
OutputStream object

### getPageHeight {#getPageHeight--}
```
public float getPageHeight()
```

<p> Gets height of first page in source file. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); System.out.println("Height = " + fileStamp.getPageHeight()); fileStamp.close(); </pre>

**Returns:**
float value

### getPageNumberRotation {#getPageNumberRotation--}
```
public float getPageNumberRotation()
```

Gets rotation of page number. Rotation is in degrees. Default is 0.

**Returns:**
float value

### getPageWidth {#getPageWidth--}
```
public float getPageWidth()
```

<p> Gets width of first page in input file. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); System.out.println("Width = " + fileStamp.getPageWidth()); fileStamp.close(); </pre>

**Returns:**
float value

### getResponse {#getResponse--}
```
public javax.servlet.http.HttpServletResponse getResponse()
```

Gets Response object where result of operation will be stored.

**Returns:**
HttpServletResponse object

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Gets save options when result is stored as HttpResponse. Default value: PdfSaveOptions.

**Returns:**
SaveOptions object

### getStampId {#getStampId--}
```
public int getStampId()
```

Stamp ID of next added stamp (including page headers/hooters/page numbers).

**Returns:**
int value

### getStartingNumber {#getStartingNumber--}
```
public int getStartingNumber()
```

Gets or sets starting number for first page in input file. Next pages will be numbered starting from this value.

**Returns:**
int value

### setAttachmentName {#setAttachmentName-java.lang.String-}
Sets name of attachment when result of operation is stored into HttpResponse objects as attachment.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Sets how content will be stored when result of operation is stored into HttpResponse object. Possible value: inline / attachment. Default: inline.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Sets PDF file format. Result file will be saved in specified file format. If this property is not specified then file will be save in default PDF format without conversion.

### setInputFile {#setInputFile-java.lang.String-}
Sets name and path of input file.

### setInputStream {#setInputStream-java.io.InputStream-}
Sets input stream.

### setKeepSecurity {#setKeepSecurity-boolean-}
```
public void setKeepSecurity(boolean value)
```

Keeps security if true. (This feature will be implemented in next versions).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setNumberingStyle {#setNumberingStyle-com.aspose.pdf.NumberingStyle-}
Gets or sets pabge numbering style.

### setOptimizeSize {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```

Gets or sets optimization flag.

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
public void setPageNumberRotation(float value)
```

Sets rotation of page number. Rotation is in degrees. Default is 0.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | float value |

### setResponse {#setResponse-javax.servlet.http.HttpServletResponse-}
Sets Response object where result of operation will be stored.

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Sets save options when result is stored as HttpResponse. Default value: PdfSaveOptions.

### setStampId {#setStampId-int-}
```
public void setStampId(int value)
```

Stamp ID of next added stamp (including page headers/hooters/page numbers).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setStartingNumber {#setStartingNumber-int-}
```
public void setStartingNumber(int value)
```

<p> Sets starting number for first page in input file. Next pages will be numbered starting from this value. For example if StartingNumber is set to 100, document pages will have numbers 100, 101, 102... </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.setStartingNumber( 100); fileStamp.addPageNumber("Page #"); fileStamp.close(); </pre>

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |
