---
title: PdfExtractor
second_title: Aspose.PDF for Java API Reference
description: Class for extracting images and text from PDF document.
type: docs
weight: 38
url: /java/com.aspose.pdf.facades/pdfextractor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade)
```
public final class PdfExtractor extends Facade
```

Class for extracting images and text from PDF document.
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfExtractor()](#PdfExtractor--) | Initializes new  PdfExtractor  object. |
| [PdfExtractor(IDocument document)](#PdfExtractor-com.aspose.pdf.IDocument-) | Initializes new  PdfExtractor  object on base of the  document . |
## Methods

| Method | Description |
| --- | --- |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | Initializes the facade. |
| [bindPdf(InputStream inputStream)](#bindPdf-java.io.InputStream-) | Binds PDF document from stream. |
| [bindPdf(InputStream srcStream, String password)](#bindPdf-java.io.InputStream-java.lang.String-) | Initializes the facade. |
| [bindPdf(String inputFile)](#bindPdf-java.lang.String-) | Bind input PDF file. |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | Initializes the facade. |
| [close()](#close--) | Disposes Document bound with a facade. |
| [dispose()](#dispose--) | Disposes the facade. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extractAttachment()](#extractAttachment--) | Extracts attachments from a Pdf document. |
| [extractAttachment(String attachmentFileName)](#extractAttachment-java.lang.String-) | Extracts attachment to PDF file by attachment name. |
| [extractImage()](#extractImage--) | Extract images from PDF file. |
| [extractMarkedContentAsImages(Page page, String path)](#extractMarkedContentAsImages-com.aspose.pdf.Page-java.lang.String-) | Gets all the Marked Content containers as separate images. |
| [extractText()](#extractText--) | Extracts text from a Pdf document. |
| [extractText(Charset encoding)](#extractText-java.nio.charset.Charset-) | Extracts text from a Pdf document using specified encoding. |
| [extractTextInternal(TextEncodingInternal encoding)](#extractTextInternal-com.aspose.pdf.TextEncodingInternal-) | For Internal usage only |
| [getAttachNames()](#getAttachNames--) | Returns list of attachments in PDF file. |
| [getAttachment()](#getAttachment--) | Saves all the attachment file to streams. |
| [getAttachment(String outputPath)](#getAttachment-java.lang.String-) | Stores attachment into file. |
| [getAttachmentInfo()](#getAttachmentInfo--) | Gets the list of attachments. |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | Gets the document facade is working on. |
| [getEndPage()](#getEndPage--) | Gets end page in the page range where extracting operation will be performed. |
| [getExtractImageMode()](#getExtractImageMode--) | Sets the mode for extract images process. |
| [getExtractTextMode()](#getExtractTextMode--) | Gets the mode for extract text's result. |
| [getNextImage(OutputStream outputStream)](#getNextImage-java.io.OutputStream-) | Retreive next image from PDF file and stores it into stream. |
| [getNextImage(OutputStream outputStream, ImageType format)](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-) | Retreive next image from PDF file and stores it into stream with given image format. |
| [getNextImage(String outputFile)](#getNextImage-java.lang.String-) | Retreives next image from PDF document. |
| [getNextImage(String outputFile, ImageType format)](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-) | Retreives next image from PDF document with given image format. |
| [getNextPageText(OutputStream outputStream)](#getNextPageText-java.io.OutputStream-) | Saves one page's text to stream. |
| [getNextPageText(String outputFile)](#getNextPageText-java.lang.String-) | Saves one page's text to file. |
| [getPassword()](#getPassword--) | Gets input file's password. |
| [getResolution()](#getResolution--) | Gets resolution for extracted images. |
| [getStartPage()](#getStartPage--) | Gets start page in the page range where extracting operation will be performed. |
| [getText(OutputStream outputStream)](#getText-java.io.OutputStream-) | Saves text to stream. see also: ExtractText  |
| [getText(OutputStream outputStream, boolean filterNotAscii)](#getText-java.io.OutputStream-boolean-) | Saves text to stream. see also: ExtractText  |
| [getText(String outputFile)](#getText-java.lang.String-) | Saves text to file. see also: ExtractText  |
| [getTextSearchOptions()](#getTextSearchOptions--) | Gets text search options. |
| [hasNextImage()](#hasNextImage--) | Checks if more images are accessible in PDF document. |
| [hasNextPageText()](#hasNextPageText--) | Indicates that whether can get more texts or not. |
| [hashCode()](#hashCode--) |  |
| [isBidi()](#isBidi--) | Is true when text has hebriew or arabic symbols. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEndPage(int value)](#setEndPage-int-) | Sets end page in the page range where extracting operation will be performed. |
| [setExtractImageMode(int value)](#setExtractImageMode-int-) | Sets the mode for extract images process. |
| [setExtractTextMode(int value)](#setExtractTextMode-int-) | Sets the mode for extract text's result. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Sets input file's password. |
| [setResolution(int value)](#setResolution-int-) | Set resolution for extracted images. |
| [setStartPage(int value)](#setStartPage-int-) | Sets start page in the page range where extracting operation will be performed. |
| [setTextSearchOptions(TextSearchOptions value)](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Sets text search options. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfExtractor() {#PdfExtractor--}
```
public PdfExtractor()
```


Initializes new  PdfExtractor  object.

### PdfExtractor(IDocument document) {#PdfExtractor-com.aspose.pdf.IDocument-}
```
public PdfExtractor(IDocument document)
```


Initializes new  PdfExtractor  object on base of the  document .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Pdf document. |

### bindPdf(IDocument srcDoc) {#bindPdf-com.aspose.pdf.IDocument-}
```
public void bindPdf(IDocument srcDoc)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcDoc | [IDocument](../../com.aspose.pdf/idocument) | The Document object. |

### bindPdf(InputStream inputStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream inputStream)
```


Binds PDF document from stream.

--------------------

```
PdfExtractor ext = new PdfExtractor();
 InputStream stream = new FileInputStream("sample.pdf");
 ext.bindPdf(stream);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Stream containing PDF document data |

### bindPdf(InputStream srcStream, String password) {#bindPdf-java.io.InputStream-java.lang.String-}
```
public void bindPdf(InputStream srcStream, String password)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | java.io.InputStream | The stream of PDF file. |
| password | java.lang.String | The password of the PDF document. |

### bindPdf(String inputFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String inputFile)
```


Bind input PDF file.

--------------------

```
PdfExtractor ext = new PdfExtractor();
 ext.bindPdf("sample.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | PDF fiel to bind |

### bindPdf(String srcFile, String password) {#bindPdf-java.lang.String-java.lang.String-}
```
public void bindPdf(String srcFile, String password)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcFile | java.lang.String | The PDF file |
| password | java.lang.String | The password of the PDF document. |

### close() {#close--}
```
public void close()
```


Disposes Document bound with a facade.

### dispose() {#dispose--}
```
public void dispose()
```


Disposes the facade.

This method is obsolete, use close() instead.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### extractAttachment() {#extractAttachment--}
```
public void extractAttachment()
```


Extracts attachments from a Pdf document.

### extractAttachment(String attachmentFileName) {#extractAttachment-java.lang.String-}
```
public void extractAttachment(String attachmentFileName)
```


Extracts attachment to PDF file by attachment name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| attachmentFileName | java.lang.String | Name of attachment to extract |

### extractImage() {#extractImage--}
```
public void extractImage()
```


Extract images from PDF file.

--------------------

```
PdfExtractor extractor = new PdfExtractor();
 	extractor.bindPdf("sample.pdf");
 	extractor.extractImage();
 	int i = 1;
 	while (extractor.HasNextImage())
 	{
 	    extractor.getNextImage("image-" + i +".pdf");
 	}
```

### extractMarkedContentAsImages(Page page, String path) {#extractMarkedContentAsImages-com.aspose.pdf.Page-java.lang.String-}
```
public void extractMarkedContentAsImages(Page page, String path)
```


Gets all the Marked Content containers as separate images.

Every Marked Content will be saved as image with png format named with  MCID\_.png 

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Page for process. |
| path | java.lang.String | The path where images will be saved. |

### extractText() {#extractText--}
```
public void extractText()
```


Extracts text from a Pdf document.

--------------------

```
First example demonstratres how to extract all the text from PDF file.
 
 
  PdfExtractor extractor = new PdfExtractor();
 	extractor.bindPdf("D:\Text\text.pdf");
 	extractor.extractText();
 	extractor.getText("D:\Text\text.txt");
```

Second example demonstratres how to extract each page's text into one txt file.

```
PdfExtractor extractor = new PdfExtractor();
  extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf");
  extractor.extractText();
  String prefix = TestPath + "Aspose.Pdf.Kit";
  String suffix = ".txt";
  int pageCount = 1;
  while (extractor.hasNextPageText())
  {
      extractor.getNextPageText(prefix + pageCount + suffix);
      pageCount++;
  }
```

### extractText(Charset encoding) {#extractText-java.nio.charset.Charset-}
```
public void extractText(Charset encoding)
```


Extracts text from a Pdf document using specified encoding.

--------------------

```
First example demonstrates how to extract all the text from PDF file.
 
 
  PdfExtractor extractor = new PdfExtractor();
 	extractor.bindPdf("D:\\Text\\text.pdf");
 	extractor.extractText(Encoding.Unicode);
 	extractor.getText("D:\\Text\\text.txt");
```

Second example demonstrates how to extract each page's text into one txt file.

```
PdfExtractor extractor = new PdfExtractor();
  extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf");
  extractor.extractText(java.nio.charset.Charset.forName("UTF-8"));
  String prefix = TestPath + "Aspose.Pdf.Kit";
  String suffix = ".txt";
  int pageCount = 1;
  while (extractor.hasNextPageText())
  {
      extractor.getNextPageText(prefix + pageCount + suffix);
      pageCount++;
  }
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| encoding | java.nio.charset.Charset | The encoding of the extracted text. |

### extractTextInternal(TextEncodingInternal encoding) {#extractTextInternal-com.aspose.pdf.TextEncodingInternal-}
```
public void extractTextInternal(TextEncodingInternal encoding)
```


For Internal usage only

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| encoding | [TextEncodingInternal](../../com.aspose.pdf/textencodinginternal) | The encoding of the extracted text. |

### getAttachNames() {#getAttachNames--}
```
public List<String> getAttachNames()
```


Returns list of attachments in PDF file. Note: ExtractAttachments must be called befor using this method.

--------------------

```
Example demonstrates how to extract attachment names form PDF file.
 
 
  PdfExtractor extractor = new PdfExtractor();
 	extractor.bindPdf(TestSettings.GetInputFile("sample.pdf"));
 	extractor.ExtractAttachment();
 	List attachments = extractor.getAttachNames();
 	for (String name : ```
(Iterable)
```attachments)
 		System.out.println(name);
```

**Returns:**
java.util.List<java.lang.String> - List of attachments
### getAttachment() {#getAttachment--}
```
public ByteArrayOutputStream[] getAttachment()
```


Saves all the attachment file to streams.

--------------------

```
PdfExtractor extractor = new PdfExtractor();     
 	extractor.bindPdf(path + "Attach.pdf");
 	extractor.extractAttachment();
 	IList names = extractor.getAttachNames();
 	ByteArrayOutputStream[] tempStreams =  extractor.getAttachment();
 	for (int i=0; i<tempStreams.Length; i++)
 	{
 		string name = (string)names[i];
 		OutputStream fs = new FileOutputStream(path + name);
 		fs.write(tempStreams[i].toByteArray()); 
 		fs.close();
 	}
```

**Returns:**
java.io.ByteArrayOutputStream[] - The stream array of the attachment file in the pdf document.
### getAttachment(String outputPath) {#getAttachment-java.lang.String-}
```
public void getAttachment(String outputPath)
```


Stores attachment into file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputPath | java.lang.String | Directory path where attachment(s) will be stored. Null or empty string means attachment(s) will be placed in the application directory. |

### getAttachmentInfo() {#getAttachmentInfo--}
```
public List<FileSpecification> getAttachmentInfo()
```


Gets the list of attachments.

**Returns:**
java.util.List<com.aspose.pdf.FileSpecification> - Returns an List<FileSpecificatio>.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


Gets the document facade is working on.

**Returns:**
[IDocument](../../com.aspose.pdf/idocument) - IDocument element
### getEndPage() {#getEndPage--}
```
public int getEndPage()
```


Gets end page in the page range where extracting operation will be performed.

--------------------

```
PdfExtractor ext = new PdfExtractor();
 ext.bindBdf("sample.pdf");
 ext.setStartPage(2);
 ext.setEndPage(3);
 ext.extractText();
```

**Returns:**
int - end page.
### getExtractImageMode() {#getExtractImageMode--}
```
public int getExtractImageMode()
```


Sets the mode for extract images process.

--------------------

Default value is ExtractImageMode.DefinedInResources that extracts all images defined in resources. To extract actually shown images ExtractImageMode.ActuallyUsed mode should be used.

**Returns:**
int - ExtractImageMode value
### getExtractTextMode() {#getExtractTextMode--}
```
public int getExtractTextMode()
```


Gets the mode for extract text's result.

--------------------

```
The example demonstratres the ```
ExtractTextMode
``` property usage in text extraction scenario.
 
 
  PdfExtractor extractor = new PdfExtractor();
 	extractor.bindPdf(@"D:\Text\text.pdf");
  extractor.setExtractTextMode(1);
 	extractor.extractText();
 	extractor.getText(@"D:\Text\text.txt");
```

Value: 0 is pure text mode and 1 is raw ordering mode. Default is 0.

**Returns:**
int - extract text's result.
### getNextImage(OutputStream outputStream) {#getNextImage-java.io.OutputStream-}
```
public boolean getNextImage(OutputStream outputStream)
```


Retreive next image from PDF file and stores it into stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Stream where image data will be saved |

**Returns:**
boolean - True in case the image is successfully extracted.
### getNextImage(OutputStream outputStream, ImageType format) {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-}
```
public boolean getNextImage(OutputStream outputStream, ImageType format)
```


Retreive next image from PDF file and stores it into stream with given image format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Stream where image data will be saved |
| format | [ImageType](../../com.aspose.pdf/imagetype) | The format of the image. |

**Returns:**
boolean - True in case the image is successfully extracted.
### getNextImage(String outputFile) {#getNextImage-java.lang.String-}
```
public boolean getNextImage(String outputFile)
```


Retreives next image from PDF document. Note: ExtractImage must be called before using of this method.

--------------------

```
PdfExtractor extractor = new PdfExtractor();
 	extractor.bindPdf("sample.pdf");
 	extractor.extractImage();
 	int i = 1;
 	while (extractor.hasNextImage())
 	{
 	    extractor.getNextImage("image-" + i +".pdf");
 	}
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | java.lang.String | File where image will be stored |

**Returns:**
boolean - True is image is successfully extracted
### getNextImage(String outputFile, ImageType format) {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-}
```
public boolean getNextImage(String outputFile, ImageType format)
```


Retreives next image from PDF document with given image format. Note: ExtractImage must be called before using of this method.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | java.lang.String | File where image will be stored |
| format | [ImageType](../../com.aspose.pdf/imagetype) | ImageType element |

**Returns:**
boolean - True is image is successfully extracted
### getNextPageText(OutputStream outputStream) {#getNextPageText-java.io.OutputStream-}
```
public void getNextPageText(OutputStream outputStream)
```


Saves one page's text to stream.

--------------------

```
The example demonstratres the ```
GetNextPageText
``` method usage in text extraction scenario.
 
 
  PdfExtractor extractor = new PdfExtractor();
  extractor.bindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf");
  extractor.extractText(Encoding.Unicode);
  String prefix = TestPath + "Aspose.Pdf.Kit";
  String suffix = ".txt";
  int pageCount = 1;
  while (extractor.hasNextPageText())
  {
      FileInputStream fs = new FileInputStream(prefix + pageCount + suffix, FileMode.Create);
      extractor.getNextPageText(fs);
      fs.close();
      pageCount++;
  }
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | The stream to save the text. |

### getNextPageText(String outputFile) {#getNextPageText-java.lang.String-}
```
public void getNextPageText(String outputFile)
```


Saves one page's text to file.

--------------------

```
The example demonstratres the GetNextPageText method usage in text extraction scenario.
 
 
  PdfExtractor extractor = new PdfExtractor();
  extractor.bindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf");
  extractor.extractText(Encoding.Unicode);
  String prefix = TestPath + @"Aspose.Pdf.Kit";
  String suffix = ".txt";
  int pageCount = 1;
  while (extractor.hasNextPageText())
  {
      extractor.getNextPageText(prefix + pageCount + suffix);
      pageCount++;
  }
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | java.lang.String | The file path and name to save the text. |

### getPassword() {#getPassword--}
```
public String getPassword()
```


Gets input file's password.

**Returns:**
java.lang.String - String value
### getResolution() {#getResolution--}
```
public int getResolution()
```


Gets resolution for extracted images. Default value is 150. Images which have greater resolution value are more clear. However increasing resolution value results in increasing time and memory needed to extract images. Usually to get clear image it's enough to set resolution to 150 or 300.

**Returns:**
int - int value
### getStartPage() {#getStartPage--}
```
public int getStartPage()
```


Gets start page in the page range where extracting operation will be performed.

--------------------

```
PdfExtractor ext = new PdfExtractor();
 ext.bindBdf("sample.pdf");
 ext.setStartPage(2);
 ext.setEndPage(5);
 ext.extractText();
```

**Returns:**
int - start page in the page range.
### getText(OutputStream outputStream) {#getText-java.io.OutputStream-}
```
public void getText(OutputStream outputStream)
```


Saves text to stream. see also: ExtractText 

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | The stream to save the text. |

### getText(OutputStream outputStream, boolean filterNotAscii) {#getText-java.io.OutputStream-boolean-}
```
public void getText(OutputStream outputStream, boolean filterNotAscii)
```


Saves text to stream. see also: ExtractText 

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | The stream to save the text. |
| filterNotAscii | boolean | If this parameter is true all Not ASCII simbols will be removed |

### getText(String outputFile) {#getText-java.lang.String-}
```
public void getText(String outputFile)
```


Saves text to file. see also: ExtractText 

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | java.lang.String | The file path and name to save the text. |

### getTextSearchOptions() {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```


Gets text search options.

**Returns:**
[TextSearchOptions](../../com.aspose.pdf/textsearchoptions) - text search options.
### hasNextImage() {#hasNextImage--}
```
public boolean hasNextImage()
```


Checks if more images are accessible in PDF document. Note: ExtractImage must be called before using of this method.

--------------------

```
PdfExtractor extractor = new PdfExtractor();
 	extractor.bindPdf("sample.pdf");
 	extractor.extractImage();
 	int i = 1;
 	while (extractor.hasNextImage())
 	{
 	    extractor.getNextImage("image-" + i +".pdf");
 	}
```

**Returns:**
boolean - Trues if more images are accessible
### hasNextPageText() {#hasNextPageText--}
```
public boolean hasNextPageText()
```


Indicates that whether can get more texts or not.

--------------------

```
The example demonstratres the ```
HasNextPageText
``` property usage in text extraction scenario.
 
 
  PdfExtractor extractor = new PdfExtractor();
  extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf");
  extractor.extractText(Encoding.Unicode);
  String prefix = TestPath + "Aspose.Pdf.Kit";
  String suffix = ".txt";
  int pageCount = 1;
  while (extractor.hasNextPageText())
  {
      extractor.getNextPageText(prefix + pageCount + suffix);
      pageCount++;
  }
```

**Returns:**
boolean - Can get more texts or not, true is can, or false.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isBidi() {#isBidi--}
```
public boolean isBidi()
```


Is true when text has hebriew or arabic symbols. This case must be specially considered because string functions change their behaviour and start process text from right to left (except numbers and other non text chars).

**Returns:**
boolean - boolean value
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setEndPage(int value) {#setEndPage-int-}
```
public void setEndPage(int value)
```


Sets end page in the page range where extracting operation will be performed.

--------------------

```
PdfExtractor ext = new PdfExtractor();
 ext.bindBdf("sample.pdf");
 ext.setStartPage(2);
 ext.setEndPage(3);
 ext.extractText();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | end page. |

### setExtractImageMode(int value) {#setExtractImageMode-int-}
```
public void setExtractImageMode(int value)
```


Sets the mode for extract images process.

--------------------

Default value is ExtractImageMode.DefinedInResources that extracts all images defined in resources. To extract actually shown images ExtractImageMode.ActuallyUsed mode should be used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ExtractImageMode value |

### setExtractTextMode(int value) {#setExtractTextMode-int-}
```
public void setExtractTextMode(int value)
```


Sets the mode for extract text's result.

--------------------

```
The example demonstratres the ```
ExtractTextMode
``` property usage in text extraction scenario.
 
 
  PdfExtractor extractor = new PdfExtractor();
 	extractor.bindPdf(@"D:\Text\text.pdf");
  extractor.setExtractTextMode(1);
 	extractor.extractText();
 	extractor.getText(@"D:\Text\text.txt");
```

Value: 0 is pure text mode and 1 is raw ordering mode. Default is 0.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | extract text's result. |

### setPassword(String value) {#setPassword-java.lang.String-}
```
public void setPassword(String value)
```


Sets input file's password.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setResolution(int value) {#setResolution-int-}
```
public void setResolution(int value)
```


Set resolution for extracted images. Default value is 150. Images which have greater resolution value are more clear. However increasing resolution value results in increasing time and memory needed to extract images. Usually to get clear image it's enough to set resolution to 150 or 300.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setStartPage(int value) {#setStartPage-int-}
```
public void setStartPage(int value)
```


Sets start page in the page range where extracting operation will be performed.

--------------------

```
PdfExtractor ext = new PdfExtractor();
 ext.bindBdf("sample.pdf");
 ext.setStartPage(2);
 ext.setEndPage(5);
 ext.extractText();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | start page in the page range. |

### setTextSearchOptions(TextSearchOptions value) {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
```
public void setTextSearchOptions(TextSearchOptions value)
```


Sets text search options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextSearchOptions](../../com.aspose.pdf/textsearchoptions) | text search options. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

