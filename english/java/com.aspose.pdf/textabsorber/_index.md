---
title: TextAbsorber
linktitle: TextAbsorber
second_title: Aspose.PDF for Java API Reference
description: <p> Represents an absorber object of a text. Performs text extraction and provides access to the result via {@code TextAbsorber.Text} object. </p> <hr> <pre> The example.
type: docs
weight: 4900
url: /java/com.aspose.pdf/textabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextAbsorber

```
public class TextAbsorber extends Object
```

<p> Represents an absorber object of a text. Performs text extraction and provides access to the result via {@code TextAbsorber.Text} object. </p> <hr> <pre> The example demonstrates how to extract text on the first PDF document page. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for first page doc.getPages().get(1).accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> The {@code TextAbsorber} object is used to extract text from a Pdf document or the document's page. </p>

## Constructors

| Constructor | Description |
| --- | --- |
| [TextAbsorber](#TextAbsorber--) | <p> Initializes a new instance of the {@code TextAbsorber}. </p> <hr> <pre> The example demonstrates how to extract text from all pages of the PDF document. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Performs text extraction and provides access to the extracted text via {@code TextAbsorber.Text} object. </p> |
| [TextAbsorber](#TextAbsorber-com.aspose.pdf.TextExtractionOptions-) | <p> Initializes a new instance of the {@code TextAbsorber}. </p> <hr> <pre> The example demonstrates how to extract text from all pages of the PDF document. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Performs text extraction and provides access to the extracted text via {@code TextAbsorber.Text} object. </p> |
| [TextAbsorber](#TextAbsorber-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextSearchOptions-) | <p> Initializes a new instance of the {@code TextAbsorber}. </p> <hr> <pre> The example demonstrates how to extract text from all pages of the PDF document. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Performs text extraction and provides access to the extracted text via {@code TextAbsorber.Text} object. </p> |
| [TextAbsorber](#TextAbsorber-com.aspose.pdf.TextSearchOptions-) | <p> Initializes a new instance of the {@code TextAbsorber}. </p> <hr> <pre> The example demonstrates how to extract text from all pages of the PDF document. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Performs text extraction and provides access to the extracted text via {@code TextAbsorber.Text} object. </p> |

## Methods

| Method | Description |
| --- | --- |
| [getErrors](#getErrors--) | List of {@code TextExtractionError} objects. It contain information about errors were found during text extraction. Searching for errors will performed only if TextSearchOptions.LogTextExtractionErrors = true; And it may decrease performance. |
| [getExtractionOptions](#getExtractionOptions--) | <p> Gets text extraction options. </p> <hr> <pre> The example demonstrates how to set Pure text formatting mode and perform text extraction. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Allows to define text formatting mode {@code TextExtractionOptions} during extraction. The default mode is {@code TextExtractionOptions.TextFormattingMode.Pure} </p> |
| [getText](#getText--) | <p> Gets extracted text that the {@code TextAbsorber} extracts on the PDF document or page. </p> |
| [getTextSearchOptions](#getTextSearchOptions--) | Gets text search options. Allows to define rectangle which delimits the extracted text. By default the rectangle is empty. That means page boundaries only defines the text extraction region. |
| [hasErrors](#hasErrors--) | Value indicates whether errors were found during text extraction. Searching for errors will performed only if TextSearchOptions.LogTextExtractionErrors = true; And it may decrease performance. |
| [setExtractionOptions](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | <p> Sets text extraction options. </p> <hr> <pre> The example demonstrates how to set Pure text formatting mode and perform text extraction. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Allows to define text formatting mode {@code TextExtractionOptions} during extraction. The default mode is {@code TextExtractionOptions.TextFormattingMode.Pure} </p> |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Sets text search options. Allows to define rectangle which delimits the extracted text. By default the rectangle is empty. That means page boundaries only defines the text extraction region. |
| [visit](#visit-com.aspose.pdf.IDocument-) | <p> Extracts text on the specified document </p> <hr> <pre> The example demonstrates how to extract text on PDF document. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc); // get the extracted text String extractedText = absorber.getText(); </pre> |
| [visit](#visit-com.aspose.pdf.Page-) | <p> Extracts text on the specified page </p> <hr> <pre> The example demonstrates how to extract text on the first PDF document page. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc.getPages(1)); // get the extracted text String extractedText = absorber.getText(); </pre> |
| [visit](#visit-com.aspose.pdf.XForm-) | <p> Extracts text on the specified XForm. </p> <hr> <pre> The example demonstrates how to extract text on the first PDF document page. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc.Pages().get(1).getResources().getForms().get("Xform1")); // get the extracted text String extractedText = absorber.getText(); </pre> |

### TextAbsorber {#TextAbsorber--}
```
public TextAbsorber()
```

<p> Initializes a new instance of the {@code TextAbsorber}. </p> <hr> <pre> The example demonstrates how to extract text from all pages of the PDF document. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Performs text extraction and provides access to the extracted text via {@code TextAbsorber.Text} object. </p>

### TextAbsorber {#TextAbsorber-com.aspose.pdf.TextExtractionOptions-}
<p> Initializes a new instance of the {@code TextAbsorber}. </p> <hr> <pre> The example demonstrates how to extract text from all pages of the PDF document. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Performs text extraction and provides access to the extracted text via {@code TextAbsorber.Text} object. </p>

### TextAbsorber {#TextAbsorber-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextSearchOptions-}
<p> Initializes a new instance of the {@code TextAbsorber}. </p> <hr> <pre> The example demonstrates how to extract text from all pages of the PDF document. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Performs text extraction and provides access to the extracted text via {@code TextAbsorber.Text} object. </p>

### TextAbsorber {#TextAbsorber-com.aspose.pdf.TextSearchOptions-}
<p> Initializes a new instance of the {@code TextAbsorber}. </p> <hr> <pre> The example demonstrates how to extract text from all pages of the PDF document. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Performs text extraction and provides access to the extracted text via {@code TextAbsorber.Text} object. </p>

### getErrors {#getErrors--}
```
public List < TextExtractionError > getErrors()
```

List of {@code TextExtractionError} objects. It contain information about errors were found during text extraction. Searching for errors will performed only if TextSearchOptions.LogTextExtractionErrors = true; And it may decrease performance.

**Returns:**
List of TextExtractionError objects

### getExtractionOptions {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```

<p> Gets text extraction options. </p> <hr> <pre> The example demonstrates how to set Pure text formatting mode and perform text extraction. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Allows to define text formatting mode {@code TextExtractionOptions} during extraction. The default mode is {@code TextExtractionOptions.TextFormattingMode.Pure} </p>

**Returns:**
TextExtractionOptions value

### getText {#getText--}
```
public String getText()
```

<p> Gets extracted text that the {@code TextAbsorber} extracts on the PDF document or page. </p>

**Returns:**
String value <hr> <pre> The example demonstrates how to extract text from all pages of the PDF document. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre>

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

Gets text search options. Allows to define rectangle which delimits the extracted text. By default the rectangle is empty. That means page boundaries only defines the text extraction region.

**Returns:**
TextSearchOptions value

### hasErrors {#hasErrors--}
```
public boolean hasErrors()
```

Value indicates whether errors were found during text extraction. Searching for errors will performed only if TextSearchOptions.LogTextExtractionErrors = true; And it may decrease performance.

**Returns:**
boolean value

### setExtractionOptions {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
<p> Sets text extraction options. </p> <hr> <pre> The example demonstrates how to set Pure text formatting mode and perform text extraction. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Allows to define text formatting mode {@code TextExtractionOptions} during extraction. The default mode is {@code TextExtractionOptions.TextFormattingMode.Pure} </p>

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
Sets text search options. Allows to define rectangle which delimits the extracted text. By default the rectangle is empty. That means page boundaries only defines the text extraction region.

### visit {#visit-com.aspose.pdf.IDocument-}
<p> Extracts text on the specified document </p> <hr> <pre> The example demonstrates how to extract text on PDF document. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc); // get the extracted text String extractedText = absorber.getText(); </pre>

### visit {#visit-com.aspose.pdf.Page-}
<p> Extracts text on the specified page </p> <hr> <pre> The example demonstrates how to extract text on the first PDF document page. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc.getPages(1)); // get the extracted text String extractedText = absorber.getText(); </pre>

### visit {#visit-com.aspose.pdf.XForm-}
<p> Extracts text on the specified XForm. </p> <hr> <pre> The example demonstrates how to extract text on the first PDF document page. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc.Pages().get(1).getResources().getForms().get("Xform1")); // get the extracted text String extractedText = absorber.getText(); </pre>
