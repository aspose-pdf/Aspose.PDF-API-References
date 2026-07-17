---
title: PdfExtractor
linktitle: PdfExtractor
second_title: Aspose.PDF for Java API Reference
description: Class for extracting images and text from PDF document.
type: docs
weight: 400
url: /java/com.aspose.pdf.facades/pdfextractor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.PdfExtractor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.PdfExtractor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public final class PdfExtractor extends Facade
```

Class for extracting images and text from PDF document.

## Constructors

| Constructor | Description |
| --- | --- |
| [PdfExtractor](#PdfExtractor--) | / * / * Binds a Pdf document for editing. / * / * / * |
| [PdfExtractor](#PdfExtractor-com.aspose.pdf.IDocument-) | / * / * Binds a Pdf document for editing. / * / * / * |

## Methods

| Method | Description |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-) | <p> Binds PDF document from stream. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); InputStream stream = new FileInputStream("sample.pdf"); ext.bindPdf(stream); </pre> |
| [bindPdf](#bindPdf-java.lang.String-) | <p> Bind input PDF file. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindPdf("sample.pdf"); </pre> |
| [extractAttachment](#extractAttachment--) | Extracts attachments from a Pdf document. |
| [extractAttachment](#extractAttachment-java.lang.String-) | Extracts attachments from a Pdf document. |
| [extractImage](#extractImage--) | <p> Extract images from PDF file. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.HasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre> |
| [extractMarkedContentAsImages](#extractMarkedContentAsImages-com.aspose.pdf.Page-java.lang.String-) | <p> Gets all the Marked Content containers as separate images. </p> <p> Every Marked Content will be saved as image with png format named with {@code MCID_<ID number of block for the page>.png} |
| [extractText](#extractText--) | <p> Extracts text from a Pdf document. </p> <hr> <pre> First example demonstrates how to extract all the text from PDF file. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("D:\\Text\\text.pdf"); extractor.extractText(); extractor.getText("D:\\Text\\text.txt"); </pre> <p> Second example demonstrates how to extract each page's text into one txt file. <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [extractText](#extractText-java.nio.charset.Charset-) | <p> Extracts text from a Pdf document. </p> <hr> <pre> First example demonstrates how to extract all the text from PDF file. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("D:\\Text\\text.pdf"); extractor.extractText(); extractor.getText("D:\\Text\\text.txt"); </pre> <p> Second example demonstrates how to extract each page's text into one txt file. <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [extractTextInternal](#extractTextInternal-com.aspose.pdf.TextEncodingInternal-) | For Internal usage only |
| [getAttachment](#getAttachment--) | <p> Saves all the attachment file to streams. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + "Attach.pdf"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre> |
| [getAttachment](#getAttachment-java.lang.String-) | <p> Saves all the attachment file to streams. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + "Attach.pdf"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre> |
| [getAttachmentInfo](#getAttachmentInfo--) | Gets the list of attachments. |
| [getAttachNames](#getAttachNames--) | <p> Returns list of attachments in PDF file. Note: ExtractAttachments must be called before using this method. </p> <hr> <pre> Example demonstrates how to extract attachment names form PDF file. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestSettings.GetInputFile("sample.pdf")); extractor.ExtractAttachment(); List attachments = extractor.getAttachNames(); for (String name : {@code (Iterable<String>)}attachments) System.out.println(name); </pre> |
| [getEndPage](#getEndPage--) | <p> Gets end page in the page range where extracting operation will be performed. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre> |
| [getExtractImageMode](#getExtractImageMode--) | <p> Sets the mode for extract images process. </p> <hr> Default value is ExtractImageMode.DefinedInResources that extracts all images defined in resources. To extract actually shown images ExtractImageMode.ActuallyUsed mode should be used. |
| [getExtractTextMode](#getExtractTextMode--) | <p> Gets the mode for extract text's result. </p> <hr> <pre> The example demonstrates the {@code ExtractTextMode} property usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@"D:\\Text\\text.pdf"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@"D:\\Text\\text.txt"); </pre> <p> Value: 0 is pure text mode and 1 is raw ordering mode. Default is 0. |
| [getNextImage](#getNextImage-java.io.OutputStream-) | Retrieves next image from PDF file and stores it into stream. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-) | Retrieves next image from PDF file and stores it into stream with given image format. |
| [getNextImage](#getNextImage-java.lang.String-) | <p> Retrieves next image from PDF document. Note: ExtractImage must be called before using of this method. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-) | Retrieves next image from PDF document with given image format. Note: ExtractImage must be called before using of this method. |
| [getNextPageText](#getNextPageText-java.io.OutputStream-) | <p> Saves one page's text to stream. </p> <hr> <pre> The example demonstrates the {@code GetNextPageText} method usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { FileInputStream fs = new FileInputStream(prefix + pageCount + suffix, FileMode.Create); extractor.getNextPageText(fs); fs.close(); pageCount++; } </pre> |
| [getNextPageText](#getNextPageText-java.lang.String-) | <p> Saves one page's text to file. </p> <hr> <pre> The example demonstrates the GetNextPageText method usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + @"Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [getPassword](#getPassword--) | Gets input file's password. |
| [getResolution](#getResolution--) | Gets resolution for extracted images. Default value is 150. Images which have greater resolution value are more clear. However increasing resolution value results in increasing time and memory needed to extract images. Usually to get clear image it's enough to set resolution to 150 or 300. |
| [getStartPage](#getStartPage--) | Pdf.Engine object representing PDF document. |
| [getText](#getText-java.io.OutputStream-) | Saves text to stream. see also:{@code ExtractText} |
| [getText](#getText-java.io.OutputStream-boolean-) | Saves text to stream. see also:{@code ExtractText} |
| [getText](#getText-java.lang.String-) | Saves text to file. see also:{@code ExtractText} |
| [getTextSearchOptions](#getTextSearchOptions--) | Gets text search options. |
| [hasNextImage](#hasNextImage--) | <p> Checks if more images are accessible in PDF document. Note: ExtractImage must be called before using of this method. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre> |
| [hasNextPageText](#hasNextPageText--) | <p> Indicates that whether can get more texts or not. </p> <hr> <pre> The example demonstrates the {@code HasNextPageText} property usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [isBidi](#isBidi--) | Is true when text has hebriew or arabic symbols. This case must be specially considered because string functions change their behaviour and start process text from right to left (except numbers and other non text chars). |
| [setEndPage](#setEndPage-int-) | <p> Sets end page in the page range where extracting operation will be performed. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre> |
| [setExtractImageMode](#setExtractImageMode-com.aspose.pdf.ExtractImageMode-) | <p> Sets the mode for extract images process. </p> <hr> Default value is ExtractImageMode.DefinedInResources that extracts all images defined in resources. To extract actually shown images ExtractImageMode.ActuallyUsed mode should be used. |
| [setExtractTextMode](#setExtractTextMode-int-) | <p> Sets the mode for extract text's result. </p> <hr> <pre> The example demonstrates the {@code ExtractTextMode} property usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@"D:\\Text\\text.pdf"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@"D:\\Text\\text.txt"); </pre> Value: 0 is pure text mode and 1 is raw ordering mode. Default is 0. |
| [setPassword](#setPassword-java.lang.String-) | Sets input file's password. |
| [setResolution](#setResolution-int-) | Set resolution for extracted images. Default value is 150. Images which have greater resolution value are more clear. However increasing resolution value results in increasing time and memory needed to extract images. Usually to get clear image it's enough to set resolution to 150 or 300. |
| [setStartPage](#setStartPage-int-) | <p> Sets start page in the page range where extracting operation will be performed. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(5); ext.extractText(); </pre> |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Sets text search options. |

### PdfExtractor {#PdfExtractor--}
```
public PdfExtractor()
```

/ * / * Binds a Pdf document for editing. / * / * / *

### PdfExtractor {#PdfExtractor-com.aspose.pdf.IDocument-}
/ * / * Binds a Pdf document for editing. / * / * / *

### bindPdf {#bindPdf-java.io.InputStream-}
<p> Binds PDF document from stream. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); InputStream stream = new FileInputStream("sample.pdf"); ext.bindPdf(stream); </pre>

### bindPdf {#bindPdf-java.lang.String-}
<p> Bind input PDF file. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindPdf("sample.pdf"); </pre>

### extractAttachment {#extractAttachment--}
```
public void extractAttachment()
```

Extracts attachments from a Pdf document.

### extractAttachment {#extractAttachment-java.lang.String-}
Extracts attachments from a Pdf document.

### extractImage {#extractImage--}
```
public void extractImage()
```

<p> Extract images from PDF file. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.HasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre>

### extractMarkedContentAsImages {#extractMarkedContentAsImages-com.aspose.pdf.Page-java.lang.String-}
<p> Gets all the Marked Content containers as separate images. </p> <p> Every Marked Content will be saved as image with png format named with {@code MCID_<ID number of block for the page>.png}

### extractText {#extractText--}
```
public void extractText()
```

<p> Extracts text from a Pdf document. </p> <hr> <pre> First example demonstrates how to extract all the text from PDF file. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("D:\Text\text.pdf"); extractor.extractText(); extractor.getText("D:\Text\text.txt"); </pre> <p> Second example demonstrates how to extract each page's text into one txt file. <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

### extractText {#extractText-java.nio.charset.Charset-}
<p> Extracts text from a Pdf document. </p> <hr> <pre> First example demonstrates how to extract all the text from PDF file. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("D:\Text\text.pdf"); extractor.extractText(); extractor.getText("D:\Text\text.txt"); </pre> <p> Second example demonstrates how to extract each page's text into one txt file. <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

### extractTextInternal {#extractTextInternal-com.aspose.pdf.TextEncodingInternal-}
For Internal usage only

### getAttachment {#getAttachment--}
```
public ByteArrayOutputStream [] getAttachment()
```

<p> Saves all the attachment file to streams. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + "Attach.pdf"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre>

**Returns:**
The stream array of the attachment file in the pdf document.

### getAttachment {#getAttachment-java.lang.String-}
<p> Saves all the attachment file to streams. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + "Attach.pdf"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre>

**Returns:**
The stream array of the attachment file in the pdf document.

### getAttachmentInfo {#getAttachmentInfo--}
```
public List < FileSpecification > getAttachmentInfo()
```

Gets the list of attachments.

**Returns:**
Returns an List<FileSpecificatio>.

### getAttachNames {#getAttachNames--}
```
public List < String > getAttachNames()
```

<p> Returns list of attachments in PDF file. Note: ExtractAttachments must be called before using this method. </p> <hr> <pre> Example demonstrates how to extract attachment names form PDF file. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestSettings.GetInputFile("sample.pdf")); extractor.ExtractAttachment(); List attachments = extractor.getAttachNames(); for (String name : {@code (Iterable<String>)}attachments) System.out.println(name); </pre>

**Returns:**
List of attachments

### getEndPage {#getEndPage--}
```
public int getEndPage()
```

<p> Gets end page in the page range where extracting operation will be performed. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre>

**Returns:**
end page.

### getExtractImageMode {#getExtractImageMode--}
```
public ExtractImageMode getExtractImageMode()
```

<p> Sets the mode for extract images process. </p> <hr> Default value is ExtractImageMode.DefinedInResources that extracts all images defined in resources. To extract actually shown images ExtractImageMode.ActuallyUsed mode should be used.

**Returns:**
ExtractImageMode value @see ExtractImageMode

### getExtractTextMode {#getExtractTextMode--}
```
public int getExtractTextMode()
```

<p> Gets the mode for extract text's result. </p> <hr> <pre> The example demonstrates the {@code ExtractTextMode} property usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@"D:\Text\text.pdf"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@"D:\Text\text.txt"); </pre> <p> Value: 0 is pure text mode and 1 is raw ordering mode. Default is 0.

**Returns:**
extract text's result.

### getNextImage {#getNextImage-java.io.OutputStream-}
Retrieves next image from PDF file and stores it into stream.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-}
Retrieves next image from PDF file and stores it into stream with given image format.

### getNextImage {#getNextImage-java.lang.String-}
<p> Retrieves next image from PDF document. Note: ExtractImage must be called before using of this method. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-}
Retrieves next image from PDF document with given image format. Note: ExtractImage must be called before using of this method.

### getNextPageText {#getNextPageText-java.io.OutputStream-}
<p> Saves one page's text to stream. </p> <hr> <pre> The example demonstrates the {@code GetNextPageText} method usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { FileInputStream fs = new FileInputStream(prefix + pageCount + suffix, FileMode.Create); extractor.getNextPageText(fs); fs.close(); pageCount++; } </pre>

### getNextPageText {#getNextPageText-java.lang.String-}
<p> Saves one page's text to file. </p> <hr> <pre> The example demonstrates the GetNextPageText method usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + @"Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

### getPassword {#getPassword--}
```
public String getPassword()
```

Gets input file's password.

**Returns:**
String value

### getResolution {#getResolution--}
```
public int getResolution()
```

Gets resolution for extracted images. Default value is 150. Images which have greater resolution value are more clear. However increasing resolution value results in increasing time and memory needed to extract images. Usually to get clear image it's enough to set resolution to 150 or 300.

**Returns:**
int value

### getStartPage {#getStartPage--}
```
public int getStartPage()
```

Pdf.Engine object representing PDF document.

**Returns:**
start page in the page range.

### getText {#getText-java.io.OutputStream-}
Saves text to stream. see also:{@code ExtractText}

### getText {#getText-java.io.OutputStream-boolean-}
Saves text to stream. see also:{@code ExtractText}

### getText {#getText-java.lang.String-}
Saves text to file. see also:{@code ExtractText}

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

Gets text search options.

**Returns:**
text search options.

### hasNextImage {#hasNextImage--}
```
public boolean hasNextImage()
```

<p> Checks if more images are accessible in PDF document. Note: ExtractImage must be called before using of this method. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre>

**Returns:**
Trues if more images are accessible

### hasNextPageText {#hasNextPageText--}
```
public boolean hasNextPageText()
```

<p> Indicates that whether can get more texts or not. </p> <hr> <pre> The example demonstrates the {@code HasNextPageText} property usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

**Returns:**
Can get more texts or not, true is can, or false.

### isBidi {#isBidi--}
```
public boolean isBidi()
```

Is true when text has hebriew or arabic symbols. This case must be specially considered because string functions change their behaviour and start process text from right to left (except numbers and other non text chars).

**Returns:**
boolean value

### setEndPage {#setEndPage-int-}
```
public void setEndPage(int value)
```

<p> Sets end page in the page range where extracting operation will be performed. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre>

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | end page. |

### setExtractImageMode {#setExtractImageMode-com.aspose.pdf.ExtractImageMode-}
<p> Sets the mode for extract images process. </p> <hr> Default value is ExtractImageMode.DefinedInResources that extracts all images defined in resources. To extract actually shown images ExtractImageMode.ActuallyUsed mode should be used.

### setExtractTextMode {#setExtractTextMode-int-}
```
public void setExtractTextMode(int value)
```

<p> Sets the mode for extract text's result. </p> <hr> <pre> The example demonstrates the {@code ExtractTextMode} property usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@"D:\Text\text.pdf"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@"D:\Text\text.txt"); </pre> Value: 0 is pure text mode and 1 is raw ordering mode. Default is 0.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | extract text's result. |

### setPassword {#setPassword-java.lang.String-}
Sets input file's password.

### setResolution {#setResolution-int-}
```
public void setResolution(int value)
```

Set resolution for extracted images. Default value is 150. Images which have greater resolution value are more clear. However increasing resolution value results in increasing time and memory needed to extract images. Usually to get clear image it's enough to set resolution to 150 or 300.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setStartPage {#setStartPage-int-}
```
public void setStartPage(int value)
```

<p> Sets start page in the page range where extracting operation will be performed. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(5); ext.extractText(); </pre>

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | start page in the page range. |

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
Sets text search options.
