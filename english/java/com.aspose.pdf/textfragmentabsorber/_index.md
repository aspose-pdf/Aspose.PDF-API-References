---
title: TextFragmentAbsorber
second_title: Aspose.PDF for Java API Reference
description: Represents an absorber object of text fragments.
type: docs
weight: 373
url: /java/com.aspose.pdf/textfragmentabsorber/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.TextAbsorber](../../com.aspose.pdf/textabsorber)
```
public final class TextFragmentAbsorber extends TextAbsorber
```

Represents an absorber object of text fragments. Performs text search and provides access to search results via  TextFragmentAbsorber.TextFragments  collection.

--------------------

```
The example demonstrates how to find text on the first PDF document page and replace the text and it's font.

 // Open document
 Document doc = new Document("D:\\Tests\\input.pdf");
 // Find font that will be used to change document text font
 com.aspose.pdf.Font font = FontRepository.findFont("Arial");
 // Create TextFragmentAbsorber object to find all "hello world" text occurrences
 TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
 // Accept the absorber for first page
 doc.getPages().get(1).accept(absorber);
 // Change text and font of the first text occurrence
 absorber.getTextFragments().get_Item(1).setText ( "hi world");
 absorber.getTextFragments().get_Item(1).getTextState().setFont ( font);
 // Save document
 doc.save("D:\\Tests\\output.pdf");
```

--------------------

The  TextFragmentAbsorber  object is basically used in text search scenario. When the search is completed the occurrences are represented with  TextFragment  objects that the  TextFragmentAbsorber.TextFragments  collection contains. The  TextFragment  object provides access to the search occurrence text, text properties, and allows to edit text and change the text state (font, font size, color etc).
## Constructors

| Constructor | Description |
| --- | --- |
| [TextFragmentAbsorber()](#TextFragmentAbsorber--) | Initializes a new instance of the  TextFragmentAbsorber  that performs search of all text segments of the document or page. |
| [TextFragmentAbsorber(TextEditOptions textEditOptions)](#TextFragmentAbsorber-com.aspose.pdf.TextEditOptions-) | Initializes a new instance of the  TextFragmentAbsorber  with text edit options, that performs search of all text segments of the document or page. |
| [TextFragmentAbsorber(String phrase)](#TextFragmentAbsorber-java.lang.String-) | Initializes a new instance of the  TextFragmentAbsorber  class for the specified text phrase. |
| [TextFragmentAbsorber(Pattern regex)](#TextFragmentAbsorber-java.util.regex.Pattern-) | Initializes a new instance of the [TextFragmentAbsorber](../../com.aspose.pdf/textfragmentabsorber) class for the specified System.Text.RegularExpressions.Regex class object. |
| [TextFragmentAbsorber(String phrase, TextSearchOptions textSearchOptions)](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-) | Initializes a new instance of the  TextFragmentAbsorber  class for the specified text phrase and text search options. |
| [TextFragmentAbsorber(Pattern regex, TextSearchOptions textSearchOptions)](#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextSearchOptions-) | Initializes a new instance of the [TextFragmentAbsorber](../../com.aspose.pdf/textfragmentabsorber) class for the specified text phrase and text search options. |
| [TextFragmentAbsorber(String phrase, TextSearchOptions textSearchOptions, TextEditOptions textEditOptions)](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-com.aspose.pdf.TextEditOptions-) | Initializes a new instance of the  TextFragmentAbsorber  class for the specified text phrase, text search options and text edit options. |
| [TextFragmentAbsorber(Pattern regex, TextEditOptions textEditOptions)](#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextEditOptions-) | Initializes a new instance of the [TextFragmentAbsorber](../../com.aspose.pdf/textfragmentabsorber) class for the specified text phrase and text edit options. |
| [TextFragmentAbsorber(String phrase, TextEditOptions textEditOptions)](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextEditOptions-) | Initializes a new instance of the  TextFragmentAbsorber  class for the specified text phrase and text edit options. |
## Methods

| Method | Description |
| --- | --- |
| [applyForAllFragments(Font font)](#applyForAllFragments-com.aspose.pdf.Font-) | Applies font for all text fragments that were absorbed. |
| [applyForAllFragments(Font font, float fontSize)](#applyForAllFragments-com.aspose.pdf.Font-float-) | Applies font and size for all text fragments that were absorbed. |
| [applyForAllFragments(float fontSize)](#applyForAllFragments-float-) | Applies font size for all text fragments that were absorbed. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getErrors()](#getErrors--) | List of  TextExtractionError  objects. |
| [getExtractionOptions()](#getExtractionOptions--) | Gets text extraction options. |
| [getPhrase()](#getPhrase--) | Gets phrase that the  TextFragmentAbsorber  searches on the PDF document or page. |
| [getText()](#getText--) | Gets extracted text that the  TextAbsorber  extracts on the PDF document or page. |
| [getTextEditOptions()](#getTextEditOptions--) | Gets text edit options. |
| [getTextFragments()](#getTextFragments--) | Gets collection of search occurrences that are presented with  TextFragment  objects. |
| [getTextReplaceOptions()](#getTextReplaceOptions--) | Gets text replace options. |
| [getTextSearchOptions()](#getTextSearchOptions--) | Gets search options. |
| [hasErrors()](#hasErrors--) | Value indicates whether errors were found during text extraction. |
| [hasErrors_Fragment()](#hasErrors-Fragment--) | Value indicates whether errors were found during text extraction. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeAllText(Document document)](#removeAllText-com.aspose.pdf.Document-) | Removes all text from the document. |
| [removeAllText(Page page)](#removeAllText-com.aspose.pdf.Page-) | Removes all text from the specified page. |
| [removeAllText(Page page, Rectangle rect)](#removeAllText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Removes text inside the specified rectangle from the specified page. |
| [reset()](#reset--) | Clears TextFragments collection of this  TextFragmentAbsorber  object. |
| [setExtractionOptions(TextExtractionOptions value)](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | Sets text extraction options. |
| [setPhrase(String value)](#setPhrase-java.lang.String-) | Sets phrase that the  TextFragmentAbsorber  searches on the PDF document or page. |
| [setTextEditOptions(TextEditOptions value)](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Sets text edit options. |
| [setTextFragments(TextFragmentCollection value)](#setTextFragments-com.aspose.pdf.TextFragmentCollection-) | Sets collection of search occurrences that are presented with  TextFragment  objects. |
| [setTextReplaceOptions(TextReplaceOptions value)](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | Sets text replace options. |
| [setTextSearchOptions(TextSearchOptions value)](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Sets search options. |
| [toString()](#toString--) |  |
| [visit(IDocument pdf)](#visit-com.aspose.pdf.IDocument-) | Performs search on the specified document. |
| [visit(Page page)](#visit-com.aspose.pdf.Page-) | Performs search on the specified page. |
| [visit(XForm xForm)](#visit-com.aspose.pdf.XForm-) | Performs search on the specified form object. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextFragmentAbsorber() {#TextFragmentAbsorber--}
```
public TextFragmentAbsorber()
```


Initializes a new instance of the  TextFragmentAbsorber  that performs search of all text segments of the document or page.

--------------------

```
The example demonstrates how to find text on the first PDF document page and replace the text.

 // Open document
 Document doc = new Document("D:\\Tests\\input.pdf");
 // Find font that will be used to change document text font
 Font font = FontRepository.findFont("Arial");
 // Create TextFragmentAbsorber object
 TextFragmentAbsorber absorber = new TextFragmentAbsorber();
 // Make the absorber to search all "hello world" text occurrences
 absorber.setPhrase ( "hello world");
 // Accept the absorber for first page
 doc.getPages().get(1).accept(absorber);
 // Change text of the first text occurrence
 absorber.getTextFragments().get_Item(1).setText ( "hi world");
 // Save document
 doc.save("D:\\Tests\\output.pdf");
```

--------------------

Performs text search and provides access to search results via  TextFragmentAbsorber.TextFragments  collection.

### TextFragmentAbsorber(TextEditOptions textEditOptions) {#TextFragmentAbsorber-com.aspose.pdf.TextEditOptions-}
```
public TextFragmentAbsorber(TextEditOptions textEditOptions)
```


Initializes a new instance of the  TextFragmentAbsorber  with text edit options, that performs search of all text segments of the document or page.

--------------------

```
The example demonstrates how to find all text fragments on the first PDF document page and replace font for them.

  // Open document
  Document doc = new Document("D:\\Tests\\input.pdf");

  // Create TextFragmentAbsorber object
  TextFragmentAbsorber absorber = new TextFragmentAbsorber(new TextEditOptions(TextEditOptions.FontReplace
  .RemoveUnusedFonts));

  // Accept the absorber for first page
  doc.getPages()get(1).accept(absorber);

  // Find Courier font
  Font font = FontRepository.findFont("Courier");
  // Set the font for all the text fragments
  for (TextFragment textFragment : ```
(Iterable)
```absorber.TextFragments)
  {
      textFragment.getTextState().setFont ( font);
  }
  // Save document
  doc.save("D:\\Tests\\output.pdf");
```

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

```
The example demonstrates how to find text on the first PDF document page and replace the text and it's font.

 // Open document
 Document doc = new Document("D:\\Tests\\input.pdf");
 // Find font that will be used to change document text font
 com.aspose.pdf.Font font = FontRepository.findFont("Arial");
 // Create TextFragmentAbsorber object to find all "hello world" text occurrences
 TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
 // Accept the absorber for first page
 doc.getPages().get_Item(1).accept(absorber);
 // Change text and font of the first text occurrence
 absorber.getTextFragments().get_Item(1).setText ( "hi world");
 absorber.getTextFragments().get_Item(1).getTextState().setFont ( font);
 // Save document
 doc.save("D:\\Tests\\output.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| phrase | java.lang.String | Phrase that the  TextFragmentAbsorber  searches

--------------------

Performs text search of the specified phrase and provides access to search results via  TextFragmentAbsorber.TextFragments  collection. |

### TextFragmentAbsorber(Pattern regex) {#TextFragmentAbsorber-java.util.regex.Pattern-}
```
public TextFragmentAbsorber(Pattern regex)
```


Initializes a new instance of the [TextFragmentAbsorber](../../com.aspose.pdf/textfragmentabsorber) class for the specified System.Text.RegularExpressions.Regex class object.

--------------------

The example demonstrates how to find text on the first PDF document page and replace the text and it's font.

```
// Open document
  Document doc = new Document("input.pdf");
  // Find font that will be used to change document text font
  Font font = FontRepository.findFont("Arial");
  // Create TextAbsorber object to find all instances of the input regex
  TextFragmentAbsorber absorber = new TextFragmentAbsorber(new Regex("h\\w*?o"));
  // Accept the absorber for first page
  doc.getPages().get_item(1).accept(absorber);
  // we should find "hello" word and replace it with "Hi"
  absorber.getTextFragments().get_item(1).setText("Hi");
  // Save document
  doc.save("output.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | System.Text.RegularExpressions.Regex class object that the [TextFragmentAbsorber](../../com.aspose.pdf/textfragmentabsorber) searches

--------------------

Performs text search of the specified phrase and provides access to search results via  TextFragmentAbsorber.TextFragments (\#getTextFragments.getTextFragments/\#setTextFragments(TextFragmentCollection).setTextFragments(TextFragmentCollection)) collection. |

### TextFragmentAbsorber(String phrase, TextSearchOptions textSearchOptions) {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-}
```
public TextFragmentAbsorber(String phrase, TextSearchOptions textSearchOptions)
```


Initializes a new instance of the  TextFragmentAbsorber  class for the specified text phrase and text search options.

--------------------

```
The example demonstrates how to find text with regular expression on the first PDF document page and replace
 the text.

 // Open document
 Document doc = new Document("D:\\Tests\\input.pdf");
 // Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular
 expression.
 TextFragmentAbsorber absorber = new TextFragmentAbsorber("h\\w*?o", new TextSearchOptions(true));
 // we should find "hello" word and replace it with "Hi"
 doc.getPages().get_Item(1).accept(absorber);
 absorber.getTextFragments().get_Item(1).setText ( "Hi");

 // Save document
 doc.save("D:\\Tests\\output.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| phrase | java.lang.String | Phrase that the  TextFragmentAbsorber  searches |
| textSearchOptions | [TextSearchOptions](../../com.aspose.pdf/textsearchoptions) | Text search options (Allows to turn on some search features. For example, search with regular expression)

--------------------

Performs text search of the specified phrase and provides access to search results via  TextFragmentAbsorber.TextFragments  collection. |

### TextFragmentAbsorber(Pattern regex, TextSearchOptions textSearchOptions) {#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextSearchOptions-}
```
public TextFragmentAbsorber(Pattern regex, TextSearchOptions textSearchOptions)
```


Initializes a new instance of the [TextFragmentAbsorber](../../com.aspose.pdf/textfragmentabsorber) class for the specified text phrase and text search options.

--------------------

The example demonstrates how to find text with regular expression on the first PDF document page and replace the text.

```
// Open document
  Document doc = new Document("input.pdf");
  // Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
  TextFragmentAbsorber absorber = new TextFragmentAbsorber(new Regex("h\\w*?o"), new TextSearchOptions(true));
  // we should find "hello" word and replace it with "Hi"
  doc.getPages().get_Item(1).accept(absorber);
  absorber.getTextFragments.get_Item(1).setText("Hi");
  // Save document
  doc.save("output.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Regex class object that the [TextFragmentAbsorber](../../com.aspose.pdf/textfragmentabsorber) searches |
| textSearchOptions | [TextSearchOptions](../../com.aspose.pdf/textsearchoptions) | Text search options (Allows to turn on some search features.)

--------------------

Performs text search of the specified phrase and provides access to search results via  TextFragmentAbsorber.TextFragments (\#getTextFragments.getTextFragments/\#setTextFragments(TextFragmentCollection).setTextFragments(TextFragmentCollection)) collection. |

### TextFragmentAbsorber(String phrase, TextSearchOptions textSearchOptions, TextEditOptions textEditOptions) {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-com.aspose.pdf.TextEditOptions-}
```
public TextFragmentAbsorber(String phrase, TextSearchOptions textSearchOptions, TextEditOptions textEditOptions)
```


Initializes a new instance of the  TextFragmentAbsorber  class for the specified text phrase, text search options and text edit options. The text edit options are not supported yet.

--------------------

```
The example demonstrates how to find text with regular expression on the first PDF document page and replace
 the text.

 // Open document
 Document doc = new Document("D:\\Tests\\input.pdf");
 // Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular
 expression.
 TextFragmentAbsorber absorber = new TextFragmentAbsorber("h\w*?o", new TextSearchOptions(true));
 // we should find "hello" word and replace it with "Hi"
 doc.getPages().get_item(1).accept(absorber);
 absorber.getTextFragments().get_Item(1).setText ( "Hi");
 // Save document
 doc.save("D:\\Tests\\output.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| phrase | java.lang.String | Phrase that the  TextFragmentAbsorber  searches |
| textSearchOptions | [TextSearchOptions](../../com.aspose.pdf/textsearchoptions) | Text search options (Allows to turn on some search features. For example, search with regular expression) |
| textEditOptions | [TextEditOptions](../../com.aspose.pdf/texteditoptions) | Text edit options (Allows to turn on some edit features. For example, define special behavior when requested symbol cannot be written with font). The parameter is not supported yet.

--------------------

Performs text search of the specified phrase and provides access to search results via  TextFragmentAbsorber.TextFragments  collection. |

### TextFragmentAbsorber(Pattern regex, TextEditOptions textEditOptions) {#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextEditOptions-}
```
public TextFragmentAbsorber(Pattern regex, TextEditOptions textEditOptions)
```


Initializes a new instance of the [TextFragmentAbsorber](../../com.aspose.pdf/textfragmentabsorber) class for the specified text phrase and text edit options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | System.Text.RegularExpressions.Regex class object that the [TextFragmentAbsorber](../../com.aspose.pdf/textfragmentabsorber) searches |
| textEditOptions | [TextEditOptions](../../com.aspose.pdf/texteditoptions) | Text edit options (Allows to turn on some edit features).

--------------------

Performs text search of the specified phrase and provides access to search results via  TextFragmentAbsorber.TextFragments (\#getTextFragments.getTextFragments/\#setTextFragments(TextFragmentCollection).setTextFragments(TextFragmentCollection)) collection. |

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

### applyForAllFragments(Font font) {#applyForAllFragments-com.aspose.pdf.Font-}
```
public void applyForAllFragments(Font font)
```


Applies font for all text fragments that were absorbed. It works faster than looping through the fragments if all fragments on the page(s) were absorbed. Otherwise it works similar with looping.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| font | [Font](../../com.aspose.pdf/font) |  Font of the text. |

### applyForAllFragments(Font font, float fontSize) {#applyForAllFragments-com.aspose.pdf.Font-float-}
```
public void applyForAllFragments(Font font, float fontSize)
```


Applies font and size for all text fragments that were absorbed. It works faster than looping through the fragments if all fragments on the page(s) were absorbed. Otherwise it works similar with looping.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| font | [Font](../../com.aspose.pdf/font) |  Font of the text. |
| fontSize | float | Font size of the text. |

### applyForAllFragments(float fontSize) {#applyForAllFragments-float-}
```
public void applyForAllFragments(float fontSize)
```


Applies font size for all text fragments that were absorbed. It works faster than looping through the fragments if all fragments on the page(s) were absorbed. Otherwise it works similar with looping.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontSize | float | Font size of the text. |

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

**Returns:**
[TextExtractionOptions](../../com.aspose.pdf/textextractionoptions) - TextExtractionOptions object
### getPhrase() {#getPhrase--}
```
public String getPhrase()
```


Gets phrase that the  TextFragmentAbsorber  searches on the PDF document or page.

**Returns:**
java.lang.String - String value

--------------------

```
The example demonstrates how to perform search text several times and perform text replacements.

 // Open document
 Document doc = new Document("D:\\Tests\\input.pdf");
 // Create TextFragmentAbsorber object to find all "hello" text occurrences
 TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello");
 doc.getPages().get(1).accept(absorber);
 absorber.getTextFragments().get_Item(1).setText ( "Hi");
 // search another word and replace it
 absorber.setPhrase ( "world");
 doc.getPages().get(1).accept(absorber);
 absorber.getTextFragments().get_Item(1).setText ( "John");
 // Save document
 doc.save("D:\\Tests\\output.pdf");
```
### getText() {#getText--}
```
public String getText()
```


Gets extracted text that the  TextAbsorber  extracts on the PDF document or page.

**Returns:**
java.lang.String
### getTextEditOptions() {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```


Gets text edit options. The options define special behavior when requested symbol cannot be written with font.

**Returns:**
[TextEditOptions](../../com.aspose.pdf/texteditoptions) - TextEditOptions object
### getTextFragments() {#getTextFragments--}
```
public TextFragmentCollection getTextFragments()
```


Gets collection of search occurrences that are presented with  TextFragment  objects.

**Returns:**
[TextFragmentCollection](../../com.aspose.pdf/textfragmentcollection) - TextFragmentCollection object

--------------------

```
The example demonstrates how to find text on the first PDF document page and replace all search occurrences
 with new text.

 // Open document
 Document doc = new Document("D:\\Tests\\input.pdf");
 // Find font that will be used to change document text font
 Font font = FontRepository.findFont("Arial");
 // Create TextFragmentAbsorber object to find all "hello world" text occurrences
 TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
 // Accept the absorber for first page
 doc.getPages().get(1).accept(absorber);
 // Change text of all search occurrences
 for (TextFragment textFragment : ```
(Iterable)
```absorber.getTextFragments())
 {
     textFragment.setText ( "hi world");
 }
 // Save document
 doc.save("D:\\Tests\\output.pdf");
```
### getTextReplaceOptions() {#getTextReplaceOptions--}
```
public TextReplaceOptions getTextReplaceOptions()
```


Gets text replace options. The options define behavior when fragment text is replaced to more short/long.

**Returns:**
[TextReplaceOptions](../../com.aspose.pdf/textreplaceoptions) - TextReplaceOptions value
### getTextSearchOptions() {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```


Gets search options. The options enable search using regular expressions.

**Returns:**
[TextSearchOptions](../../com.aspose.pdf/textsearchoptions) - TextSearchOptions object

--------------------

```
The example demonstrates how to perform search text using regular expression.

 // Open document
 Document doc = new Document("D:\\Tests\\input.pdf");
 // Create TextFragmentAbsorber object
 TextFragmentAbsorber absorber = new TextFragmentAbsorber();
 // make the absorber to search all words starting 'h' and ending 'o' using regular expression.
 absorber.setPhrase ( "h\w*?o");
 absorber.setTextSearchOptions ( new TextSearchOptions(true));
 // we should find "hello" word and replace it with "Hi"
 doc.getPages().get(1).accept(absorber);
 absorber.getTextFragments().get_Item(1).setText ( "Hi");
 // Save document
 doc.save("D:\\Tests\\output.pdf");
```
### hasErrors() {#hasErrors--}
```
public boolean hasErrors()
```


Value indicates whether errors were found during text extraction. Searching for errors will performed only if TextSearchOptions.LogTextExtractionErrors = true; And it may decrease performance.

**Returns:**
boolean - boolean value
### hasErrors_Fragment() {#hasErrors-Fragment--}
```
public boolean hasErrors_Fragment()
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




### removeAllText(Document document) {#removeAllText-com.aspose.pdf.Document-}
```
public void removeAllText(Document document)
```


Removes all text from the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [Document](../../com.aspose.pdf/document) | PDF document object. |

### removeAllText(Page page) {#removeAllText-com.aspose.pdf.Page-}
```
public void removeAllText(Page page)
```


Removes all text from the specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | PDF document page object. |

### removeAllText(Page page, Rectangle rect) {#removeAllText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public final void removeAllText(Page page, Rectangle rect)
```


Removes text inside the specified rectangle from the specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | PDF document page object. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | [Rectangle](../../com.aspose.pdf/rectangle) to remove text inside. |

### reset() {#reset--}
```
public void reset()
```


Clears TextFragments collection of this  TextFragmentAbsorber  object.

### setExtractionOptions(TextExtractionOptions value) {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
```
public void setExtractionOptions(TextExtractionOptions value)
```


Sets text extraction options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextExtractionOptions](../../com.aspose.pdf/textextractionoptions) | TextExtractionOptions object |

### setPhrase(String value) {#setPhrase-java.lang.String-}
```
public void setPhrase(String value)
```


Sets phrase that the  TextFragmentAbsorber  searches on the PDF document or page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value

--------------------

```
The example demonstrates how to perform search text several times and perform text replacements.

              // Open document
              Document doc = new Document("D:\\Tests\\input.pdf");
              // Create TextFragmentAbsorber object to find all "hello" text occurrences
              TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello");
              doc.getPages().get(1).accept(absorber);
              absorber.getTextFragments().get_Item(1).setText ( "Hi");
              // search another word and replace it
              absorber.setPhrase ( "world");
              doc.getPages().get(1).accept(absorber);
              absorber.getTextFragments().get_Item(1).setText ( "John");
              // Save document
              doc.save("D:\\Tests\\output.pdf");
``` |

### setTextEditOptions(TextEditOptions value) {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
```
public void setTextEditOptions(TextEditOptions value)
```


Sets text edit options. The options define special behavior when requested symbol cannot be written with font.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextEditOptions](../../com.aspose.pdf/texteditoptions) | TextEditOptions object |

### setTextFragments(TextFragmentCollection value) {#setTextFragments-com.aspose.pdf.TextFragmentCollection-}
```
public void setTextFragments(TextFragmentCollection value)
```


Sets collection of search occurrences that are presented with  TextFragment  objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextFragmentCollection](../../com.aspose.pdf/textfragmentcollection) | TextFragmentCollection object

--------------------

```
The example demonstrates how to find text on the first PDF document page and replace all search
              occurrences with new text.

              // Open document
              Document doc = new Document("D:\\Tests\\input.pdf");
              // Find font that will be used to change document text font
              Font font = FontRepository.findFont("Arial");
              // Create TextFragmentAbsorber object to find all "hello world" text occurrences
              TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
              // Accept the absorber for first page
              doc.getPages().get(1).accept(absorber);
              // Change text of all search occurrences
              for (TextFragment textFragment : ```
(Iterable)
```absorber.getTextFragments())
              {
                  textFragment.setText ( "hi world");
              }
              // Save document
              doc.save("D:\\Tests\\output.pdf");
``` |

### setTextReplaceOptions(TextReplaceOptions value) {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
```
public void setTextReplaceOptions(TextReplaceOptions value)
```


Sets text replace options. The options define behavior when fragment text is replaced to more short/long.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextReplaceOptions](../../com.aspose.pdf/textreplaceoptions) | TextReplaceOptions value |

### setTextSearchOptions(TextSearchOptions value) {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
```
public void setTextSearchOptions(TextSearchOptions value)
```


Sets search options. The options enable search using regular expressions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextSearchOptions](../../com.aspose.pdf/textsearchoptions) | TextSearchOptions object

--------------------

```
The example demonstrates how to perform search text using regular expression.

              // Open document
              Document doc = new Document("D:\\Tests\\input.pdf");
              // Create TextFragmentAbsorber object
              TextFragmentAbsorber absorber = new TextFragmentAbsorber();
              // make the absorber to search all words starting 'h' and ending 'o' using regular expression.
              absorber.setPhrase ( "h\w*?o");
              absorber.setTextSearchOptions ( new TextSearchOptions(true));
              // we should find "hello" word and replace it with "Hi"
              doc.getPages().get(1).accept(absorber);
              absorber.getTextFragments().get_Item(1).setText ( "Hi");
              // Save document
              doc.save("D:\\Tests\\output.pdf");
``` |

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


Performs search on the specified document.

--------------------

```
The example demonstrates how to find text on PDF document and replace text of all search occurrences.

 // Open document
 Document doc = new Document("D:\\Tests\\input.pdf");
 // Find font that will be used to change document text font
 Font font = FontRepository.findFont("Arial");
 // Create TextFragmentAbsorber object to find all "hello world" text occurrences
 TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
 // Accept the absorber for first page
 absorber.visit(doc);
 // Change text of the first text occurrence
 absorber.getTextFragments().get_Item(1).setText ( "hi world");
 // Save document
 doc.save("D:\\Tests\\output.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdf | [IDocument](../../com.aspose.pdf/idocument) | PDF document object. |

### visit(Page page) {#visit-com.aspose.pdf.Page-}
```
public void visit(Page page)
```


Performs search on the specified page.

--------------------

```
The example demonstrates how to find text on the first PDF document page and replace the text.

 // Open document
 Document doc = new Document("D:\\Tests\\input.pdf");
 // Find font that will be used to change document text font
 Font font = FontRepository.findFont("Arial");
 // Create TextFragmentAbsorber object to find all "hello world" text occurrences
 TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
 // Accept the absorber for first page
 absorber.visit(doc.getPages().get(1));
 // Change text of all search occurrences
 for (TextFragment textFragment : ```
(Iterable)
```absorber.getTextFragments())
 {
     textFragment.setText ( "hi world");
 }
 // Save document
 doc.save("D:\\Tests\\output.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | PDF document page object. |

### visit(XForm xForm) {#visit-com.aspose.pdf.XForm-}
```
public void visit(XForm xForm)
```


Performs search on the specified form object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xForm | [XForm](../../com.aspose.pdf/xform) | Pdf form object. |

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

