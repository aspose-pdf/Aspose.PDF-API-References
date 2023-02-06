---
title: PageMarkup
second_title: Aspose.PDF for Java API Reference
description: Page markup represented by collections of MarkupSection and MarkupParagraph.
type: docs
weight: 268
url: /java/com.aspose.pdf/pagemarkup/
---
**Inheritance:**
java.lang.Object
```
public final class PageMarkup
```

Page markup represented by collections of  MarkupSection  and  MarkupParagraph .
## Methods

| Method | Description |
| --- | --- |
| [getNumber()](#getNumber--) | Gets processed page number. |
| [getRectangle()](#getRectangle--) | Gets processed page rectangle. |
| [getSections()](#getSections--) | Gets collection of  MarkupSection  that was found on the page. |
| [getParagraphs()](#getParagraphs--) | Gets collection of  MarkupParagraph  that was found on the page. |
| [getTextFragments()](#getTextFragments--) | Gets collection of  TextFragment  that was found on the page. |
| [isMulticolumnParagraphsAllowed()](#isMulticolumnParagraphsAllowed--) | Gets or sets value that indicates whether starting text lines of a next section may be treated as continuation of the last paragraph of a previous section. |
| [setMulticolumnParagraphsAllowed(boolean value)](#setMulticolumnParagraphsAllowed-boolean-) | Gets or sets value that indicates whether starting text lines of a next section may be treated as continuation of the last paragraph of a previous section. |
### getNumber() {#getNumber--}
```
public int getNumber()
```


Gets processed page number.

**Returns:**
int - int value
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Gets processed page rectangle.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle object
### getSections() {#getSections--}
```
public List<MarkupSection> getSections()
```


Gets collection of  MarkupSection  that was found on the page.

**Returns:**
java.util.List<com.aspose.pdf.MarkupSection> - List of MarkupSection instances
### getParagraphs() {#getParagraphs--}
```
public List<MarkupParagraph> getParagraphs()
```


Gets collection of  MarkupParagraph  that was found on the page.

**Returns:**
java.util.List<com.aspose.pdf.MarkupParagraph> - List of MarkupParagraph instances
### getTextFragments() {#getTextFragments--}
```
public List<TextFragment> getTextFragments()
```


Gets collection of  TextFragment  that was found on the page.

--------------------

The  TextFragment  object provides access to the search occurrence text, text properties, and allows to edit text and change the text state (font, font size, color etc).

**Returns:**
java.util.List<com.aspose.pdf.TextFragment> - List of TextFragment instances
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

