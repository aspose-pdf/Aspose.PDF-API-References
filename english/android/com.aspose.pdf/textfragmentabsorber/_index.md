---
title: TextFragmentAbsorber
second_title: Aspose.PDF for Java API Reference
description: Represents an absorber object of text fragments.
type: docs
weight: 296
url: /java/com.aspose.pdf/textfragmentabsorber/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.TextAbsorber](../../com.aspose.pdf/textabsorber)
```
public final class TextFragmentAbsorber extends TextAbsorber
```

Represents an absorber object of text fragments. Performs text search and provides access to search results via  TextFragmentAbsorber.TextFragments  collection.

--------------------

> ```
> The example demonstrates how to find text on the first PDF document page and replace the text and it's font.
>   
>  // Open document
>  Document doc = new Document("D:\Tests\input.pdf");
>  // Find font that will be used to change document text font
>  com.aspose.pdf.Font font = FontRepository.FindFont("Arial");
>  // Create TextFragmentAbsorber object to find all "hello world" text occurrences
>  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
>  // Accept the absorber for first page
>  doc.getPages().get(1).accept(absorber);
>  // Change text and font of the first text occurrence
>  absorber.getTextFragments().get_Item(1).setText ( "hi world");
>  absorber.getTextFragments().get_Item(1).getTextState().setFont ( font);
>  // Save document
>  doc.save("D:\Tests\output.pdf");
> ```

--------------------

The  TextFragmentAbsorber  object is basically used in text search scenario. When the search is completed the occurrences are represented with  TextFragment  objects that the  TextFragmentAbsorber.TextFragments  collection contains. The  TextFragment  object provides access to the search occurrence text, text properties, and allows to edit text and change the text state (font, font size, color etc).
## Constructors

| Constructor | Description |
| --- | --- |
| [TextFragmentAbsorber()](#TextFragmentAbsorber--) | Initializes a new instance of the  TextFragmentAbsorber  that performs search of all text segments of the document or page. |
| [TextFragmentAbsorber(TextEditOptions textEditOptions)](#TextFragmentAbsorber-com.aspose.pdf.TextEditOptions-) | Initializes a new instance of the  TextFragmentAbsorber  with text edit options, that performs search of all text segments of the document or page. |
| [TextFragmentAbsorber(String phrase)](#TextFragmentAbsorber-java.lang.String-) | Initializes a new instance of the  TextFragmentAbsorber  class for the specified text phrase. |
| [TextFragmentAbsorber(String phrase, TextSearchOptions textSearchOptions)](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-) | Initializes a new instance of the  TextFragmentAbsorber  class for the specified text phrase and text search options. |
| [TextFragmentAbsorber(String phrase, TextSearchOptions textSearchOptions, TextEditOptions textEditOptions)](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-com.aspose.pdf.TextEditOptions-) | Initializes a new instance of the  TextFragmentAbsorber  class for the specified text phrase, text search options and text edit options. |
| [TextFragmentAbsorber(String phrase, TextEditOptions textEditOptions)](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextEditOptions-) | Initializes a new instance of the  TextFragmentAbsorber  class for the specified text phrase and text edit options. |
## Methods

| Method | Description |
| --- | --- |
| [getTextFragments()](#getTextFragments--) | Gets collection of search occurrences that are presented with  TextFragment  objects. |
| [setTextFragments(TextFragmentCollection value)](#setTextFragments-com.aspose.pdf.TextFragmentCollection-) | Sets collection of search occurrences that are presented with  TextFragment  objects. |
| [getPhrase()](#getPhrase--) | Gets phrase that the  TextFragmentAbsorber  searches on the PDF document or page. |
| [setPhrase(String value)](#setPhrase-java.lang.String-) | Gets phrase that the  TextFragmentAbsorber  searches on the PDF document or page. |
| [getTextSearchOptions()](#getTextSearchOptions--) | Gets search options. |
| [setTextSearchOptions(TextSearchOptions value)](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Sets search options. |
| [getTextEditOptions()](#getTextEditOptions--) | Gets text edit options. |
| [setTextEditOptions(TextEditOptions value)](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Sets text edit options. |
| [visit(Page page)](#visit-com.aspose.pdf.Page-) | Performs search on the specified page. |
| [visit(IDocument pdf)](#visit-com.aspose.pdf.IDocument-) | Performs search on the specified document. |
| [visit(XForm xForm)](#visit-com.aspose.pdf.XForm-) | Performs search on the specified form object. |
| [getExtractionOptions()](#getExtractionOptions--) | Gets or sets text extraction options. |
| [setExtractionOptions(TextExtractionOptions value)](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) |  |
| [getTextReplaceOptions()](#getTextReplaceOptions--) | Gets text replace options. |
| [setTextReplaceOptions(TextReplaceOptions value)](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | Sets text replace options. |
### TextFragmentAbsorber() {#TextFragmentAbsorber--}
```
public TextFragmentAbsorber()
```


Initializes a new instance of the  TextFragmentAbsorber  that performs search of all text segments of the document or page.

--------------------

> ```
> The example demonstrates how to find text on the first PDF document page and replace the text.
>   
>  // Open document
>  Document doc = new Document("D:\Tests\input.pdf");
>  // Find font that will be used to change document text font
>  Font font = FontRepository.findFont("Arial");
>  // Create TextFragmentAbsorber object
>  TextFragmentAbsorber absorber = new TextFragmentAbsorber();
>  // Make the absorber to search all "hello world" text occurrences
>  absorber.setPhrase ( "hello world");
>  // Accept the absorber for first page
>  doc.getPages().get(1).accept(absorber);
>  // Change text of the first text occurrence
>  absorber.getTextFragments().get_Item(1).setText ( "hi world");
>  // Save document
>  doc.save("D:\Tests\output.pdf");
> ```

--------------------

Performs text search and provides access to search results via  TextFragmentAbsorber.TextFragments  collection.

### TextFragmentAbsorber(TextEditOptions textEditOptions) {#TextFragmentAbsorber-com.aspose.pdf.TextEditOptions-}
```
public TextFragmentAbsorber(TextEditOptions textEditOptions)
```


Initializes a new instance of the  TextFragmentAbsorber  with text edit options, that performs search of all text segments of the document or page.

--------------------

> ```
> The example demonstrates how to find all text fragments on the first PDF document page and replace font for them.
>    
>   // Open document
>   Document doc = new Document(@"D:\Tests\input.pdf");
>   
>   // Create TextFragmentAbsorber object
>   TextFragmentAbsorber absorber = new TextFragmentAbsorber(new TextEditOptions(TextEditOptions.FontReplace.RemoveUnusedFonts));
>   
>   // Accept the absorber for first page
>   doc.Pages[1].Accept(absorber);
>   
>   // Find Courier font
>   Pdf.Text.Font font = FontRepository.FindFont("Courier");
>   // Set the font for all the text fragments
>   foreach (TextFragment textFragment in absorber.TextFragments)
>   {
>       textFragment.TextState.Font = font;
>   }
>   // Save document
>   doc.Save(@"D:\Tests\output.pdf");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| textEditOptions | [TextEditOptions](../../com.aspose.pdf/texteditoptions) | Text edit options (Allows to turn on some edit features).

--------------------

Performs text search and provides access to search results via  TextFragmentAbsorber.TextFragments  collection. |

### TextFragmentAbsorber(String phrase) {#TextFragmentAbsorber-java.lang.String-}
```
public TextFragmentAbsorber(String phrase)
```


Initializes a new instance of the  TextFragmentAbsorber  class for the specified text phrase.

--------------------

> ```
> The example demonstrates how to find text on the first PDF document page and replace the text and it's font.
>   
>  // Open document
>  Document doc = new Document("D:\Tests\input.pdf");
>  // Find font that will be used to change document text font
>  com.aspose.pdf.Font font = FontRepository.FindFont("Arial");
>  // Create TextFragmentAbsorber object to find all "hello world" text occurrences
>  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
>  // Accept the absorber for first page
>  doc.getPages().get(1).accept(absorber);
>  // Change text and font of the first text occurrence
>  absorber.getTextFragments().get_Item(1).setText ( "hi world");
>  absorber.getTextFragments().get_Item(1).getTextState().setFont ( font);
>  // Save document
>  doc.save("D:\Tests\output.pdf");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| phrase | java.lang.String | Phrase that the  TextFragmentAbsorber  searches

--------------------

Performs text search of the specified phrase and provides access to search results via  TextFragmentAbsorber.TextFragments  collection. |

### TextFragmentAbsorber(String phrase, TextSearchOptions textSearchOptions) {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-}
```
public TextFragmentAbsorber(String phrase, TextSearchOptions textSearchOptions)
```


Initializes a new instance of the  TextFragmentAbsorber  class for the specified text phrase and text search options.

--------------------

> ```
> The example demonstrates how to find text with regular expression on the first PDF document page and replace the text.
>   
>  // Open document
>  Document doc = new Document("D:\Tests\input.pdf");
>  // Create TextFragmentAbsorber object that seatches all words starting 'h' and ending 'o' using regular expression.
>  TextFragmentAbsorber absorber = new TextFragmentAbsorber("h\w*?o", new TextSearchOptions(true));
>  // we should find "hello" word and replace it with "Hi"
>  doc.getPages().get(1).accept(absorber);
>  absorber.getTextFragments().get_Item(1).setText ( "Hi"); 
>   
>  // Save document
>  doc.save("D:\Tests\output.pdf");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| phrase | java.lang.String | Phrase that the  TextFragmentAbsorber  searches |
| textSearchOptions | [TextSearchOptions](../../com.aspose.pdf/textsearchoptions) | Text search options (Allows to turn on some search features. For example, search with regular expression)

--------------------

Performs text search of the specified phrase and provides access to search results via  TextFragmentAbsorber.TextFragments  collection. |

### TextFragmentAbsorber(String phrase, TextSearchOptions textSearchOptions, TextEditOptions textEditOptions) {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-com.aspose.pdf.TextEditOptions-}
```
public TextFragmentAbsorber(String phrase, TextSearchOptions textSearchOptions, TextEditOptions textEditOptions)
```


Initializes a new instance of the  TextFragmentAbsorber  class for the specified text phrase, text search options and text edit options. The text edit options are not supported yet.

--------------------

> ```
> The example demonstrates how to find text with regular expression on the first PDF document page and replace the text.
>   
>  // Open document
>  Document doc = new Document("D:\Tests\input.pdf");
>  // Create TextFragmentAbsorber object that seatches all words starting 'h' and ending 'o' using regular expression.
>  TextFragmentAbsorber absorber = new TextFragmentAbsorber("h\w*?o", new TextSearchOptions(true));
>  // we should find "hello" word and replace it with "Hi"
>  doc.getPages().get(1).accept(absorber);
>  absorber.getTextFragments().get_Item(1).setText ( "Hi"); 
>  // Save document
>  doc.save("D:\Tests\output.pdf");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| phrase | java.lang.String | Phrase that the  TextFragmentAbsorber  searches |
| textSearchOptions | [TextSearchOptions](../../com.aspose.pdf/textsearchoptions) | Text search options (Allows to turn on some search features. For example, search with regular expression) |
| textEditOptions | [TextEditOptions](../../com.aspose.pdf/texteditoptions) | Text edit options (Allows to turn on some edit features. For example, define special behavior when requested symbol cannot be written with font). The parameter is not supported yet.

--------------------

Performs text search of the specified phrase and provides access to search results via  TextFragmentAbsorber.TextFragments  collection. |

### TextFragmentAbsorber(String phrase, TextEditOptions textEditOptions) {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextEditOptions-}
```
public TextFragmentAbsorber(String phrase, TextEditOptions textEditOptions)
```


Initializes a new instance of the  TextFragmentAbsorber  class for the specified text phrase and text edit options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| phrase | java.lang.String | Phrase that the  TextFragmentAbsorber  searches |
| textEditOptions | [TextEditOptions](../../com.aspose.pdf/texteditoptions) | Text edit options (Allows to turn on some edit features).

--------------------

Performs text search of the specified phrase and provides access to search results via  TextFragmentAbsorber.TextFragments  collection. |

### getTextFragments() {#getTextFragments--}
```
public TextFragmentCollection getTextFragments()
```


Gets collection of search occurrences that are presented with  TextFragment  objects.

--------------------

> ```
> The example demonstrates how to find text on the first PDF document page and replace all search occurrences with new text.
>   
>  // Open document
>  Document doc = new Document("D:\Tests\input.pdf");
>  // Find font that will be used to change document text font
>  Font font = FontRepository.FindFont("Arial");
>  // Create TextFragmentAbsorber object to find all "hello world" text occurrences
>  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
>  // Accept the absorber for first page
>  doc.getPages().get(1).accept(absorber);
>  // Change text of all search occurrences
>  for (TextFragment textFragment : absorber.getTextFragments())
>  {
>      textFragment.setText ( "hi world");
>  }
>  // Save document
>  doc.save("D:\Tests\output.pdf");
> ```

**Returns:**
[TextFragmentCollection](../../com.aspose.pdf/textfragmentcollection)
### setTextFragments(TextFragmentCollection value) {#setTextFragments-com.aspose.pdf.TextFragmentCollection-}
```
public void setTextFragments(TextFragmentCollection value)
```


Sets collection of search occurrences that are presented with  TextFragment  objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextFragmentCollection](../../com.aspose.pdf/textfragmentcollection) |  |

### getPhrase() {#getPhrase--}
```
public String getPhrase()
```


Gets phrase that the  TextFragmentAbsorber  searches on the PDF document or page.

--------------------

> ```
> The example demonstrates how to perform search text several times and perform text replacements.
>   
>  // Open document
>  Document doc = new Document("D:\Tests\input.pdf");
>  // Create TextFragmentAbsorber object to find all "hello" text occurrences
>  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello");
>  doc.getPages().get(1).accept(absorber);
>  absorber.getTextFragments().get_Item(1).setText ( "Hi");
>  // search another word and replace it
>  absorber.setPhrase ( "world");
>  doc.getPages().get(1).accept(absorber);
>  absorber.getTextFragments().get_Item(1).setText ( "John");
>  // Save document
>  doc.save("D:\Tests\output.pdf");
> ```

**Returns:**
java.lang.String
### setPhrase(String value) {#setPhrase-java.lang.String-}
```
public void setPhrase(String value)
```


Gets phrase that the  TextFragmentAbsorber  searches on the PDF document or page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextSearchOptions() {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```


Gets search options. The options enable search using regular expressions.

--------------------

> ```
> The example demonstrates how to perform search text using regular expression.
>   
>  // Open document
>  Document doc = new Document("D:\Tests\input.pdf");
>  // Create TextFragmentAbsorber object
>  TextFragmentAbsorber absorber = new TextFragmentAbsorber();
>  // make the absorber to search all words starting 'h' and ending 'o' using regular expression.
>  absorber.setPhrase ( "h\w*?o");
>  absorber.setTextSearchOptions ( new TextSearchOptions(true));
>  // we should find "hello" word and replace it with "Hi"
>  doc.getPages().get(1).accept(absorber);
>  absorber.getTextFragments().get_Item(1).setText ( "Hi"); 
>  // Save document
>  doc.save("D:\Tests\output.pdf");
> ```

**Returns:**
[TextSearchOptions](../../com.aspose.pdf/textsearchoptions)
### setTextSearchOptions(TextSearchOptions value) {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
```
public void setTextSearchOptions(TextSearchOptions value)
```


Sets search options. The options enable search using regular expressions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextSearchOptions](../../com.aspose.pdf/textsearchoptions) |  |

### getTextEditOptions() {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```


Gets text edit options. The options define special behavior when requested symbol cannot be written with font.

**Returns:**
[TextEditOptions](../../com.aspose.pdf/texteditoptions)
### setTextEditOptions(TextEditOptions value) {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
```
public void setTextEditOptions(TextEditOptions value)
```


Sets text edit options. The options define special behavior when requested symbol cannot be written with font.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextEditOptions](../../com.aspose.pdf/texteditoptions) |  |

### visit(Page page) {#visit-com.aspose.pdf.Page-}
```
public void visit(Page page)
```


Performs search on the specified page.

--------------------

> ```
> The example demonstrates how to find text on the first PDF document page and replace the text.
>   
>  // Open document
>  Document doc = new Document("D:\Tests\input.pdf");
>  // Find font that will be used to change document text font
>  Font font = FontRepository.FindFont("Arial");
>  // Create TextFragmentAbsorber object to find all "hello world" text occurrences
>  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
>  // Accept the absorber for first page
>  absorber.visit(doc.getPages().get(1));
>  // Change text of all search occurrences
>  for (TextFragment textFragment : absorber.getTextFragments())
>  {
>      textFragment.setText ( "hi world");
>  }
>  // Save document
>  doc.save("D:\Tests\output.pdf");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) |  |

### visit(IDocument pdf) {#visit-com.aspose.pdf.IDocument-}
```
public void visit(IDocument pdf)
```


Performs search on the specified document.

--------------------

> ```
> The example demonstrates how to find text on PDF document and replace text of all search occurrences.
>   
>  // Open document
>  Document doc = new Document("D:\Tests\input.pdf");
>  // Find font that will be used to change document text font
>  Font font = FontRepository.FindFont("Arial");
>  // Create TextFragmentAbsorber object to find all "hello world" text occurrences
>  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
>  // Accept the absorber for first page
>  absorber.visit(doc);
>  // Change text of the first text occurrence
>  absorber.getTextFragments().get_Item(1).setText ( "hi world");
>  // Save document
>  doc.save("D:\Tests\output.pdf");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdf | [IDocument](../../com.aspose.pdf/idocument) |  |

### visit(XForm xForm) {#visit-com.aspose.pdf.XForm-}
```
public void visit(XForm xForm)
```


Performs search on the specified form object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xForm | [XForm](../../com.aspose.pdf/xform) |  |

### getExtractionOptions() {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```


Gets or sets text extraction options.

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

### getTextReplaceOptions() {#getTextReplaceOptions--}
```
public TextReplaceOptions getTextReplaceOptions()
```


Gets text replace options. The options define behavior when text fragment is replaced to more short.

**Returns:**
[TextReplaceOptions](../../com.aspose.pdf/textreplaceoptions) - TextReplaceOptions value
### setTextReplaceOptions(TextReplaceOptions value) {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
```
public void setTextReplaceOptions(TextReplaceOptions value)
```


Sets text replace options. The options define behavior when text fragment is replaced to more short.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextReplaceOptions](../../com.aspose.pdf/textreplaceoptions) | TextReplaceOptions value |

