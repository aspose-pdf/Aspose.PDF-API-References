---
title: TextParagraphAbsorber
second_title: Aspose.PDF for Java API Reference
description: Represents an absorber object of text paragraphs. Performs text search and provides access to search results via {@code TextParagraphAbsorber.TextParagraphs} collection.
type: docs
weight: 5220
url: /java/com.aspose.pdf/textparagraphabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextAbsorber com.aspose.pdf.TextParagraphAbsorber, com.aspose.pdf.TextAbsorber, com.aspose.pdf.TextParagraphAbsorber

```
public final class TextParagraphAbsorber extends TextAbsorber
```

Represents an absorber object of text paragraphs. Performs text search and provides access to search results via {@code TextParagraphAbsorber.TextParagraphs} collection.

## Constructors

| Constructor | Description |
| --- | --- |
| [TextParagraphAbsorber](#TextParagraphAbsorber-com.aspose.pdf.Rectangle:A-) | <p> Initializes a new instance of the {@code TextParagraphAbsorber} with rectangles collection. </p> |

## Methods

| Method | Description |
| --- | --- |
| [getRectangles](#getRectangles--) | Gets ractangles that the {@code TextParagraphAbsorber} used to searche for text paragraphs on the PDF document or page. |
| [getTextParagraphs](#getTextParagraphs--) | Gets collection of search occurrences that are presented with {@code TextParagraph} objects. |
| [setRectangles](#setRectangles-com.aspose.pdf.Rectangle:A-) | Sets rectangles that the {@code TextParagraphAbsorber} used to search for text paragraphs on the PDF document or page. |
| [setTextParagraphs](#setTextParagraphs-com.aspose.pdf.TextParagraphCollection-) | Sets collection of search occurrences that are presented with {@code TextParagraph} objects. |
| [visit](#visit-com.aspose.pdf.Page-) | Performs search on the specified page. |

### TextParagraphAbsorber {#TextParagraphAbsorber-com.aspose.pdf.Rectangle:A-}
<p> Initializes a new instance of the {@code TextParagraphAbsorber} with rectangles collection. </p>

### getRectangles {#getRectangles--}
```
public Rectangle [] getRectangles()
```

Gets ractangles that the {@code TextParagraphAbsorber} used to searche for text paragraphs on the PDF document or page.

**Returns:**
rectangle array

### getTextParagraphs {#getTextParagraphs--}
```
public TextParagraphCollection getTextParagraphs()
```

Gets collection of search occurrences that are presented with {@code TextParagraph} objects.

**Returns:**
TextParagraphCollection value

### setRectangles {#setRectangles-com.aspose.pdf.Rectangle:A-}
Sets rectangles that the {@code TextParagraphAbsorber} used to search for text paragraphs on the PDF document or page.

### setTextParagraphs {#setTextParagraphs-com.aspose.pdf.TextParagraphCollection-}
Sets collection of search occurrences that are presented with {@code TextParagraph} objects.

### visit {#visit-com.aspose.pdf.Page-}
Performs search on the specified page.
