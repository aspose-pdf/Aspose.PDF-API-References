---
title: ParagraphAbsorber
second_title: Aspose.PDF for Java API Reference
description: <p> Represents an absorber object of page structure objects such as sections and paragraphs. Performs search for sections and paragraphs of text and provides access for.
type: docs
weight: 3470
url: /java/com.aspose.pdf/paragraphabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ParagraphAbsorber

```
public class ParagraphAbsorber extends Object
```

<p> Represents an absorber object of page structure objects such as sections and paragraphs. Performs search for sections and paragraphs of text and provides access for rectangles and polydons that describes it in text coordinate space. Also performs text segments search and provides access to search results via {@code TextFragments} collections grouped by structure elements. </p> The example demonstrates how to find first text segment of each paragraph on the first PDF document page and highlight it. <p> // Open document Document doc = new Document("input.pdf"); // Create ParagraphAbsorber object ParagraphAbsorber absorber = new ParagraphAbsorber(); // Accept the absorber for first page absorber.visit(doc.getPages.get_Item(1)); // Get markup object of first page PageMarkup markup = absorber.getPageMarkups().get(0); // Loop through structure elements of the page text to find first text fragment of each paragraph for (MarkupSection section : markup.getSections()) { for (MarkupParagraph paragraph : section.getParagraphs()) { TextFragment fragment = paragraph.getFragments().get_Item(0); // Update text properties fragment.getTextState().setBackgroundColor (Color.getLightBlue()); } } // Save document doc.save(GetOutputPath("output.pdf")); </p> <hr> When the search is completed the {@code ParagraphAbsorber.PageMarkups} collection will contains {@code PageMarkup} objects that represents page structure by collections of {@code MarkupSection} and {@code MarkupParagraph}. The {@code TextFragment} object provides access to the search occurrence text, text properties, and allows to edit text and change the text state (font, font size, color etc).

## Constructors

| Constructor | Description |
| --- | --- |
| [ParagraphAbsorber](#ParagraphAbsorber--) | Initializes a new instance of the {@code ParagraphAbsorber} that performs search for sections/paragraphs of the document or page. |
| [ParagraphAbsorber](#ParagraphAbsorber-int-) | <p> Initializes a new instance of the {@code ParagraphAbsorber} that performs search for sections/paragraphs of the document or page. </p> |
| [ParagraphAbsorber](#ParagraphAbsorber-int-com.aspose.pdf.ParagraphAbsorberOptions-) | Initializes a new instance of the {@code ParagraphAbsorber} that performs search for sections/paragraphs of the document or page. |
| [ParagraphAbsorber](#ParagraphAbsorber-com.aspose.pdf.ParagraphAbsorberOptions-) | Initializes a new instance of the {@code ParagraphAbsorber} that performs search for sections/paragraphs of the document or page. |

## Methods

| Method | Description |
| --- | --- |
| [getPageMarkups](#getPageMarkups--) | Gets collection of {@code PageMarkup} that were absorbed. |
| [getParagraphAbsorberOptions](#getParagraphAbsorberOptions--) | Gets the ParagraphAbsorberOptions. |
| [getSectionsSearchDepth](#getSectionsSearchDepth--) | <p> Gets or sets value that instructs how many times sequential searches for more fine elements of structure will be performed. Default search depth is 3. It means three searches for horizontally divided sections (headers, paragraphs etc) and three searches for vertically divided ones (columns). </p><hr> Increasing of this value may lead to minor decreasing performance with no visible changes in search result. Decreasing of this value may lead to incorrect determination of paragraphs in sections. We are not recommend to set value less than default if you aren't desire to get only 'rough' elements of page structure. |
| [getTextReplaceOptions](#getTextReplaceOptions--) | Gets or sets the TextReplaceOptions. |
| [isMulticolumnParagraphsAllowed](#isMulticolumnParagraphsAllowed--) | Gets or sets value that indicates whether starting text lines of a next section may be treated as continuation of the last paragraph of a previous section. |
| [setMulticolumnParagraphsAllowed](#setMulticolumnParagraphsAllowed-boolean-) | Gets or sets value that indicates whether starting text lines of a next section may be treated as continuation of the last paragraph of a previous section. |
| [setParagraphAbsorberOptions](#setParagraphAbsorberOptions-com.aspose.pdf.ParagraphAbsorberOptions-) | Sets the ParagraphAbsorberOptions. |
| [setSectionsSearchDepth](#setSectionsSearchDepth-int-) | <p> Gets or sets value that instructs how many times sequential searches for more fine elements of structure will be performed. Default search depth is 3. It means three searches for horizontally divided sections (headers, paragraphs etc) and three searches for vertically divided ones (columns). </p><hr> Increasing of this value may lead to minor decreasing performance with no visible changes in search result. Decreasing of this value may lead to incorrect determination of paragraphs in sections. We are not recommend to set value less than default if you aren't desire to get only 'rough' elements of page structure. |
| [setTextReplaceOptions](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | Gets or sets the TextReplaceOptions. |
| [visit](#visit-com.aspose.pdf.Document-) | Performs search for sections and paragraphs on the specified {@link Document}. |
| [visit](#visit-com.aspose.pdf.Page-) | Performs search on the specified {@code Page}. |

### ParagraphAbsorber {#ParagraphAbsorber--}
```
public ParagraphAbsorber()
```

Initializes a new instance of the {@code ParagraphAbsorber} that performs search for sections/paragraphs of the document or page.

### ParagraphAbsorber {#ParagraphAbsorber-int-}
```
public ParagraphAbsorber(int sectionsSearchDepth)
```

<p> Initializes a new instance of the {@code ParagraphAbsorber} that performs search for sections/paragraphs of the document or page. </p>

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sectionsSearchDepth |  | Number of sequential searches for more fine elements of structure that will be performed. <hr> See {@code ParagraphAbsorber.SectionsSearchDepth} property for more hints about the parameter. <hr> |

### ParagraphAbsorber {#ParagraphAbsorber-int-com.aspose.pdf.ParagraphAbsorberOptions-}
Initializes a new instance of the {@code ParagraphAbsorber} that performs search for sections/paragraphs of the document or page.

### ParagraphAbsorber {#ParagraphAbsorber-com.aspose.pdf.ParagraphAbsorberOptions-}
Initializes a new instance of the {@code ParagraphAbsorber} that performs search for sections/paragraphs of the document or page.

### getPageMarkups {#getPageMarkups--}
```
public List < PageMarkup > getPageMarkups()
```

Gets collection of {@code PageMarkup} that were absorbed.

**Returns:**
List of PageMarkup instances

### getParagraphAbsorberOptions {#getParagraphAbsorberOptions--}
```
public final ParagraphAbsorberOptions getParagraphAbsorberOptions()
```

Gets the ParagraphAbsorberOptions.

**Returns:**
ParagraphAbsorberOptions instance

### getSectionsSearchDepth {#getSectionsSearchDepth--}
```
public int getSectionsSearchDepth()
```

<p> Gets or sets value that instructs how many times sequential searches for more fine elements of structure will be performed. Default search depth is 3. It means three searches for horizontally divided sections (headers, paragraphs etc) and three searches for vertically divided ones (columns). </p><hr> Increasing of this value may lead to minor decreasing performance with no visible changes in search result. Decreasing of this value may lead to incorrect determination of paragraphs in sections. We are not recommend to set value less than default if you aren't desire to get only 'rough' elements of page structure.

**Returns:**
int value

### getTextReplaceOptions {#getTextReplaceOptions--}
```
public final TextReplaceOptions getTextReplaceOptions()
```

Gets or sets the TextReplaceOptions.

**Returns:**
TextReplaceOptions instance

### isMulticolumnParagraphsAllowed {#isMulticolumnParagraphsAllowed--}
```
public final boolean isMulticolumnParagraphsAllowed()
```

Gets or sets value that indicates whether starting text lines of a next section may be treated as continuation of the last paragraph of a previous section.

**Returns:**
boolean value

### setMulticolumnParagraphsAllowed {#setMulticolumnParagraphsAllowed-boolean-}
```
public final void setMulticolumnParagraphsAllowed(boolean value)
```

Gets or sets value that indicates whether starting text lines of a next section may be treated as continuation of the last paragraph of a previous section.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setParagraphAbsorberOptions {#setParagraphAbsorberOptions-com.aspose.pdf.ParagraphAbsorberOptions-}
Sets the ParagraphAbsorberOptions.

### setSectionsSearchDepth {#setSectionsSearchDepth-int-}
```
public void setSectionsSearchDepth(int value)
```

<p> Gets or sets value that instructs how many times sequential searches for more fine elements of structure will be performed. Default search depth is 3. It means three searches for horizontally divided sections (headers, paragraphs etc) and three searches for vertically divided ones (columns). </p><hr> Increasing of this value may lead to minor decreasing performance with no visible changes in search result. Decreasing of this value may lead to incorrect determination of paragraphs in sections. We are not recommend to set value less than default if you aren't desire to get only 'rough' elements of page structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setTextReplaceOptions {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
Gets or sets the TextReplaceOptions.

### visit {#visit-com.aspose.pdf.Document-}
Performs search for sections and paragraphs on the specified {@link Document}.

### visit {#visit-com.aspose.pdf.Page-}
Performs search on the specified {@code Page}.
