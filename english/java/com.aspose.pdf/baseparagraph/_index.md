---
title: BaseParagraph
linktitle: BaseParagraph
second_title: Aspose.PDF for Java API Reference
description: Represents a abstract base object can be added to the page(doc.Paragraphs.Add()).
type: docs
weight: 280
url: /java/com.aspose.pdf/baseparagraph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public abstract class BaseParagraph extends Object implements com.aspose.ms.System.ICloneable
```

Represents a abstract base object can be added to the page(doc.Paragraphs.Add()).

## Constructors

| Constructor | Description |
| --- | --- |
| [BaseParagraph](#BaseParagraph--) |  |

## Methods

| Method | Description |
| --- | --- |
| [deepClone](#deepClone--) | Clones this instance. Virtual method. Always return null. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Gets a horizontal alignment of paragraph |
| [getHyperlink](#getHyperlink--) | / * / * Gets or sets a paragraph is footnote. Default is false.(for pdf generation) / * / * |
| [getMargin](#getMargin--) | Gets a outer margin for paragraph (for pdf generation) |
| [getVerticalAlignment](#getVerticalAlignment--) | Gets a vertical alignment of paragraph |
| [getZIndex](#getZIndex--) | Gets an int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |
| [isFirstParagraphInColumn](#isFirstParagraphInColumn--) | Gets or sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [isInLineParagraph](#isInLineParagraph--) | Gets a paragraph is inline. Default is false.(for pdf generation) |
| [isInNewPage](#isInNewPage--) | Gets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [isKeptWithNext](#isKeptWithNext--) | Gets a boolean value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [setFirstParagraphInColumn](#setFirstParagraphInColumn-boolean-) | Gets or sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Sets a horizontal alignment of paragraph |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | Sets hyperlink(for pdf generator). |
| [setInLineParagraph](#setInLineParagraph-boolean-) | Sets a paragraph is inline. Default is false.(for pdf generation) |
| [setInNewPage](#setInNewPage-boolean-) | Sets a boolean value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [setKeptWithNext](#setKeptWithNext-boolean-) | Sets a boolean value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Sets a outer margin for paragraph (for pdf generation) |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Sets a vertical alignment of paragraph |
| [setZIndex](#setZIndex-int-) | Sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |

### BaseParagraph {#BaseParagraph--}
```
public BaseParagraph()
```



### deepClone {#deepClone--}
```
public Object deepClone()
```

Clones this instance. Virtual method. Always return null.

**Returns:**
Null

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Gets a horizontal alignment of paragraph

**Returns:**
HorizontalAlignment value @see HorizontalAlignment

### getHyperlink {#getHyperlink--}
```
public Hyperlink getHyperlink()
```

/ * / * Gets or sets a paragraph is footnote. Default is false.(for pdf generation) / * / *

**Returns:**
boolean value /

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

Gets a outer margin for paragraph (for pdf generation)

**Returns:**
MarginInfo value

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Gets a vertical alignment of paragraph

**Returns:**
VerticalAlignment element @see VerticalAlignment

### getZIndex {#getZIndex--}
```
public int getZIndex()
```

Gets an int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page.

**Returns:**
int value

### isFirstParagraphInColumn {#isFirstParagraphInColumn--}
```
public boolean isFirstParagraphInColumn()
```

Gets or sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation)

**Returns:**
boolean value

### isInLineParagraph {#isInLineParagraph--}
```
public boolean isInLineParagraph()
```

Gets a paragraph is inline. Default is false.(for pdf generation)

**Returns:**
boolean value

### isInNewPage {#isInNewPage--}
```
public boolean isInNewPage()
```

Gets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation)

**Returns:**
boolean value

### isKeptWithNext {#isKeptWithNext--}
```
public boolean isKeptWithNext()
```

Gets a boolean value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation)

**Returns:**
boolean value

### setFirstParagraphInColumn {#setFirstParagraphInColumn-boolean-}
```
public void setFirstParagraphInColumn(boolean value)
```

Gets or sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Sets a horizontal alignment of paragraph

### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
Sets hyperlink(for pdf generator).

### setInLineParagraph {#setInLineParagraph-boolean-}
```
public void setInLineParagraph(boolean value)
```

Sets a paragraph is inline. Default is false.(for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setInNewPage {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```

Sets a boolean value that force this paragraph generates at new page. Default is false.(for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setKeptWithNext {#setKeptWithNext-boolean-}
```
public final void setKeptWithNext(boolean value)
```

Sets a boolean value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Sets a outer margin for paragraph (for pdf generation)

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Sets a vertical alignment of paragraph

### setZIndex {#setZIndex-int-}
```
public void setZIndex(int value)
```

Sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |
