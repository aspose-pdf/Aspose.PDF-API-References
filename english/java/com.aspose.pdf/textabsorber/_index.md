---
title: TextAbsorber
second_title: Aspose.PDF for Java API Reference
description: Represents an absorber object of a text.
type: docs
weight: 364
url: /java/com.aspose.pdf/textabsorber/
---
**Inheritance:**
java.lang.Object
```
public class TextAbsorber
```

Represents an absorber object of a text. Performs text extraction and provides access to the result via  TextAbsorber.Text  object.

--------------------

```
The example demonstrates how to extract text on the first PDF document page.
 
 // open document
 Document doc = new Document(inFile);
 // create TextAbsorber object to extract text
 TextAbsorber absorber = new TextAbsorber();
 // accept the absorber for first page
 doc.getPages().get(1).accept(absorber);
 // get the extracted text
 String extractedText = absorber.getText();
```

--------------------

The  TextAbsorber  object is used to extract text from a Pdf document or the document's page.
## Constructors

| Constructor | Description |
| --- | --- |
| [TextAbsorber()](#TextAbsorber--) | Initializes a new instance of the  TextAbsorber . |
| [TextAbsorber(TextExtractionOptions extractionOptions)](#TextAbsorber-com.aspose.pdf.TextExtractionOptions-) | Initializes a new instance of the  TextAbsorber  with extraction options. |
| [TextAbsorber(TextExtractionOptions extractionOptions, TextSearchOptions textSearchOptions)](#TextAbsorber-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextSearchOptions-) | Initializes a new instance of the  TextAbsorber  with extraction and text search options. |
| [TextAbsorber(TextSearchOptions textSearchOptions)](#TextAbsorber-com.aspose.pdf.TextSearchOptions-) | Initializes a new instance of the  TextAbsorber  with text search options. |
## Methods

| Method | Description |
| --- | --- |
| [getText()](#getText--) | Gets extracted text that the  TextAbsorber  extracts on the PDF document or page. |
| [hasErrors()](#hasErrors--) | Value indicates whether errors were found during text extraction. |
| [getErrors()](#getErrors--) | List of  TextExtractionError  objects. |
| [visit(Page page)](#visit-com.aspose.pdf.Page-) | Extracts text on the specified page |
| [visit(XForm form)](#visit-com.aspose.pdf.XForm-) | Extracts text on the specified XForm. |
| [visit(IDocument pdf)](#visit-com.aspose.pdf.IDocument-) | Extracts text on the specified document |
| [getExtractionOptions()](#getExtractionOptions--) | Gets text extraction options. |
| [setExtractionOptions(TextExtractionOptions value)](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | Sets text extraction options. |
| [getTextSearchOptions()](#getTextSearchOptions--) | Gets text search options. |
| [setTextSearchOptions(TextSearchOptions value)](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Sets text search options. |
### TextAbsorber() {#TextAbsorber--}
```
public TextAbsorber()
```


Initializes a new instance of the  TextAbsorber .

--------------------

```
The example demonstrates how to extract text from all pages of the PDF document.
 
 // open document
 Document doc = new Document(inFile);
 // create TextAbsorber object to extract text
 TextAbsorber absorber = new TextAbsorber();
 // accept the absorber for all document's pages
 doc.getPages().accept(absorber);
 // get the extracted text
 String extractedText = absorber.getText();
```

--------------------

Performs text extraction and provides access to the extracted text via  TextAbsorber.Text  object.

### TextAbsorber(TextExtractionOptions extractionOptions) {#TextAbsorber-com.aspose.pdf.TextExtractionOptions-}
```
public TextAbsorber(TextExtractionOptions extractionOptions)
```


Initializes a new instance of the  TextAbsorber  with extraction options.

--------------------

```
The example demonstrates how to extract text from all pages of the PDF document.
 
 // open document
 Document doc = new Document(inFile);
 // create TextAbsorber object to extract text with formatting
 TextAbsorber absorber = new TextAbsorber(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure));
 // accept the absorber for all document's pages
 doc.getPages().accept(absorber);
 // get the extracted text
 String extractedText = absorber.getText();
```

--------------------

Performs text extraction and provides access to the extracted text via  TextAbsorber.Text  object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extractionOptions | [TextExtractionOptions](../../com.aspose.pdf/textextractionoptions) | Text extraction options

-------------------- |

### TextAbsorber(TextExtractionOptions extractionOptions, TextSearchOptions textSearchOptions) {#TextAbsorber-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextSearchOptions-}
```
public TextAbsorber(TextExtractionOptions extractionOptions, TextSearchOptions textSearchOptions)
```


Initializes a new instance of the  TextAbsorber  with extraction and text search options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extractionOptions | [TextExtractionOptions](../../com.aspose.pdf/textextractionoptions) | Text extraction options |
| textSearchOptions | [TextSearchOptions](../../com.aspose.pdf/textsearchoptions) | Text search options

--------------------

Performs text extraction and provides access to the extracted text via  TextAbsorber.Text  object. |

### TextAbsorber(TextSearchOptions textSearchOptions) {#TextAbsorber-com.aspose.pdf.TextSearchOptions-}
```
public TextAbsorber(TextSearchOptions textSearchOptions)
```


Initializes a new instance of the  TextAbsorber  with text search options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| textSearchOptions | [TextSearchOptions](../../com.aspose.pdf/textsearchoptions) | Text search options

--------------------

Performs text extraction and provides access to the extracted text via  TextAbsorber.Text  object. |

### getText() {#getText--}
```
public String getText()
```


Gets extracted text that the  TextAbsorber  extracts on the PDF document or page.

**Returns:**
java.lang.String - String value

--------------------

```
The example demonstrates how to extract text from all pages of the PDF document.
 
 // open document
 Document doc = new Document(inFile);
 // create TextAbsorber object to extract text
 TextAbsorber absorber = new TextAbsorber();
 // accept the absorber for all document's pages
 doc.getPages().accept(absorber);
 // get the extracted text
 String extractedText = absorber.getText();
```
### hasErrors() {#hasErrors--}
```
public boolean hasErrors()
```


Value indicates whether errors were found during text extraction. Searching for errors will performed only if TextSearchOptions.LogTextExtractionErrors = true; And it may decrease performance.

**Returns:**
boolean - boolean value
### getErrors() {#getErrors--}
```
public List<TextExtractionError> getErrors()
```


List of  TextExtractionError  objects. It contain information about errors were found during text extraction. Searching for errors will performed only if TextSearchOptions.LogTextExtractionErrors = true; And it may decrease performance.

**Returns:**
java.util.List<com.aspose.pdf.TextExtractionError> - List of TextExtractionError objects
### visit(Page page) {#visit-com.aspose.pdf.Page-}
```
public void visit(Page page)
```


Extracts text on the specified page

--------------------

```
The example demonstrates how to extract text on the first PDF document page.
 
 // open document
 Document doc = new Document(inFile);
 // create TextAbsorber object to extract text
 TextAbsorber absorber = new TextAbsorber();
 // accept the absorber for all document's pages
 absorber.visit(doc.getPages(1));
 // get the extracted text
 String extractedText = absorber.getText();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Pdf pocument page object. |

### visit(XForm form) {#visit-com.aspose.pdf.XForm-}
```
public void visit(XForm form)
```


Extracts text on the specified XForm.

--------------------

```
The example demonstrates how to extract text on the first PDF document page.
 
  // open document
  Document doc = new Document(inFile);
  
  // create TextAbsorber object to extract text
  TextAbsorber absorber = new TextAbsorber();
   
  // accept the absorber for all document's pages
  absorber.visit(doc.Pages().get(1).getResources().getForms().get("Xform1"));
     
  // get the extracted text
  String extractedText = absorber.getText();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| form | [XForm](../../com.aspose.pdf/xform) | Pdf form object. |

### visit(IDocument pdf) {#visit-com.aspose.pdf.IDocument-}
```
public void visit(IDocument pdf)
```


Extracts text on the specified document

--------------------

```
The example demonstrates how to extract text on PDF document.
 
 // open document
 Document doc = new Document(inFile);
 // create TextAbsorber object to extract text
 TextAbsorber absorber = new TextAbsorber();
 // accept the absorber for all document's pages
 absorber.visit(doc);
 // get the extracted text
 String extractedText = absorber.getText();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdf | [IDocument](../../com.aspose.pdf/idocument) | Pdf pocument object. |

### getExtractionOptions() {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```


Gets text extraction options.

--------------------

```
The example demonstrates how to set Pure text formatting mode and perform text extraction.
 
 // open document
 Document doc = new Document(inFile);
 // create TextAbsorber object to extract text with formatting
 TextAbsorber absorber = new TextAbsorber();
 // set pure text formatting mode
 absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure));
 // accept the absorber for all document's pages
 doc.getPages().accept(absorber);
 // get the extracted text
 String extractedText = absorber.getText();
```

--------------------

Allows to define text formatting mode  TextExtractionOptions  during extraction. The default mode is  TextExtractionOptions.TextFormattingMode.Pure 

**Returns:**
[TextExtractionOptions](../../com.aspose.pdf/textextractionoptions) - TextExtractionOptions value
### setExtractionOptions(TextExtractionOptions value) {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
```
public void setExtractionOptions(TextExtractionOptions value)
```


Sets text extraction options.

--------------------

```
The example demonstrates how to set Pure text formatting mode and perform text extraction.
 
 // open document
 Document doc = new Document(inFile);
 // create TextAbsorber object to extract text with formatting
 TextAbsorber absorber = new TextAbsorber();
 // set pure text formatting mode
 absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure));
 // accept the absorber for all document's pages
 doc.getPages().accept(absorber);
 // get the extracted text
 String extractedText = absorber.getText();
```

--------------------

Allows to define text formatting mode  TextExtractionOptions  during extraction. The default mode is  TextExtractionOptions.TextFormattingMode.Pure 

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextExtractionOptions](../../com.aspose.pdf/textextractionoptions) | TextExtractionOptions value |

### getTextSearchOptions() {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```


Gets text search options.

Allows to define rectangle which delimits the extracted text. By default the rectangle is empty. That means page boundaries only defines the text extraction region.

**Returns:**
[TextSearchOptions](../../com.aspose.pdf/textsearchoptions) - TextSearchOptions value
### setTextSearchOptions(TextSearchOptions value) {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
```
public void setTextSearchOptions(TextSearchOptions value)
```


Sets text search options.

Allows to define rectangle which delimits the extracted text. By default the rectangle is empty. That means page boundaries only defines the text extraction region.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextSearchOptions](../../com.aspose.pdf/textsearchoptions) | TextSearchOptions value |

