---
title: TextAbsorber
second_title: Aspose.PDF for Java API Reference
description: Represents an absorber object of a text.
type: docs
weight: 286
url: /java/com.aspose.pdf/textabsorber/
---
**Inheritance:**
java.lang.Object
```
public class TextAbsorber
```

Represents an absorber object of a text. Performs text extraction and provides access to the result via  TextAbsorber.Text  object.

--------------------

> ```
> The example demonstrates how to extract text on the first PDF document page.
>  
>  // open document
>  Document doc = new Document(inFile);
>  // create TextAbsorber object to extract text
>  TextAbsorber absorber = new TextAbsorber();
>  // accept the absorber for first page
>  doc.getPages().get(1).accept(absorber);
>  // get the extracted text
>  String extractedText = absorber.getText();
> ```

--------------------

The  TextAbsorber  object is used to extract text from a Pdf document or the document's page.
## Constructors

| Constructor | Description |
| --- | --- |
| [TextAbsorber()](#TextAbsorber--) | Initializes a new instance of the  TextAbsorber . |
| [TextAbsorber(TextExtractionOptions extractionOptions)](#TextAbsorber-com.aspose.pdf.TextExtractionOptions-) | Initializes a new instance of the  TextAbsorber  with extraction options. |
## Methods

| Method | Description |
| --- | --- |
| [getText()](#getText--) | Gets extracted text that the  TextAbsorber  extracts on the PDF document or page. |
| [visit(Page page)](#visit-com.aspose.pdf.Page-) | Extracts text on the specified page |
| [visit(XForm form)](#visit-com.aspose.pdf.XForm-) | Extracts text on the specified XForm. |
| [visit(IDocument pdf)](#visit-com.aspose.pdf.IDocument-) | Extracts text on the specified document |
| [getExtractionOptions()](#getExtractionOptions--) | Gets or sets text extraction options. |
| [setExtractionOptions(TextExtractionOptions value)](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) |  |
| [getTextSearchOptions()](#getTextSearchOptions--) | Gets or sets text search options. |
| [setTextSearchOptions(TextSearchOptions value)](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) |  |
### TextAbsorber() {#TextAbsorber--}
```
public TextAbsorber()
```


Initializes a new instance of the  TextAbsorber .

--------------------

> ```
> The example demonstrates how to extract text from all pages of the PDF document.
>  
>  // open document
>  Document doc = new Document(inFile);
>  // create TextAbsorber object to extract text
>  TextAbsorber absorber = new TextAbsorber();
>  // accept the absorber for all document's pages
>  doc.getPages().accept(absorber);
>  // get the extracted text
>  String extractedText = absorber.Text;
> ```

--------------------

Performs text extraction and provides access to the extracted text via  TextAbsorber.Text  object.

### TextAbsorber(TextExtractionOptions extractionOptions) {#TextAbsorber-com.aspose.pdf.TextExtractionOptions-}
```
public TextAbsorber(TextExtractionOptions extractionOptions)
```


Initializes a new instance of the  TextAbsorber  with extraction options.

--------------------

> ```
> The example demonstrates how to extract text from all pages of the PDF document.
>  
>  // open document
>  Document doc = new Document(inFile);
>  // create TextAbsorber object to extract text with formatting
>  TextAbsorber absorber = new TextAbsorber(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure));
>  // accept the absorber for all document's pages
>  doc.getPages().accept(absorber);
>  // get the extracted text
>  string extractedText = absorber.Text;
> ```

--------------------

Performs text extraction and provides access to the extracted text via  TextAbsorber.Text  object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extractionOptions | [TextExtractionOptions](../../com.aspose.pdf/textextractionoptions) |  |

### getText() {#getText--}
```
public String getText()
```


Gets extracted text that the  TextAbsorber  extracts on the PDF document or page.

--------------------

> ```
> The example demonstrates how to extract text from all pages of the PDF document.
>  
>  // open document
>  Document doc = new Document(inFile);
>  // create TextAbsorber object to extract text
>  TextAbsorber absorber = new TextAbsorber();
>  // accept the absorber for all document's pages
>  doc.getPages().accept(absorber);
>  // get the extracted text
>  String extractedText = absorber.getText();
> ```

**Returns:**
java.lang.String
### visit(Page page) {#visit-com.aspose.pdf.Page-}
```
public void visit(Page page)
```


Extracts text on the specified page

--------------------

> ```
> The example demonstrates how to extract text on the first PDF document page.
>  
>  // open document
>  Document doc = new Document(inFile);
>  // create TextAbsorber object to extract text
>  TextAbsorber absorber = new TextAbsorber();
>  // accept the absorber for all document's pages
>  absorber.visit(doc.getPages(1));
>  // get the extracted text
>  String extractedText = absorber.Text;
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) |  |

### visit(XForm form) {#visit-com.aspose.pdf.XForm-}
```
public void visit(XForm form)
```


Extracts text on the specified XForm.

--------------------

> ```
> The example demonstrates how to extract text on the first PDF document page.
>  
>   // open document
>   Document doc = new Document(inFile);
> 
>   // create TextAbsorber object to extract text
>   TextAbsorber absorber = new TextAbsorber();
> 
>   // accept the absorber for all document's pages
>   absorber.Visit(doc.Pages[1].Resources.Forms["Xform1"]);
> 
>   // get the extracted text
>   string extractedText = absorber.Text;
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| form | [XForm](../../com.aspose.pdf/xform) |  |

### visit(IDocument pdf) {#visit-com.aspose.pdf.IDocument-}
```
public void visit(IDocument pdf)
```


Extracts text on the specified document

--------------------

> ```
> The example demonstrates how to extract text on PDF document.
>  
>  // open document
>  Document doc = new Document(inFile);
>  // create TextAbsorber object to extract text
>  TextAbsorber absorber = new TextAbsorber();
>  // accept the absorber for all document's pages
>  absorber.visit(doc);
>  // get the extracted text
>  String extractedText = absorber.Text;
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdf | [IDocument](../../com.aspose.pdf/idocument) |  |

### getExtractionOptions() {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```


Gets or sets text extraction options.

--------------------

> ```
> The example demonstrates how to set Pure text formatting mode and perform text extraction.
>  
>  // open document
>  Document doc = new Document(inFile);
>  // create TextAbsorber object to extract text with formatting
>  TextAbsorber absorber = new TextAbsorber();
>  // set pure text formatting mode
>  absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure));
>  // accept the absorber for all document's pages
>  doc.getPages().accept(absorber);
>  // get the extracted text
>  String extractedText = absorber.Text;
> ```

--------------------

Allows to define text formatting mode  TextExtractionOptions  during extraction. The default mode is  TextExtractionOptions.TextFormattingMode.Pure 

**Returns:**
[TextExtractionOptions](../../com.aspose.pdf/textextractionoptions)
### setExtractionOptions(TextExtractionOptions value) {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
```
public void setExtractionOptions(TextExtractionOptions value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextExtractionOptions](../../com.aspose.pdf/textextractionoptions) |  |

### getTextSearchOptions() {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```


Gets or sets text search options.  Allows to define rectangle which delimits the extracted text. By default the rectangle is empty. That means page boundaries only defines the text extraction region.

**Returns:**
[TextSearchOptions](../../com.aspose.pdf/textsearchoptions) - 
### setTextSearchOptions(TextSearchOptions value) {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
```
public void setTextSearchOptions(TextSearchOptions value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextSearchOptions](../../com.aspose.pdf/textsearchoptions) |  |

