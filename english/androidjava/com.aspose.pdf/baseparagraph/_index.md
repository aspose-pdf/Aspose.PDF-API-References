---
title: BaseParagraph
second_title: Aspose.PDF for Java API Reference
description: Represents a abstract base object can be added to the pagedoc.Paragraphs.Add.
type: docs
weight: 33
url: /java/com.aspose.pdf/baseparagraph/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable
```
public abstract class BaseParagraph implements System.ICloneable
```

Represents a abstract base object can be added to the page(doc.Paragraphs.Add()).
## Constructors

| Constructor | Description |
| --- | --- |
| [BaseParagraph()](#BaseParagraph--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getVerticalAlignment()](#getVerticalAlignment--) | Gets a vertical alignment of paragraph |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Sets a vertical alignment of paragraph |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Gets a horizontal alignment of paragraph |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Sets a horizontal alignment of paragraph |
| [getMargin()](#getMargin--) | Gets a outer margin for paragraph (for pdf generation) |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | Sets a outer margin for paragraph (for pdf generation) |
| [isFirstParagraphInColumn()](#isFirstParagraphInColumn--) | Gets or sets a bool value that indicates whether this paragraph will be at next column. |
| [setFirstParagraphInColumn(boolean value)](#setFirstParagraphInColumn-boolean-) | Gets or sets a bool value that indicates whether this paragraph will be at next column. |
| [isKeptWithNext()](#isKeptWithNext--) | Gets a boolean value that indicates whether current paragraph remains in the same page along with next paragraph. |
| [setKeptWithNext(boolean value)](#setKeptWithNext-boolean-) | Sets a boolean value that indicates whether current paragraph remains in the same page along with next paragraph. |
| [isInNewPage()](#isInNewPage--) | Gets a bool value that force this paragraph generates at new page. |
| [setInNewPage(boolean value)](#setInNewPage-boolean-) | Sets a boolean value that force this paragraph generates at new page. |
| [isInLineParagraph()](#isInLineParagraph--) | Gets a paragraph is inline. |
| [setInLineParagraph(boolean value)](#setInLineParagraph-boolean-) | Sets a paragraph is inline. |
| [getHyperlink()](#getHyperlink--) | Gets the fragment hyperlink(for pdf generator). |
| [setHyperlink(Hyperlink value)](#setHyperlink-com.aspose.pdf.Hyperlink-) | Sets hyperlink(for pdf generator). |
| [getZIndex()](#getZIndex--) | Gets an int value that indicates the Z-order of the graph. |
| [setZIndex(int value)](#setZIndex-int-) | Sets a int value that indicates the Z-order of the graph. |
| [deepClone()](#deepClone--) | Clones this instance. |
### BaseParagraph() {#BaseParagraph--}
```
public BaseParagraph()
```


### getVerticalAlignment() {#getVerticalAlignment--}
```
public int getVerticalAlignment()
```


Gets a vertical alignment of paragraph

**Returns:**
int - VerticalAlignment element
### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int value)
```


Sets a vertical alignment of paragraph

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | VerticalAlignment element |

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


Gets a horizontal alignment of paragraph

**Returns:**
int - HorizontalAlignment value
### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```


Sets a horizontal alignment of paragraph

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | HorizontalAlignment value |

### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


Gets a outer margin for paragraph (for pdf generation)

**Returns:**
[MarginInfo](../../com.aspose.pdf/margininfo) - MarginInfo value
### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public void setMargin(MarginInfo value)
```


Sets a outer margin for paragraph (for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo object |

### isFirstParagraphInColumn() {#isFirstParagraphInColumn--}
```
public boolean isFirstParagraphInColumn()
```


Gets or sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation)

**Returns:**
boolean - boolean value
### setFirstParagraphInColumn(boolean value) {#setFirstParagraphInColumn-boolean-}
```
public void setFirstParagraphInColumn(boolean value)
```


Gets or sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isKeptWithNext() {#isKeptWithNext--}
```
public boolean isKeptWithNext()
```


Gets a boolean value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation)

**Returns:**
boolean - boolean value
### setKeptWithNext(boolean value) {#setKeptWithNext-boolean-}
```
public final void setKeptWithNext(boolean value)
```


Sets a boolean value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isInNewPage() {#isInNewPage--}
```
public boolean isInNewPage()
```


Gets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation)

**Returns:**
boolean - boolean value
### setInNewPage(boolean value) {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```


Sets a boolean value that force this paragraph generates at new page. Default is false.(for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isInLineParagraph() {#isInLineParagraph--}
```
public boolean isInLineParagraph()
```


Gets a paragraph is inline. Default is false.(for pdf generation)

**Returns:**
boolean - boolean value
### setInLineParagraph(boolean value) {#setInLineParagraph-boolean-}
```
public void setInLineParagraph(boolean value)
```


Sets a paragraph is inline. Default is false.(for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getHyperlink() {#getHyperlink--}
```
public Hyperlink getHyperlink()
```


Gets the fragment hyperlink(for pdf generator).

**Returns:**
[Hyperlink](../../com.aspose.pdf/hyperlink) - the fragment hyperlink(for pdf generator).
### setHyperlink(Hyperlink value) {#setHyperlink-com.aspose.pdf.Hyperlink-}
```
public void setHyperlink(Hyperlink value)
```


Sets hyperlink(for pdf generator).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Hyperlink](../../com.aspose.pdf/hyperlink) | hyperlink(for pdf generator). |

### getZIndex() {#getZIndex--}
```
public int getZIndex()
```


Gets an int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page.

**Returns:**
int - int value
### setZIndex(int value) {#setZIndex-int-}
```
public void setZIndex(int value)
```


Sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clones this instance. Virtual method. Always return null.

**Returns:**
java.lang.Object - Cloned object
