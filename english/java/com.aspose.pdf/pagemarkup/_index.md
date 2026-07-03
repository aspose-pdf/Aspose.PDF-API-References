---
title: PageMarkup
second_title: Aspose.PDF for Java API Reference
description: Page markup represented by collections of {@code MarkupSection} and {@code MarkupParagraph}.
type: docs
weight: 3420
url: /java/com.aspose.pdf/pagemarkup/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageMarkup

```
public final class PageMarkup extends Object
```

Page markup represented by collections of {@code MarkupSection} and {@code MarkupParagraph}.

## Methods

| Method | Description |
| --- | --- |
| [getNumber](#getNumber--) | Gets processed page number. |
| [getParagraphs](#getParagraphs--) | Gets collection of {@code MarkupParagraph} that was found on the page. |
| [getRectangle](#getRectangle--) | Gets processed page rectangle. |
| [getSections](#getSections--) | Gets collection of {@code MarkupSection} that was found on the page. |
| [getTextFragments](#getTextFragments--) | <p> Gets collection of {@code TextFragment} that was found on the page. </p><hr> The {@code TextFragment} object provides access to the search occurrence text, text properties, and allows to edit text and change the text state (font, font size, color etc). |
| [isMulticolumnParagraphsAllowed](#isMulticolumnParagraphsAllowed--) | Gets or sets value that indicates whether starting text lines of a next section may be treated as continuation of the last paragraph of a previous section. |
| [setMulticolumnParagraphsAllowed](#setMulticolumnParagraphsAllowed-boolean-) | Gets or sets value that indicates whether starting text lines of a next section may be treated as continuation of the last paragraph of a previous section. |

### getNumber {#getNumber--}
```
public int getNumber()
```

Gets processed page number.

**Returns:**
int value

### getParagraphs {#getParagraphs--}
```
public List < MarkupParagraph > getParagraphs()
```

Gets collection of {@code MarkupParagraph} that was found on the page.

**Returns:**
List of MarkupParagraph instances

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Gets processed page rectangle.

**Returns:**
Rectangle object

### getSections {#getSections--}
```
public List < MarkupSection > getSections()
```

Gets collection of {@code MarkupSection} that was found on the page.

**Returns:**
List of MarkupSection instances

### getTextFragments {#getTextFragments--}
```
public List < TextFragment > getTextFragments()
```

<p> Gets collection of {@code TextFragment} that was found on the page. </p><hr> The {@code TextFragment} object provides access to the search occurrence text, text properties, and allows to edit text and change the text state (font, font size, color etc).

**Returns:**
List of TextFragment instances

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
