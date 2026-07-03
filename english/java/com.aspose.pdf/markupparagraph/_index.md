---
title: MarkupParagraph
second_title: Aspose.PDF for Java API Reference
description: Represents a paragraph.
type: docs
weight: 2880
url: /java/com.aspose.pdf/markupparagraph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.MarkupParagraph

```
public final class MarkupParagraph extends Object
```

Represents a paragraph.

## Methods

| Method | Description |
| --- | --- |
| [getContinuationPageNumbers](#getContinuationPageNumbers--) | List of page numbers on which the paragraph is continued. It will match with page where the paragraph started if it is continuing in the next column on the same page. |
| [getFragments](#getFragments--) | <p> Collection of not empty {@code TextFragment} objects of the paragraph. </p><hr> The {@code TextFragment} object provides access to the search occurrence text, text properties, and allows to edit text and change the text state (font, font size, color etc). |
| [getFragmentsInternal](#getFragmentsInternal--) |  |
| [getLines](#getLines--) | <p> Lines of paragraph. Each line represented by list of text fragments. </p><hr> The {@code TextFragment} object provides access to the search occurrence text, text properties, and allows to edit text and change the text state (font, font size, color etc). |
| [getLinesInternal](#getLinesInternal--) |  |
| [getPoints](#getPoints--) | Points of polygon that describes paragraph. Starting point is lower left corner of the paragraph. And next points are in anti-clockwise sequence. |
| [getSecondaryPoints](#getSecondaryPoints--) | Points of secondary polygon describes paragraph continuation. It will not be null if the paragraph is continued in the next column or page. Starting point is lower left corner of the paragraph. And next points are in anti-clockwise sequence. |
| [getText](#getText--) | Gets {@code string} text object that the {@code MarkupParagraph} object represents. |
| [setText](#setText-java.lang.String-) | Gets or sets the paragraph text. |

### getContinuationPageNumbers {#getContinuationPageNumbers--}
```
public final List < Integer > getContinuationPageNumbers()
```

List of page numbers on which the paragraph is continued. It will match with page where the paragraph started if it is continuing in the next column on the same page.

**Returns:**
list of Integer

### getFragments {#getFragments--}
```
public List < TextFragment > getFragments()
```

<p> Collection of not empty {@code TextFragment} objects of the paragraph. </p><hr> The {@code TextFragment} object provides access to the search occurrence text, text properties, and allows to edit text and change the text state (font, font size, color etc).

**Returns:**
list of TextFragment instances

### getFragmentsInternal {#getFragmentsInternal--}
```
public com.aspose.ms.System.Collections.Generic.List< TextFragment > getFragmentsInternal()
```



### getLines {#getLines--}
```
public List <com.aspose.ms.System.Collections.Generic.List< TextFragment >> getLines()
```

<p> Lines of paragraph. Each line represented by list of text fragments. </p><hr> The {@code TextFragment} object provides access to the search occurrence text, text properties, and allows to edit text and change the text state (font, font size, color etc).

**Returns:**
list of TextFragment instances

### getLinesInternal {#getLinesInternal--}
```
public com.aspose.ms.System.Collections.Generic.List<com.aspose.ms.System.Collections.Generic.List< TextFragment >> getLinesInternal()
```



### getPoints {#getPoints--}
```
public Point [] getPoints()
```

Points of polygon that describes paragraph. Starting point is lower left corner of the paragraph. And next points are in anti-clockwise sequence.

**Returns:**
array of Point instances

### getSecondaryPoints {#getSecondaryPoints--}
```
public final List < Point []> getSecondaryPoints()
```

Points of secondary polygon describes paragraph continuation. It will not be null if the paragraph is continued in the next column or page. Starting point is lower left corner of the paragraph. And next points are in anti-clockwise sequence.

**Returns:**
list of Point[]

### getText {#getText--}
```
public String getText()
```

Gets {@code string} text object that the {@code MarkupParagraph} object represents.

**Returns:**
String value

### setText {#setText-java.lang.String-}
Gets or sets the paragraph text.
