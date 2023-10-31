---
title: MarkupSection
second_title: Aspose.PDF for Java API Reference
description: Represents a markup section - the rectangular region of a page that contains text and can be visually divided from another text blocks.
type: docs
weight: 206
url: /java/com.aspose.pdf/markupsection/
---
**Inheritance:**
java.lang.Object
```
public final class MarkupSection
```

Represents a markup section - the rectangular region of a page that contains text and can be visually divided from another text blocks.
## Methods

| Method | Description |
| --- | --- |
| [getRectangle()](#getRectangle--) | Section rectangle |
| [getFragments()](#getFragments--) | Collection of not empty  TextFragment  objects that are inside the section. |
| [getParagraphs()](#getParagraphs--) | Collection of  MarkupParagraph  objects that are inside the section. |
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Section rectangle

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle instance
### getFragments() {#getFragments--}
```
public List<TextFragment> getFragments()
```


Collection of not empty  TextFragment  objects that are inside the section.

--------------------

The  TextFragment  object provides access to the search occurrence text, text properties, and allows to edit text and change the text state (font, font size, color etc).

**Returns:**
java.util.List<com.aspose.pdf.TextFragment> - list of TextFragment instances
### getParagraphs() {#getParagraphs--}
```
public List<MarkupParagraph> getParagraphs()
```


Collection of  MarkupParagraph  objects that are inside the section.

**Returns:**
java.util.List<com.aspose.pdf.MarkupParagraph> - list of MarkupParagraph instances
