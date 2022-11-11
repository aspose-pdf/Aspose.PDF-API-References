---
title: FloatingBox
second_title: Aspose.PDF for Java API Reference
description: Represents a FloatingBox in a Pdf document.
type: docs
weight: 128
url: /java/com.aspose.pdf/floatingbox/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph)
```
public class FloatingBox extends BaseParagraph
```

Represents a FloatingBox in a Pdf document. FloatingBox is custom positioned.
## Constructors

| Constructor | Description |
| --- | --- |
| [FloatingBox(float width, float height)](#FloatingBox-float-float-) | Initializes a new instance of the  FloatingBox  class with specified width and height. |
| [FloatingBox()](#FloatingBox--) | Initializes a new instance of the  FloatingBox  class. |
## Methods

| Method | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Clones a new  FloatingBox  object. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | Gets a object that indicates the background color of the floating box. |
| [getBackgroundImage()](#getBackgroundImage--) | Gets or sets background image for page (for generator only). |
| [getBorder()](#getBorder--) | Gets a object that indicates the border info of the floating box. |
| [getClass()](#getClass--) |  |
| [getColumnInfo()](#getColumnInfo--) | Gets a column info |
| [getHeight()](#getHeight--) | Gets a float value that indicates the height of the floating box. |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Gets a horizontal alignment of paragraph |
| [getHyperlink()](#getHyperlink--) | Gets the fragment hyperlink(for pdf generator). |
| [getLeft()](#getLeft--) | Gets the table left coordinate. |
| [getMargin()](#getMargin--) | Gets a outer margin for paragraph (for pdf generation) |
| [getPadding()](#getPadding--) | Gets a object that indicates the padding of the floating box. |
| [getParagraphs()](#getParagraphs--) | Gets a collection that indicates all paragraphs in the cell. |
| [getTop()](#getTop--) | Gets the table top coordinate. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Gets a vertical alignment of paragraph |
| [getWidth()](#getWidth--) | Gets a float value that indicates the width of the floating box. |
| [getZIndex()](#getZIndex--) | Gets an int value that indicates the Z-order of the graph. |
| [hashCode()](#hashCode--) |  |
| [isFirstParagraphInColumn()](#isFirstParagraphInColumn--) | Gets or sets a bool value that indicates whether this paragraph will be at next column. |
| [isInLineParagraph()](#isInLineParagraph--) | Gets a paragraph is inline. |
| [isInNewPage()](#isInNewPage--) | Gets a bool value that force this paragraph generates at new page. |
| [isKeptWithNext()](#isKeptWithNext--) | Gets a boolean value that indicates whether current paragraph remains in the same page along with next paragraph. |
| [isNeedRepeating()](#isNeedRepeating--) | Gets a boolean value that indicates whether the paragraph need to be repeated on next page. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | Sets a object that indicates the background color of the floating box. |
| [setBackgroundImage(Image value)](#setBackgroundImage-com.aspose.pdf.Image-) | Gets or sets background image for page (for generator only). |
| [setBorder(BorderInfo value)](#setBorder-com.aspose.pdf.BorderInfo-) | Sets a object that indicates the border info of the floating box. |
| [setColumnInfo(ColumnInfo value)](#setColumnInfo-com.aspose.pdf.ColumnInfo-) | Sets a column info |
| [setFirstParagraphInColumn(boolean value)](#setFirstParagraphInColumn-boolean-) | Gets or sets a bool value that indicates whether this paragraph will be at next column. |
| [setHeight(double value)](#setHeight-double-) | Sets a float value that indicates the height of the floating box. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Sets a horizontal alignment of paragraph |
| [setHyperlink(Hyperlink value)](#setHyperlink-com.aspose.pdf.Hyperlink-) | Sets hyperlink(for pdf generator). |
| [setInLineParagraph(boolean value)](#setInLineParagraph-boolean-) | Sets a paragraph is inline. |
| [setInNewPage(boolean value)](#setInNewPage-boolean-) | Sets a boolean value that force this paragraph generates at new page. |
| [setKeptWithNext(boolean value)](#setKeptWithNext-boolean-) | Sets a boolean value that indicates whether current paragraph remains in the same page along with next paragraph. |
| [setLeft(double value)](#setLeft-double-) | Sets the table left coordinate. |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | Sets a outer margin for paragraph (for pdf generation) |
| [setNeedRepeating(boolean value)](#setNeedRepeating-boolean-) | Sets a boolean value that indicates whether the paragraph need to be repeated on next page. |
| [setPadding(MarginInfo value)](#setPadding-com.aspose.pdf.MarginInfo-) | Sets a object that indicates the padding of the floating box. |
| [setParagraphs(Paragraphs value)](#setParagraphs-com.aspose.pdf.Paragraphs-) | Sets a collection that indicates all paragraphs in the cell. |
| [setTop(double value)](#setTop-double-) | Sets the table top coordinate. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Sets a vertical alignment of paragraph |
| [setWidth(double value)](#setWidth-double-) | Sets a float value that indicates the width of the floating box. |
| [setZIndex(int value)](#setZIndex-int-) | Sets a int value that indicates the Z-order of the graph. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FloatingBox(float width, float height) {#FloatingBox-float-float-}
```
public FloatingBox(float width, float height)
```


Initializes a new instance of the  FloatingBox  class with specified width and height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | float | The width of the box. |
| height | float | The height of the box. |

### FloatingBox() {#FloatingBox--}
```
public FloatingBox()
```


Initializes a new instance of the  FloatingBox  class.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clones a new  FloatingBox  object. Paragraphs in the floating box are not cloned.

**Returns:**
java.lang.Object - The new  FloatingBox  object.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Gets a object that indicates the background color of the floating box.

**Returns:**
[Color](../../com.aspose.pdf/color) - object that indicates the background color.
### getBackgroundImage() {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```


Gets or sets background image for page (for generator only).

**Returns:**
[Image](../../com.aspose.pdf/image) - Image instance
### getBorder() {#getBorder--}
```
public BorderInfo getBorder()
```


Gets a object that indicates the border info of the floating box.

**Returns:**
[BorderInfo](../../com.aspose.pdf/borderinfo) - object that indicates the border info.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColumnInfo() {#getColumnInfo--}
```
public ColumnInfo getColumnInfo()
```


Gets a column info

**Returns:**
[ColumnInfo](../../com.aspose.pdf/columninfo) - ColumnInfo object
### getHeight() {#getHeight--}
```
public double getHeight()
```


Gets a float value that indicates the height of the floating box.

**Returns:**
double - value that indicates the height.
### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


Gets a horizontal alignment of paragraph

**Returns:**
int - HorizontalAlignment value
### getHyperlink() {#getHyperlink--}
```
public Hyperlink getHyperlink()
```


Gets the fragment hyperlink(for pdf generator).

**Returns:**
[Hyperlink](../../com.aspose.pdf/hyperlink) - the fragment hyperlink(for pdf generator).
### getLeft() {#getLeft--}
```
public double getLeft()
```


Gets the table left coordinate.

**Returns:**
double - table left coordinate.
### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


Gets a outer margin for paragraph (for pdf generation)

**Returns:**
[MarginInfo](../../com.aspose.pdf/margininfo) - MarginInfo value
### getPadding() {#getPadding--}
```
public MarginInfo getPadding()
```


Gets a object that indicates the padding of the floating box.

**Returns:**
[MarginInfo](../../com.aspose.pdf/margininfo) - object that indicates the padding.
### getParagraphs() {#getParagraphs--}
```
public Paragraphs getParagraphs()
```


Gets a collection that indicates all paragraphs in the cell.

**Returns:**
[Paragraphs](../../com.aspose.pdf/paragraphs) - collection that indicates all paragraphs.
### getTop() {#getTop--}
```
public double getTop()
```


Gets the table top coordinate.

**Returns:**
double - table top coordinate.
### getVerticalAlignment() {#getVerticalAlignment--}
```
public int getVerticalAlignment()
```


Gets a vertical alignment of paragraph

**Returns:**
int - VerticalAlignment element
### getWidth() {#getWidth--}
```
public double getWidth()
```


Gets a float value that indicates the width of the floating box.

**Returns:**
double - double value
### getZIndex() {#getZIndex--}
```
public int getZIndex()
```


Gets an int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page.

**Returns:**
int - int value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isFirstParagraphInColumn() {#isFirstParagraphInColumn--}
```
public boolean isFirstParagraphInColumn()
```


Gets or sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation)

**Returns:**
boolean - boolean value
### isInLineParagraph() {#isInLineParagraph--}
```
public boolean isInLineParagraph()
```


Gets a paragraph is inline. Default is false.(for pdf generation)

**Returns:**
boolean - boolean value
### isInNewPage() {#isInNewPage--}
```
public boolean isInNewPage()
```


Gets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation)

**Returns:**
boolean - boolean value
### isKeptWithNext() {#isKeptWithNext--}
```
public boolean isKeptWithNext()
```


Gets a boolean value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation)

**Returns:**
boolean - boolean value
### isNeedRepeating() {#isNeedRepeating--}
```
public boolean isNeedRepeating()
```


Gets a boolean value that indicates whether the paragraph need to be repeated on next page. Default value is true.The attribute is only valid when the paragraph itself and the object its ReferenceParagraphID referred to both are included in RepeatingRows.

**Returns:**
boolean - boolean value
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.pdf.Color-}
```
public void setBackgroundColor(Color value)
```


Sets a object that indicates the background color of the floating box.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | object that indicates the background color. |

### setBackgroundImage(Image value) {#setBackgroundImage-com.aspose.pdf.Image-}
```
public final void setBackgroundImage(Image value)
```


Gets or sets background image for page (for generator only).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Image](../../com.aspose.pdf/image) | Image instance |

### setBorder(BorderInfo value) {#setBorder-com.aspose.pdf.BorderInfo-}
```
public void setBorder(BorderInfo value)
```


Sets a object that indicates the border info of the floating box.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | object that indicates the border info. |

### setColumnInfo(ColumnInfo value) {#setColumnInfo-com.aspose.pdf.ColumnInfo-}
```
public void setColumnInfo(ColumnInfo value)
```


Sets a column info

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ColumnInfo](../../com.aspose.pdf/columninfo) | ColumnInfo value |

### setFirstParagraphInColumn(boolean value) {#setFirstParagraphInColumn-boolean-}
```
public void setFirstParagraphInColumn(boolean value)
```


Gets or sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Sets a float value that indicates the height of the floating box.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | value that indicates the height. |

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```


Sets a horizontal alignment of paragraph

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | HorizontalAlignment value |

### setHyperlink(Hyperlink value) {#setHyperlink-com.aspose.pdf.Hyperlink-}
```
public void setHyperlink(Hyperlink value)
```


Sets hyperlink(for pdf generator).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Hyperlink](../../com.aspose.pdf/hyperlink) | hyperlink(for pdf generator). |

### setInLineParagraph(boolean value) {#setInLineParagraph-boolean-}
```
public void setInLineParagraph(boolean value)
```


Sets a paragraph is inline. Default is false.(for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setInNewPage(boolean value) {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```


Sets a boolean value that force this paragraph generates at new page. Default is false.(for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setKeptWithNext(boolean value) {#setKeptWithNext-boolean-}
```
public final void setKeptWithNext(boolean value)
```


Sets a boolean value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setLeft(double value) {#setLeft-double-}
```
public void setLeft(double value)
```


Sets the table left coordinate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | table left coordinate. |

### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public void setMargin(MarginInfo value)
```


Sets a outer margin for paragraph (for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo object |

### setNeedRepeating(boolean value) {#setNeedRepeating-boolean-}
```
public void setNeedRepeating(boolean value)
```


Sets a boolean value that indicates whether the paragraph need to be repeated on next page. Default value is true.The attribute is only valid when the paragraph itself and the object its ReferenceParagraphID referred to both are included in RepeatingRows.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setPadding(MarginInfo value) {#setPadding-com.aspose.pdf.MarginInfo-}
```
public void setPadding(MarginInfo value)
```


Sets a object that indicates the padding of the floating box.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | object that indicates the padding. |

### setParagraphs(Paragraphs value) {#setParagraphs-com.aspose.pdf.Paragraphs-}
```
public void setParagraphs(Paragraphs value)
```


Sets a collection that indicates all paragraphs in the cell.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Paragraphs](../../com.aspose.pdf/paragraphs) | collection that indicates all paragraphs. |

### setTop(double value) {#setTop-double-}
```
public void setTop(double value)
```


Sets the table top coordinate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | table top coordinate. |

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int value)
```


Sets a vertical alignment of paragraph

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | VerticalAlignment element |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Sets a float value that indicates the width of the floating box.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### setZIndex(int value) {#setZIndex-int-}
```
public void setZIndex(int value)
```


Sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

