---
title: Graph
second_title: Aspose.PDF for Java API Reference
description: Represents graph - graphics generator paragraph.
type: docs
weight: 16
url: /java/com.aspose.pdf.drawing/graph/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph)
```
public final class Graph extends BaseParagraph
```

Represents graph - graphics generator paragraph.
## Constructors

| Constructor | Description |
| --- | --- |
| [Graph()](#Graph--) | For Internal usage only |
| [Graph(float width, float height)](#Graph-float-float-) | Initializes a new instance of the  Graph  class. |
## Methods

| Method | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Clone the graph. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBorder()](#getBorder--) | Gets the border. |
| [getClass()](#getClass--) |  |
| [getGraphInfo()](#getGraphInfo--) | Gets a  GraphInfo  object that indicates the graph info,such as color, line width,etc. |
| [getHeight()](#getHeight--) | Gets float value that indicates the graph height. |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Gets a horizontal alignment of paragraph |
| [getHyperlink()](#getHyperlink--) | Gets the fragment hyperlink(for pdf generator). |
| [getLeft()](#getLeft--) | Gets table left coordinate. |
| [getMargin()](#getMargin--) | Gets a outer margin for paragraph (for pdf generation) |
| [getShapes()](#getShapes--) | Gets a  Shapes  collection that indicates all shapes in the graph. |
| [getTitle()](#getTitle--) | Gets string value that indicates the title of the graph. |
| [getTop()](#getTop--) | Gets the table top coordinate. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Gets a vertical alignment of paragraph |
| [getWidth()](#getWidth--) | Gets float value that indicates the graph width. |
| [getZIndex()](#getZIndex--) | Gets an int value that indicates the Z-order of the graph. |
| [hashCode()](#hashCode--) |  |
| [isChangePosition()](#isChangePosition--) | Gets change current position after process paragraph. |
| [isFirstParagraphInColumn()](#isFirstParagraphInColumn--) | Gets or sets a bool value that indicates whether this paragraph will be at next column. |
| [isInLineParagraph()](#isInLineParagraph--) | Gets a paragraph is inline. |
| [isInNewPage()](#isInNewPage--) | Gets a bool value that force this paragraph generates at new page. |
| [isKeptWithNext()](#isKeptWithNext--) | Gets a boolean value that indicates whether current paragraph remains in the same page along with next paragraph. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBorder(BorderInfo value)](#setBorder-com.aspose.pdf.BorderInfo-) | Sets the border. |
| [setChangePosition(boolean value)](#setChangePosition-boolean-) | Sets change current position after process paragraph. |
| [setFirstParagraphInColumn(boolean value)](#setFirstParagraphInColumn-boolean-) | Gets or sets a bool value that indicates whether this paragraph will be at next column. |
| [setGraphInfo(GraphInfo value)](#setGraphInfo-com.aspose.pdf.GraphInfo-) | Gets or sets a  GraphInfo  object that indicates the graph info,such as color, line width,etc. |
| [setHeight(double value)](#setHeight-double-) | Sets float value that indicates the graph height. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Sets a horizontal alignment of paragraph |
| [setHyperlink(Hyperlink value)](#setHyperlink-com.aspose.pdf.Hyperlink-) | Sets hyperlink(for pdf generator). |
| [setInLineParagraph(boolean value)](#setInLineParagraph-boolean-) | Sets a paragraph is inline. |
| [setInNewPage(boolean value)](#setInNewPage-boolean-) | Sets a boolean value that force this paragraph generates at new page. |
| [setKeptWithNext(boolean value)](#setKeptWithNext-boolean-) | Sets a boolean value that indicates whether current paragraph remains in the same page along with next paragraph. |
| [setLeft(double value)](#setLeft-double-) | Sets table left coordinate. |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | Sets a outer margin for paragraph (for pdf generation) |
| [setShapes(List<Shape> value)](#setShapes-java.util.List-com.aspose.pdf.drawing.Shape--) | Sets a  Shapes  collection that indicates all shapes in the graph. |
| [setTitle(TextFragment value)](#setTitle-com.aspose.pdf.TextFragment-) | Sets string value that indicates the title of the graph. |
| [setTop(double value)](#setTop-double-) | Sets the table top coordinate. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Sets a vertical alignment of paragraph |
| [setWidth(double value)](#setWidth-double-) | Sets float value that indicates the graph width. |
| [setZIndex(int value)](#setZIndex-int-) | Sets a int value that indicates the Z-order of the graph. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Graph() {#Graph--}
```
public Graph()
```


For Internal usage only

### Graph(float width, float height) {#Graph-float-float-}
```
public Graph(float width, float height)
```


Initializes a new instance of the  Graph  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | float | The width of the graph. |
| height | float | The height of the graph. |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clone the graph.

**Returns:**
java.lang.Object - The cloned object
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
### getBorder() {#getBorder--}
```
public BorderInfo getBorder()
```


Gets the border.

**Returns:**
[BorderInfo](../../com.aspose.pdf/borderinfo) - BorderInfo element
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getGraphInfo() {#getGraphInfo--}
```
public GraphInfo getGraphInfo()
```


Gets a  GraphInfo  object that indicates the graph info,such as color, line width,etc.

**Returns:**
[GraphInfo](../../com.aspose.pdf/graphinfo) - GraphInfo object
### getHeight() {#getHeight--}
```
public double getHeight()
```


Gets float value that indicates the graph height. The unit is point. In XML,the default unit is point,but cm and inch are also supported. For example,GraphHeight="10cm" or GraphHeight="5inch".

**Returns:**
double - value that indicates the graph height.
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


Gets table left coordinate.

**Returns:**
double - table left coordinate.
### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


Gets a outer margin for paragraph (for pdf generation)

**Returns:**
[MarginInfo](../../com.aspose.pdf/margininfo) - MarginInfo value
### getShapes() {#getShapes--}
```
public List<Shape> getShapes()
```


Gets a  Shapes  collection that indicates all shapes in the graph.

**Returns:**
java.util.List<com.aspose.pdf.drawing.Shape> - List of Shape elements
### getTitle() {#getTitle--}
```
public TextFragment getTitle()
```


Gets string value that indicates the title of the graph.

**Returns:**
[TextFragment](../../com.aspose.pdf/textfragment) - title of the graph.
### getTop() {#getTop--}
```
public double getTop()
```


Gets the table top coordinate.

**Returns:**
double - the table top coordinate.
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


Gets float value that indicates the graph width. The unit is point. In XML,the default unit is point,but cm and inch are also supported. For example,GraphWidth="10cm" or GraphWidth="5inch".

**Returns:**
double - float value that indicates the graph width.
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
### isChangePosition() {#isChangePosition--}
```
public boolean isChangePosition()
```


Gets change current position after process paragraph.(default true)

**Returns:**
boolean - boolean value
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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBorder(BorderInfo value) {#setBorder-com.aspose.pdf.BorderInfo-}
```
public void setBorder(BorderInfo value)
```


Sets the border.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | BorderInfo element |

### setChangePosition(boolean value) {#setChangePosition-boolean-}
```
public void setChangePosition(boolean value)
```


Sets change current position after process paragraph.(default true)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setFirstParagraphInColumn(boolean value) {#setFirstParagraphInColumn-boolean-}
```
public void setFirstParagraphInColumn(boolean value)
```


Gets or sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setGraphInfo(GraphInfo value) {#setGraphInfo-com.aspose.pdf.GraphInfo-}
```
public void setGraphInfo(GraphInfo value)
```


Gets or sets a  GraphInfo  object that indicates the graph info,such as color, line width,etc.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [GraphInfo](../../com.aspose.pdf/graphinfo) | GraphInfo object |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Sets float value that indicates the graph height. The unit is point. In XML,the default unit is point,but cm and inch are also supported. For example,GraphHeight="10cm" or GraphHeight="5inch".

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | that indicates the graph height. |

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


Sets table left coordinate.

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

### setShapes(List<Shape> value) {#setShapes-java.util.List-com.aspose.pdf.drawing.Shape--}
```
public void setShapes(List<Shape> value)
```


Sets a  Shapes  collection that indicates all shapes in the graph.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.List<com.aspose.pdf.drawing.Shape> | List of Shape elements |

### setTitle(TextFragment value) {#setTitle-com.aspose.pdf.TextFragment-}
```
public void setTitle(TextFragment value)
```


Sets string value that indicates the title of the graph.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextFragment](../../com.aspose.pdf/textfragment) | title of the graph. |

### setTop(double value) {#setTop-double-}
```
public void setTop(double value)
```


Sets the table top coordinate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | the table top coordinate. |

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


Sets float value that indicates the graph width. The unit is point. In XML,the default unit is point,but cm and inch are also supported. For example,GraphWidth="10cm" or GraphWidth="5inch".

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | float value that indicates the graph width. |

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

