---
title: TextParagraphAbsorber
second_title: Aspose.PDF for Java API Reference
description: Represents an absorber object of text paragraphs.
type: docs
weight: 381
url: /java/com.aspose.pdf/textparagraphabsorber/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.TextAbsorber](../../com.aspose.pdf/textabsorber)
```
public final class TextParagraphAbsorber extends TextAbsorber
```

Represents an absorber object of text paragraphs. Performs text search and provides access to search results via  TextParagraphAbsorber.TextParagraphs  collection.
## Constructors

| Constructor | Description |
| --- | --- |
| [TextParagraphAbsorber(Rectangle[] rectangles)](#TextParagraphAbsorber-com.aspose.pdf.Rectangle---) | Initializes a new instance of the  TextParagraphAbsorber  with rectangles collection. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getErrors()](#getErrors--) | List of  TextExtractionError  objects. |
| [getExtractionOptions()](#getExtractionOptions--) | Gets text extraction options. |
| [getRectangles()](#getRectangles--) | Gets ractangles that the  TextParagraphAbsorber  used to searche for text paragraphs on the PDF document or page. |
| [getText()](#getText--) | Gets extracted text that the  TextAbsorber  extracts on the PDF document or page. |
| [getTextParagraphs()](#getTextParagraphs--) | Gets collection of search occurrences that are presented with  TextParagraph  objects. |
| [getTextSearchOptions()](#getTextSearchOptions--) | Gets text search options. |
| [hasErrors()](#hasErrors--) | Value indicates whether errors were found during text extraction. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setExtractionOptions(TextExtractionOptions value)](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | Sets text extraction options. |
| [setRectangles(Rectangle[] value)](#setRectangles-com.aspose.pdf.Rectangle---) | Sets rectangles that the  TextParagraphAbsorber  used to search for text paragraphs on the PDF document or page. |
| [setTextParagraphs(TextParagraphCollection value)](#setTextParagraphs-com.aspose.pdf.TextParagraphCollection-) | Sets collection of search occurrences that are presented with  TextParagraph  objects. |
| [setTextSearchOptions(TextSearchOptions value)](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Sets text search options. |
| [toString()](#toString--) |  |
| [visit(IDocument pdf)](#visit-com.aspose.pdf.IDocument-) | Extracts text on the specified document |
| [visit(Page page)](#visit-com.aspose.pdf.Page-) | Performs search on the specified page. |
| [visit(XForm form)](#visit-com.aspose.pdf.XForm-) | Extracts text on the specified XForm. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextParagraphAbsorber(Rectangle[] rectangles) {#TextParagraphAbsorber-com.aspose.pdf.Rectangle---}
```
public TextParagraphAbsorber(Rectangle[] rectangles)
```


Initializes a new instance of the  TextParagraphAbsorber  with rectangles collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangles | [Rectangle\[\]](../../com.aspose.pdf/rectangle) | The paragraphs' rectangles.

--------------------

The absorber will search for text and return paragraphs corresponding to the rectangles. |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getErrors() {#getErrors--}
```
public List<TextExtractionError> getErrors()
```


List of  TextExtractionError  objects. It contain information about errors were found during text extraction. Searching for errors will performed only if TextSearchOptions.LogTextExtractionErrors = true; And it may decrease performance.

**Returns:**
java.util.List<com.aspose.pdf.TextExtractionError> - List of TextExtractionError objects
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
### getRectangles() {#getRectangles--}
```
public Rectangle[] getRectangles()
```


Gets ractangles that the  TextParagraphAbsorber  used to searche for text paragraphs on the PDF document or page.

**Returns:**
com.aspose.pdf.Rectangle[] - rectangle array
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
### getTextParagraphs() {#getTextParagraphs--}
```
public TextParagraphCollection getTextParagraphs()
```


Gets collection of search occurrences that are presented with  TextParagraph  objects.

**Returns:**
[TextParagraphCollection](../../com.aspose.pdf/textparagraphcollection) - TextParagraphCollection value
### getTextSearchOptions() {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```


Gets text search options.

Allows to define rectangle which delimits the extracted text. By default the rectangle is empty. That means page boundaries only defines the text extraction region.

**Returns:**
[TextSearchOptions](../../com.aspose.pdf/textsearchoptions) - TextSearchOptions value
### hasErrors() {#hasErrors--}
```
public boolean hasErrors()
```


Value indicates whether errors were found during text extraction. Searching for errors will performed only if TextSearchOptions.LogTextExtractionErrors = true; And it may decrease performance.

**Returns:**
boolean - boolean value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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

### setRectangles(Rectangle[] value) {#setRectangles-com.aspose.pdf.Rectangle---}
```
public void setRectangles(Rectangle[] value)
```


Sets rectangles that the  TextParagraphAbsorber  used to search for text paragraphs on the PDF document or page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.pdf/rectangle) | rectangle array |

### setTextParagraphs(TextParagraphCollection value) {#setTextParagraphs-com.aspose.pdf.TextParagraphCollection-}
```
public void setTextParagraphs(TextParagraphCollection value)
```


Sets collection of search occurrences that are presented with  TextParagraph  objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextParagraphCollection](../../com.aspose.pdf/textparagraphcollection) | TextParagraphCollection value |

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

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

### visit(Page page) {#visit-com.aspose.pdf.Page-}
```
public void visit(Page page)
```


Performs search on the specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Page object |

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

