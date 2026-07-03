---
title: TextFragmentAbsorber
linktitle: TextFragmentAbsorber
second_title: Aspose.PDF for Java API Reference
description: <p> Represents an absorber object of text fragments. Performs text search and provides access to search results via {@code TextFragmentAbsorber.TextFragments} collection. </p>.
type: docs
weight: 5120
url: /java/com.aspose.pdf/textfragmentabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextAbsorber com.aspose.pdf.TextFragmentAbsorber, com.aspose.pdf.TextAbsorber, com.aspose.pdf.TextFragmentAbsorber

```
public final class TextFragmentAbsorber extends TextAbsorber
```

<p> Represents an absorber object of text fragments. Performs text search and provides access to search results via {@code TextFragmentAbsorber.TextFragments} collection. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text and it's font. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font com.aspose.pdf.Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text and font of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> The {@code TextFragmentAbsorber} object is basically used in text search scenario. When the search is completed the occurrences are represented with {@code TextFragment} objects that the {@code TextFragmentAbsorber.TextFragments} collection contains. The {@code TextFragment} object provides access to the search occurrence text, text properties, and allows to edit text and change the text state (font, font size, color etc). </p>

## Constructors

| Constructor | Description |
| --- | --- |
| [TextFragmentAbsorber](#TextFragmentAbsorber--) | <p> Initializes a new instance of the {@code TextFragmentAbsorber} that performs search of all text segments of the document or page. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Performs text search and provides access to search results via {@code TextFragmentAbsorber.TextFragments} collection. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern-) | <p> Initializes a new instance of the {@code TextFragmentAbsorber} that performs search of all text segments of the document or page. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Performs text search and provides access to search results via {@code TextFragmentAbsorber.TextFragments} collection. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern:A-com.aspose.pdf.TextSearchOptions-) | <p> Initializes a new instance of the {@code TextFragmentAbsorber} that performs search of all text segments of the document or page. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Performs text search and provides access to search results via {@code TextFragmentAbsorber.TextFragments} collection. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextEditOptions-) | <p> Initializes a new instance of the {@code TextFragmentAbsorber} that performs search of all text segments of the document or page. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Performs text search and provides access to search results via {@code TextFragmentAbsorber.TextFragments} collection. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextSearchOptions-) | <p> Initializes a new instance of the {@code TextFragmentAbsorber} that performs search of all text segments of the document or page. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Performs text search and provides access to search results via {@code TextFragmentAbsorber.TextFragments} collection. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-) | <p> Initializes a new instance of the {@code TextFragmentAbsorber} that performs search of all text segments of the document or page. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Performs text search and provides access to search results via {@code TextFragmentAbsorber.TextFragments} collection. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextEditOptions-) | <p> Initializes a new instance of the {@code TextFragmentAbsorber} that performs search of all text segments of the document or page. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Performs text search and provides access to search results via {@code TextFragmentAbsorber.TextFragments} collection. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-) | <p> Initializes a new instance of the {@code TextFragmentAbsorber} that performs search of all text segments of the document or page. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Performs text search and provides access to search results via {@code TextFragmentAbsorber.TextFragments} collection. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-com.aspose.pdf.TextEditOptions-) | <p> Initializes a new instance of the {@code TextFragmentAbsorber} that performs search of all text segments of the document or page. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Performs text search and provides access to search results via {@code TextFragmentAbsorber.TextFragments} collection. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-com.aspose.pdf.TextEditOptions-) | <p> Initializes a new instance of the {@code TextFragmentAbsorber} that performs search of all text segments of the document or page. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Performs text search and provides access to search results via {@code TextFragmentAbsorber.TextFragments} collection. </p> |

## Methods

| Method | Description |
| --- | --- |
| [applyForAllFragments](#applyForAllFragments-float-) | Applies font size for all text fragments that were absorbed. It works faster than looping through the fragments if all fragments on the page(s) were absorbed. Otherwise it works similar with looping. |
| [applyForAllFragments](#applyForAllFragments-com.aspose.pdf.Font-) | Applies font for all text fragments that were absorbed. It works faster than looping through the fragments if all fragments on the page(s) were absorbed. Otherwise it works similar with looping. |
| [applyForAllFragments](#applyForAllFragments-com.aspose.pdf.Font-float-) | Applies font and size for all text fragments that were absorbed. It works faster than looping through the fragments if all fragments on the page(s) were absorbed. Otherwise it works similar with looping. |
| [getErrors](#getErrors--) | List of {@code TextExtractionError} objects. It contain information about errors were found during text extraction. Searching for errors will performed only if TextSearchOptions.LogTextExtractionErrors = true; And it may decrease performance. |
| [getExtractionOptions](#getExtractionOptions--) | Gets text extraction options. |
| [getPhrase](#getPhrase--) | <p> Gets phrase that the {@code TextFragmentAbsorber} searches on the PDF document or page. </p> |
| [getRegexResults](#getRegexResults--) | Gets dictionary of search occurrences that are presented with System.Text.RegularExpressions.Regex class as key and {@link TextFragment} as value. The example demonstrates how to find text with array of regular expressions on the first PDF document page. // Open document Document doc = new Document("input.pdf"); Regex regexes = new Regex[] { new Regex( RegexOptions.IgnoreCase), new Regex( RegexOptions.IgnoreCase), }; // Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression. TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true)); doc.getPages().get_Item(1).accept(absorber); // Get results Dictionary results = absorber.getRegexResults(); |
| [getRegexResultsInternal](#getRegexResultsInternal--) |  |
| [getText](#getText--) | Gets extracted text that the {@code TextAbsorber} extracts on the PDF document or page. |
| [getTextEditOptions](#getTextEditOptions--) | Gets text edit options. The options define special behavior when requested symbol cannot be written with font. |
| [getTextFragments](#getTextFragments--) | <p> Gets collection of search occurrences that are presented with {@code TextFragment} objects. </p> |
| [getTextReplaceOptions](#getTextReplaceOptions--) | Gets text replace options. The options define behavior when fragment text is replaced to more short/long. |
| [getTextSearchOptions](#getTextSearchOptions--) | <p> Gets search options. The options enable search using regular expressions. </p> |
| [hasErrors_Fragment](#hasErrors_Fragment--) | Value indicates whether errors were found during text extraction. Searching for errors will performed only if TextSearchOptions.LogTextExtractionErrors = true; And it may decrease performance. |
| [removeAllText](#removeAllText-com.aspose.pdf.Document-) | Removes all text from the document. |
| [removeAllText](#removeAllText-com.aspose.pdf.Page-) | Removes all text from the specified page. |
| [removeAllText](#removeAllText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Removes text inside the specified rectangle from the specified page. |
| [reset](#reset--) | Clears TextFragments collection of this {@code TextFragmentAbsorber} object. |
| [setExtractionOptions](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | Sets text extraction options. |
| [setPhrase](#setPhrase-java.lang.String-) | <p> Sets phrase that the {@code TextFragmentAbsorber} searches on the PDF document or page. </p> |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Sets text edit options. The options define special behavior when requested symbol cannot be written with font. |
| [setTextFragments](#setTextFragments-com.aspose.pdf.TextFragmentCollection-) | <p> Sets collection of search occurrences that are presented with {@code TextFragment} objects. </p> |
| [setTextReplaceOptions](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | Sets text replace options. The options define behavior when fragment text is replaced to more short/long. |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | <p> Sets search options. The options enable search using regular expressions. </p> |
| [visit](#visit-com.aspose.pdf.IDocument-) | <p> Performs search on the specified document. </p> <hr> <pre> The example demonstrates how to find text on PDF document and replace text of all search occurrences. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page absorber.visit(doc); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [visit](#visit-com.aspose.pdf.Page-) | <p> Performs search on the specified page. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page absorber.visit(doc.getPages().get(1)); // Change text of all search occurrences for (TextFragment textFragment : {@code (Iterable<TextFragment>)}absorber.getTextFragments()) { textFragment.setText ( "hi world"); } // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [visit](#visit-com.aspose.pdf.XForm-) | Performs search on the specified form object. |

### TextFragmentAbsorber {#TextFragmentAbsorber--}
```
public TextFragmentAbsorber()
```

<p> Initializes a new instance of the {@code TextFragmentAbsorber} that performs search of all text segments of the document or page. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Performs text search and provides access to search results via {@code TextFragmentAbsorber.TextFragments} collection. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern-}
<p> Initializes a new instance of the {@code TextFragmentAbsorber} that performs search of all text segments of the document or page. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Performs text search and provides access to search results via {@code TextFragmentAbsorber.TextFragments} collection. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern:A-com.aspose.pdf.TextSearchOptions-}
<p> Initializes a new instance of the {@code TextFragmentAbsorber} that performs search of all text segments of the document or page. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Performs text search and provides access to search results via {@code TextFragmentAbsorber.TextFragments} collection. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextEditOptions-}
<p> Initializes a new instance of the {@code TextFragmentAbsorber} that performs search of all text segments of the document or page. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Performs text search and provides access to search results via {@code TextFragmentAbsorber.TextFragments} collection. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextSearchOptions-}
<p> Initializes a new instance of the {@code TextFragmentAbsorber} that performs search of all text segments of the document or page. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Performs text search and provides access to search results via {@code TextFragmentAbsorber.TextFragments} collection. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-}
<p> Initializes a new instance of the {@code TextFragmentAbsorber} that performs search of all text segments of the document or page. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Performs text search and provides access to search results via {@code TextFragmentAbsorber.TextFragments} collection. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextEditOptions-}
<p> Initializes a new instance of the {@code TextFragmentAbsorber} that performs search of all text segments of the document or page. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Performs text search and provides access to search results via {@code TextFragmentAbsorber.TextFragments} collection. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-}
<p> Initializes a new instance of the {@code TextFragmentAbsorber} that performs search of all text segments of the document or page. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Performs text search and provides access to search results via {@code TextFragmentAbsorber.TextFragments} collection. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-com.aspose.pdf.TextEditOptions-}
<p> Initializes a new instance of the {@code TextFragmentAbsorber} that performs search of all text segments of the document or page. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Performs text search and provides access to search results via {@code TextFragmentAbsorber.TextFragments} collection. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-com.aspose.pdf.TextEditOptions-}
<p> Initializes a new instance of the {@code TextFragmentAbsorber} that performs search of all text segments of the document or page. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Performs text search and provides access to search results via {@code TextFragmentAbsorber.TextFragments} collection. </p>

### applyForAllFragments {#applyForAllFragments-float-}
```
public void applyForAllFragments(float fontSize)
```

Applies font size for all text fragments that were absorbed. It works faster than looping through the fragments if all fragments on the page(s) were absorbed. Otherwise it works similar with looping.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontSize |  | Font size of the text. |

### applyForAllFragments {#applyForAllFragments-com.aspose.pdf.Font-}
Applies font for all text fragments that were absorbed. It works faster than looping through the fragments if all fragments on the page(s) were absorbed. Otherwise it works similar with looping.

### applyForAllFragments {#applyForAllFragments-com.aspose.pdf.Font-float-}
Applies font and size for all text fragments that were absorbed. It works faster than looping through the fragments if all fragments on the page(s) were absorbed. Otherwise it works similar with looping.

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

Gets text extraction options.

**Returns:**
TextExtractionOptions object

### getPhrase {#getPhrase--}
```
public String getPhrase()
```

<p> Gets phrase that the {@code TextFragmentAbsorber} searches on the PDF document or page. </p>

**Returns:**
String value <hr> <pre> The example demonstrates how to perform search text several times and perform text replacements. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello"); doc.getPages().get(1).accept(absorber); absorber.getTextFragments().get_Item(1).setText ( "Hi"); // search another word and replace it absorber.setPhrase ( "world"); doc.getPages().get(1).accept(absorber); absorber.getTextFragments().get_Item(1).setText ( "John"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### getRegexResults {#getRegexResults--}
```
public final HashMap < Pattern , TextFragmentCollection > getRegexResults()
```

Gets dictionary of search occurrences that are presented with System.Text.RegularExpressions.Regex class as key and {@link TextFragment} as value. The example demonstrates how to find text with array of regular expressions on the first PDF document page. // Open document Document doc = new Document("input.pdf"); Regex regexes = new Regex[] { new Regex( RegexOptions.IgnoreCase), new Regex( RegexOptions.IgnoreCase), }; // Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression. TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true)); doc.getPages().get_Item(1).accept(absorber); // Get results Dictionary results = absorber.getRegexResults();

**Returns:**
Dictionary instance

### getRegexResultsInternal {#getRegexResultsInternal--}
```
public final com.aspose.ms.System.Collections.Generic.Dictionary<com.aspose.ms.System.Text.RegularExpressions.Regex, TextFragmentCollection > getRegexResultsInternal()
```



### getText {#getText--}
```
public String getText()
```

Gets extracted text that the {@code TextAbsorber} extracts on the PDF document or page.

**Returns:**
String value The example demonstrates how to extract text from all pages of the PDF document. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText();

### getTextEditOptions {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```

Gets text edit options. The options define special behavior when requested symbol cannot be written with font.

**Returns:**
TextEditOptions object

### getTextFragments {#getTextFragments--}
```
public TextFragmentCollection getTextFragments()
```

<p> Gets collection of search occurrences that are presented with {@code TextFragment} objects. </p>

**Returns:**
TextFragmentCollection object <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace all search occurrences with new text. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of all search occurrences for (TextFragment textFragment : {@code (Iterable<TextFragment>)}absorber.getTextFragments()) { textFragment.setText ( "hi world"); } // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### getTextReplaceOptions {#getTextReplaceOptions--}
```
public TextReplaceOptions getTextReplaceOptions()
```

Gets text replace options. The options define behavior when fragment text is replaced to more short/long.

**Returns:**
TextReplaceOptions value

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

<p> Gets search options. The options enable search using regular expressions. </p>

**Returns:**
TextSearchOptions object <hr> <pre> The example demonstrates how to perform search text using regular expression. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // make the absorber to search all words starting 'h' and ending 'o' using regular expression. absorber.setPhrase ( "h\w*?o"); absorber.setTextSearchOptions ( new TextSearchOptions(true)); // we should find "hello" word and replace it with "Hi" doc.getPages().get(1).accept(absorber); absorber.getTextFragments().get_Item(1).setText ( "Hi"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### hasErrors_Fragment {#hasErrors_Fragment--}
```
public boolean hasErrors_Fragment()
```

Value indicates whether errors were found during text extraction. Searching for errors will performed only if TextSearchOptions.LogTextExtractionErrors = true; And it may decrease performance.

**Returns:**
boolean value

### removeAllText {#removeAllText-com.aspose.pdf.Document-}
Removes all text from the document.

### removeAllText {#removeAllText-com.aspose.pdf.Page-}
Removes all text from the specified page.

### removeAllText {#removeAllText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Removes text inside the specified rectangle from the specified page.

### reset {#reset--}
```
public void reset()
```

Clears TextFragments collection of this {@code TextFragmentAbsorber} object.

### setExtractionOptions {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
Sets text extraction options.

### setPhrase {#setPhrase-java.lang.String-}
<p> Sets phrase that the {@code TextFragmentAbsorber} searches on the PDF document or page. </p>

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
Sets text edit options. The options define special behavior when requested symbol cannot be written with font.

### setTextFragments {#setTextFragments-com.aspose.pdf.TextFragmentCollection-}
<p> Sets collection of search occurrences that are presented with {@code TextFragment} objects. </p>

### setTextReplaceOptions {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
Sets text replace options. The options define behavior when fragment text is replaced to more short/long.

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
<p> Sets search options. The options enable search using regular expressions. </p>

### visit {#visit-com.aspose.pdf.IDocument-}
<p> Performs search on the specified document. </p> <hr> <pre> The example demonstrates how to find text on PDF document and replace text of all search occurrences. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page absorber.visit(doc); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### visit {#visit-com.aspose.pdf.Page-}
<p> Performs search on the specified page. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page absorber.visit(doc.getPages().get(1)); // Change text of all search occurrences for (TextFragment textFragment : {@code (Iterable<TextFragment>)}absorber.getTextFragments()) { textFragment.setText ( "hi world"); } // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### visit {#visit-com.aspose.pdf.XForm-}
Performs search on the specified form object.
