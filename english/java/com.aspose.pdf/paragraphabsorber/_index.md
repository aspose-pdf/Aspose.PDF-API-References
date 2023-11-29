---
title: ParagraphAbsorber
second_title: Aspose.PDF for Java API Reference
description: Represents an absorber object of page structure objects such as sections and paragraphs.
type: docs
weight: 269
url: /java/com.aspose.pdf/paragraphabsorber/
---
**Inheritance:**
java.lang.Object
```
public class ParagraphAbsorber
```

Represents an absorber object of page structure objects such as sections and paragraphs. Performs search for sections and paragraphs of text and provides access for rectangles and polydons that describes it in text coordinate space. Also performs text segments search and provides access to search results via  TextFragments  collections grouped by structure elements.

--------------------

The example demonstrates how to find first text segment of each paragraph on the first PDF document page and highlight it.

// Open document Document doc = new Document("input.pdf"); // Create ParagraphAbsorber object ParagraphAbsorber absorber = new ParagraphAbsorber(); // Accept the absorber for first page absorber.visit(doc.getPages.get\_Item(1)); // Get markup object of first page PageMarkup markup = absorber.getPageMarkups().get(0); // Loop through structure elements of the page text to find first text fragment of each paragraph for (MarkupSection section : markup.getSections()) \{ for (MarkupParagraph paragraph : section.getParagraphs()) \{ TextFragment fragment = paragraph.getFragments().get\_Item(0); // Update text properties fragment.getTextState().setBackgroundColor (Color.getLightBlue()); \} \} // Save document doc.save(GetOutputPath("output.pdf"));

--------------------

When the search is completed the  ParagraphAbsorber.PageMarkups  collection will contains  PageMarkup  objects that represents page structure by collections of  MarkupSection  and  MarkupParagraph . The  TextFragment  object provides access to the search occurrence text, text properties, and allows to edit text and change the text state (font, font size, color etc).
## Constructors

| Constructor | Description |
| --- | --- |
| [ParagraphAbsorber()](#ParagraphAbsorber--) | Initializes a new instance of the  ParagraphAbsorber  that performs search for sections/paragraphs of the document or page. |
| [ParagraphAbsorber(int sectionsSearchDepth)](#ParagraphAbsorber-int-) | Initializes a new instance of the  ParagraphAbsorber  that performs search for sections/paragraphs of the document or page. |
## Methods

| Method | Description |
| --- | --- |
| [getPageMarkups()](#getPageMarkups--) | Gets collection of  PageMarkup  that were absorbed. |
| [getSectionsSearchDepth()](#getSectionsSearchDepth--) | Gets or sets value that instructs how many times sequential searches for more fine elements of structure will be performed. |
| [setSectionsSearchDepth(int value)](#setSectionsSearchDepth-int-) | Gets or sets value that instructs how many times sequential searches for more fine elements of structure will be performed. |
| [isMulticolumnParagraphsAllowed()](#isMulticolumnParagraphsAllowed--) | Gets or sets value that indicates whether starting text lines of a next section may be treated as continuation of the last paragraph of a previous section. |
| [setMulticolumnParagraphsAllowed(boolean value)](#setMulticolumnParagraphsAllowed-boolean-) | Gets or sets value that indicates whether starting text lines of a next section may be treated as continuation of the last paragraph of a previous section. |
| [visit(Document doc)](#visit-com.aspose.pdf.Document-) | Performs search for sections and paragraphs on the specified [Document](../../com.aspose.pdf/document). |
| [visit(Page page)](#visit-com.aspose.pdf.Page-) | Performs search on the specified  Page . |
### ParagraphAbsorber() {#ParagraphAbsorber--}
```
public ParagraphAbsorber()
```


Initializes a new instance of the  ParagraphAbsorber  that performs search for sections/paragraphs of the document or page.

### ParagraphAbsorber(int sectionsSearchDepth) {#ParagraphAbsorber-int-}
```
public ParagraphAbsorber(int sectionsSearchDepth)
```


Initializes a new instance of the  ParagraphAbsorber  that performs search for sections/paragraphs of the document or page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sectionsSearchDepth | int | Number of sequential searches for more fine elements of structure that will be performed.

--------------------

See  ParagraphAbsorber.SectionsSearchDepth  property for more hints about the parameter.

-------------------- |

### getPageMarkups() {#getPageMarkups--}
```
public List<PageMarkup> getPageMarkups()
```


Gets collection of  PageMarkup  that were absorbed.

**Returns:**
java.util.List<com.aspose.pdf.PageMarkup> - List of PageMarkup instances
### getSectionsSearchDepth() {#getSectionsSearchDepth--}
```
public int getSectionsSearchDepth()
```


Gets or sets value that instructs how many times sequential searches for more fine elements of structure will be performed. Default search depth is 3. It means three searches for horizontally divided sections (headers, paragraphs etc) and three searches for vertically divided ones (columns).

--------------------

Increasing of this value may lead to minor decreasing performance with no visible changes in search result. Decreasing of this value may lead to incorrect determination of paragraphs in sections. We are not recommend to set value less than default if you aren't desire to get only 'rough' elements of page structure.

**Returns:**
int - int value
### setSectionsSearchDepth(int value) {#setSectionsSearchDepth-int-}
```
public void setSectionsSearchDepth(int value)
```


Gets or sets value that instructs how many times sequential searches for more fine elements of structure will be performed. Default search depth is 3. It means three searches for horizontally divided sections (headers, paragraphs etc) and three searches for vertically divided ones (columns).

--------------------

Increasing of this value may lead to minor decreasing performance with no visible changes in search result. Decreasing of this value may lead to incorrect determination of paragraphs in sections. We are not recommend to set value less than default if you aren't desire to get only 'rough' elements of page structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### isMulticolumnParagraphsAllowed() {#isMulticolumnParagraphsAllowed--}
```
public final boolean isMulticolumnParagraphsAllowed()
```


Gets or sets value that indicates whether starting text lines of a next section may be treated as continuation of the last paragraph of a previous section.

**Returns:**
boolean - boolean value
### setMulticolumnParagraphsAllowed(boolean value) {#setMulticolumnParagraphsAllowed-boolean-}
```
public final void setMulticolumnParagraphsAllowed(boolean value)
```


Gets or sets value that indicates whether starting text lines of a next section may be treated as continuation of the last paragraph of a previous section.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### visit(Document doc) {#visit-com.aspose.pdf.Document-}
```
public void visit(Document doc)
```


Performs search for sections and paragraphs on the specified [Document](../../com.aspose.pdf/document).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| doc | [Document](../../com.aspose.pdf/document) | Pdf document object. |

### visit(Page page) {#visit-com.aspose.pdf.Page-}
```
public void visit(Page page)
```


Performs search on the specified  Page .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Pdf document page object. |

