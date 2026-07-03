---
title: MarkupSection
linktitle: MarkupSection
second_title: Aspose.PDF for Java API Reference
description: Represents a markup section - the rectangular region of a page that contains text and can be visually divided from another text blocks.
type: docs
weight: 2890
url: /java/com.aspose.pdf/markupsection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.MarkupSection

```
public final class MarkupSection extends Object
```

Represents a markup section - the rectangular region of a page that contains text and can be visually divided from another text blocks.

## Methods

| Method | Description |
| --- | --- |
| [getFragments](#getFragments--) | <p> Collection of not empty {@code TextFragment} objects that are inside the section. </p><hr> The {@code TextFragment} object provides access to the search occurrence text, text properties, and allows to edit text and change the text state (font, font size, color etc). |
| [getParagraphs](#getParagraphs--) | Collection of {@code MarkupParagraph} objects that are inside the section. |
| [getRectangle](#getRectangle--) | Section rectangle |

### getFragments {#getFragments--}
```
public List < TextFragment > getFragments()
```

<p> Collection of not empty {@code TextFragment} objects that are inside the section. </p><hr> The {@code TextFragment} object provides access to the search occurrence text, text properties, and allows to edit text and change the text state (font, font size, color etc).

**Returns:**
list of TextFragment instances

### getParagraphs {#getParagraphs--}
```
public List < MarkupParagraph > getParagraphs()
```

Collection of {@code MarkupParagraph} objects that are inside the section.

**Returns:**
list of MarkupParagraph instances

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Section rectangle

**Returns:**
Rectangle instance
