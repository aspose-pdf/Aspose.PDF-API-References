---
title: TextParagraphAbsorber
second_title: Aspose.PDF for Java API Reference
description: Represents an absorber object of text paragraphs.
type: docs
weight: 380
url: /java/com.aspose.pdf/textparagraphabsorber/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.TextAbsorber](../../com.aspose.pdf/textabsorber)
```
public final class TextParagraphAbsorber extends TextAbsorber
```

Represents an absorber object of text paragraphs. Performs text search and provides access to search results via  TextParagraphAbsorber.TextParagraphs  collection.
## Constructors

| Constructor | Description |
| --- | --- |
| [TextParagraphAbsorber(Rectangle[] rectangles)](#TextParagraphAbsorber-com.aspose.pdf.Rectangle---) | Initializes a new instance of the  TextParagraphAbsorber  with rectangles collection. |
## Methods

| Method | Description |
| --- | --- |
| [getTextParagraphs()](#getTextParagraphs--) | Gets collection of search occurrences that are presented with  TextParagraph  objects. |
| [setTextParagraphs(TextParagraphCollection value)](#setTextParagraphs-com.aspose.pdf.TextParagraphCollection-) | Sets collection of search occurrences that are presented with  TextParagraph  objects. |
| [getRectangles()](#getRectangles--) | Gets ractangles that the  TextParagraphAbsorber  used to searche for text paragraphs on the PDF document or page. |
| [setRectangles(Rectangle[] value)](#setRectangles-com.aspose.pdf.Rectangle---) | Sets rectangles that the  TextParagraphAbsorber  used to search for text paragraphs on the PDF document or page. |
| [visit(Page page)](#visit-com.aspose.pdf.Page-) | Performs search on the specified page. |
### TextParagraphAbsorber(Rectangle[] rectangles) {#TextParagraphAbsorber-com.aspose.pdf.Rectangle---}
```
public TextParagraphAbsorber(Rectangle[] rectangles)
```


Initializes a new instance of the  TextParagraphAbsorber  with rectangles collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangles | [Rectangle\[\]](../../com.aspose.pdf/rectangle) | The paragraphs' rectangles.

--------------------

The absorber will search for text and return paragraphs corresponding to the rectangles. |

### getTextParagraphs() {#getTextParagraphs--}
```
public TextParagraphCollection getTextParagraphs()
```


Gets collection of search occurrences that are presented with  TextParagraph  objects.

**Returns:**
[TextParagraphCollection](../../com.aspose.pdf/textparagraphcollection) - TextParagraphCollection value
### setTextParagraphs(TextParagraphCollection value) {#setTextParagraphs-com.aspose.pdf.TextParagraphCollection-}
```
public void setTextParagraphs(TextParagraphCollection value)
```


Sets collection of search occurrences that are presented with  TextParagraph  objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextParagraphCollection](../../com.aspose.pdf/textparagraphcollection) | TextParagraphCollection value |

### getRectangles() {#getRectangles--}
```
public Rectangle[] getRectangles()
```


Gets ractangles that the  TextParagraphAbsorber  used to searche for text paragraphs on the PDF document or page.

**Returns:**
com.aspose.pdf.Rectangle[] - rectangle array
### setRectangles(Rectangle[] value) {#setRectangles-com.aspose.pdf.Rectangle---}
```
public void setRectangles(Rectangle[] value)
```


Sets rectangles that the  TextParagraphAbsorber  used to search for text paragraphs on the PDF document or page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.pdf/rectangle) | rectangle array |

### visit(Page page) {#visit-com.aspose.pdf.Page-}
```
public void visit(Page page)
```


Performs search on the specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Page object |

