---
title: Table
second_title: Aspose.PDF for Java API Reference
description: Represents a table that can be added to the page.
type: docs
weight: 352
url: /java/com.aspose.pdf/table/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph)
```
public final class Table extends BaseParagraph
```

Represents a table that can be added to the page.
## Constructors

| Constructor | Description |
| --- | --- |
| [Table()](#Table--) | Default ctor |
## Methods

| Method | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Clone the table. |
| [drawRoundedRectangle(GraphInfo info, Point topLeft, Point rightBottom, List<Operator> operators, double radius)](#drawRoundedRectangle-com.aspose.pdf.GraphInfo-com.aspose.pdf.Point-com.aspose.pdf.Point-java.util.List-com.aspose.pdf.Operator--double-) | Add operators for rectangle. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Gets the table alignment. |
| [getBackgroundColor()](#getBackgroundColor--) | Gets table background color |
| [getBorder()](#getBorder--) | Gets the border. |
| [getBreakText()](#getBreakText--) | Gets break text for table |
| [getBroken()](#getBroken--) | Gets or sets table vertial broken; |
| [getClass()](#getClass--) |  |
| [getColumnAdjustment()](#getColumnAdjustment--) | Gets the table column adjustment. |
| [getColumnWidth(String stringColumnWidth)](#getColumnWidth-java.lang.String-) | Get column width |
| [getColumnWidths()](#getColumnWidths--) | Gets the column widths of the table. |
| [getCornerStyle()](#getCornerStyle--) | Gets the styles of the border corners |
| [getDefaultCellBorder()](#getDefaultCellBorder--) | Gets default cell border; |
| [getDefaultCellPadding()](#getDefaultCellPadding--) | Gets the default cell padding. |
| [getDefaultCellTextState()](#getDefaultCellTextState--) | Gets the default cell text state. |
| [getDefaultColumnWidth()](#getDefaultColumnWidth--) | Gets default cell border; |
| [getHeight()](#getHeight--) | Get height. |
| [getHeight(Page parentPage)](#getHeight-com.aspose.pdf.Page-) | Get height. |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Gets a horizontal alignment of paragraph |
| [getHyperlink()](#getHyperlink--) | Gets the fragment hyperlink(for pdf generator). |
| [getLeft()](#getLeft--) | Gets the table left coordinate. |
| [getMargin()](#getMargin--) | Gets a outer margin for paragraph (for pdf generation) |
| [getRepeatingColumnsCount()](#getRepeatingColumnsCount--) | Gets or sets the maximum columns count for table |
| [getRepeatingRowsCount()](#getRepeatingRowsCount--) | Gets the first rows count repeated for several pages |
| [getRepeatingRowsStyle()](#getRepeatingRowsStyle--) | Gets the style for repeating rows |
| [getRows()](#getRows--) | Gets the rows of the table. |
| [getTop()](#getTop--) | Gets the table top coordinate. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Gets a vertical alignment of paragraph |
| [getWidth()](#getWidth--) | Get width. |
| [getZIndex()](#getZIndex--) | Gets an int value that indicates the Z-order of the graph. |
| [hashCode()](#hashCode--) |  |
| [isBordersIncluded()](#isBordersIncluded--) | Gets border included in column widths. |
| [isBroken()](#isBroken--) | Gets the table is broken - will be truncated for next page. |
| [isFirstParagraphInColumn()](#isFirstParagraphInColumn--) | Gets or sets a bool value that indicates whether this paragraph will be at next column. |
| [isInLineParagraph()](#isInLineParagraph--) | Gets a paragraph is inline. |
| [isInNewPage()](#isInNewPage--) | Gets a bool value that force this paragraph generates at new page. |
| [isKeptWithNext()](#isKeptWithNext--) | Gets a boolean value that indicates whether current paragraph remains in the same page along with next paragraph. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(int value)](#setAlignment-int-) | Sets the table alignment. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | Sets table background color |
| [setBorder(BorderInfo value)](#setBorder-com.aspose.pdf.BorderInfo-) | Sets the border. |
| [setBordersIncluded(boolean value)](#setBordersIncluded-boolean-) | Sets border included in column widths. |
| [setBreakText(TextFragment value)](#setBreakText-com.aspose.pdf.TextFragment-) | Sets break text for table |
| [setBroken(boolean value)](#setBroken-boolean-) | Sets the table is broken - will be truncated for next page. |
| [setBroken(int value)](#setBroken-int-) | Gets or sets table vertial broken; |
| [setColumnAdjustment(int value)](#setColumnAdjustment-int-) | Sets the table column adjustment. |
| [setColumnTextState(int colNumber, TextState textState)](#setColumnTextState-int-com.aspose.pdf.TextState-) | Set height. |
| [setColumnWidths(String value)](#setColumnWidths-java.lang.String-) | Gets the column widths of the table. |
| [setCornerStyle(int value)](#setCornerStyle-int-) | Gets or sets the styles of the border corners |
| [setDefaultCellBorder(BorderInfo value)](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Gets default cell border; |
| [setDefaultCellPadding(MarginInfo value)](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Sets the default cell padding. |
| [setDefaultCellTextState(TextState value)](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Sets the default cell text state. |
| [setDefaultColumnWidth(String value)](#setDefaultColumnWidth-java.lang.String-) | Gets default cell border; |
| [setFirstParagraphInColumn(boolean value)](#setFirstParagraphInColumn-boolean-) | Gets or sets a bool value that indicates whether this paragraph will be at next column. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Sets a horizontal alignment of paragraph |
| [setHyperlink(Hyperlink value)](#setHyperlink-com.aspose.pdf.Hyperlink-) | Sets hyperlink(for pdf generator). |
| [setInLineParagraph(boolean value)](#setInLineParagraph-boolean-) | Sets a paragraph is inline. |
| [setInNewPage(boolean value)](#setInNewPage-boolean-) | Sets a boolean value that force this paragraph generates at new page. |
| [setKeptWithNext(boolean value)](#setKeptWithNext-boolean-) | Sets a boolean value that indicates whether current paragraph remains in the same page along with next paragraph. |
| [setLeft(float value)](#setLeft-float-) | Sets the table left coordinate. |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | Sets a outer margin for paragraph (for pdf generation) |
| [setRepeatingColumnsCount(int value)](#setRepeatingColumnsCount-int-) | Gets or sets the maximum columns count for table |
| [setRepeatingRowsCount(int value)](#setRepeatingRowsCount-int-) | Gets the first rows count repeated for several pages |
| [setRepeatingRowsStyle(TextState value)](#setRepeatingRowsStyle-com.aspose.pdf.TextState-) | Gets the style for repeating rows |
| [setTop(float value)](#setTop-float-) | Sets the table top coordinate. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Sets a vertical alignment of paragraph |
| [setZIndex(int value)](#setZIndex-int-) | Sets a int value that indicates the Z-order of the graph. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Table() {#Table--}
```
public Table()
```


Default ctor

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clone the table.

**Returns:**
java.lang.Object - The cloned object
### drawRoundedRectangle(GraphInfo info, Point topLeft, Point rightBottom, List<Operator> operators, double radius) {#drawRoundedRectangle-com.aspose.pdf.GraphInfo-com.aspose.pdf.Point-com.aspose.pdf.Point-java.util.List-com.aspose.pdf.Operator--double-}
```
public static void drawRoundedRectangle(GraphInfo info, Point topLeft, Point rightBottom, List<Operator> operators, double radius)
```


Add operators for rectangle.

For internal usage only.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| info | [GraphInfo](../../com.aspose.pdf/graphinfo) | The border style. |
| topLeft | [Point](../../com.aspose.pdf/point) | The left top point. |
| rightBottom | [Point](../../com.aspose.pdf/point) | The right bottom point. |
| operators | java.util.List<com.aspose.pdf.Operator> | The operators list to be added into the page's content. |
| radius | double | The border radius. |

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
### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```


Gets the table alignment.

**Returns:**
int - HorizontalAlignment value
### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


Gets table background color

**Returns:**
[Color](../../com.aspose.pdf/color) - Color object
### getBorder() {#getBorder--}
```
public final BorderInfo getBorder()
```


Gets the border.

**Returns:**
[BorderInfo](../../com.aspose.pdf/borderinfo) - BorderInfo object
### getBreakText() {#getBreakText--}
```
public final TextFragment getBreakText()
```


Gets break text for table

**Returns:**
[TextFragment](../../com.aspose.pdf/textfragment) - TextFragment object
### getBroken() {#getBroken--}
```
public final int getBroken()
```


Gets or sets table vertial broken;

**Returns:**
int - TableBroken value
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColumnAdjustment() {#getColumnAdjustment--}
```
public final int getColumnAdjustment()
```


Gets the table column adjustment.

**Returns:**
int - ColumnAdjustment value
### getColumnWidth(String stringColumnWidth) {#getColumnWidth-java.lang.String-}
```
public static double getColumnWidth(String stringColumnWidth)
```


Get column width

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stringColumnWidth | java.lang.String | The string representation. |

**Returns:**
double - double value
### getColumnWidths() {#getColumnWidths--}
```
public final String getColumnWidths()
```


Gets the column widths of the table.

**Returns:**
java.lang.String - String value
### getCornerStyle() {#getCornerStyle--}
```
public final int getCornerStyle()
```


Gets the styles of the border corners

**Returns:**
int - BorderCornerStyle value
### getDefaultCellBorder() {#getDefaultCellBorder--}
```
public final BorderInfo getDefaultCellBorder()
```


Gets default cell border;

**Returns:**
[BorderInfo](../../com.aspose.pdf/borderinfo) - BorderInfo object
### getDefaultCellPadding() {#getDefaultCellPadding--}
```
public final MarginInfo getDefaultCellPadding()
```


Gets the default cell padding.

**Returns:**
[MarginInfo](../../com.aspose.pdf/margininfo) - MarginInfo object
### getDefaultCellTextState() {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```


Gets the default cell text state.

**Returns:**
[TextState](../../com.aspose.pdf/textstate) - TextState value
### getDefaultColumnWidth() {#getDefaultColumnWidth--}
```
public final String getDefaultColumnWidth()
```


Gets default cell border;

**Returns:**
java.lang.String - String object
### getHeight() {#getHeight--}
```
public double getHeight()
```


Get height.

**Returns:**
double - The table height
### getHeight(Page parentPage) {#getHeight-com.aspose.pdf.Page-}
```
public double getHeight(Page parentPage)
```


Get height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentPage | [Page](../../com.aspose.pdf/page) | The table's parent page |

**Returns:**
double - The table height
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
public final float getLeft()
```


Gets the table left coordinate.

**Returns:**
float - float value
### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


Gets a outer margin for paragraph (for pdf generation)

**Returns:**
[MarginInfo](../../com.aspose.pdf/margininfo) - MarginInfo value
### getRepeatingColumnsCount() {#getRepeatingColumnsCount--}
```
public final int getRepeatingColumnsCount()
```


Gets or sets the maximum columns count for table

**Returns:**
int - int value
### getRepeatingRowsCount() {#getRepeatingRowsCount--}
```
public final int getRepeatingRowsCount()
```


Gets the first rows count repeated for several pages

**Returns:**
int - int value
### getRepeatingRowsStyle() {#getRepeatingRowsStyle--}
```
public final TextState getRepeatingRowsStyle()
```


Gets the style for repeating rows

**Returns:**
[TextState](../../com.aspose.pdf/textstate) - TextState object
### getRows() {#getRows--}
```
public final Rows getRows()
```


Gets the rows of the table.

**Returns:**
[Rows](../../com.aspose.pdf/rows) - Rows object
### getTop() {#getTop--}
```
public final float getTop()
```


Gets the table top coordinate.

**Returns:**
float - float value
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


Get width.

**Returns:**
double - The table width
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
### isBordersIncluded() {#isBordersIncluded--}
```
public final boolean isBordersIncluded()
```


Gets border included in column widths.

**Returns:**
boolean - boolean value
### isBroken() {#isBroken--}
```
public final boolean isBroken()
```


Gets the table is broken - will be truncated for next page.

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




### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```


Sets the table alignment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | HorizontalAlignment value |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.pdf.Color-}
```
public final void setBackgroundColor(Color value)
```


Sets table background color

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Color object |

### setBorder(BorderInfo value) {#setBorder-com.aspose.pdf.BorderInfo-}
```
public final void setBorder(BorderInfo value)
```


Sets the border.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | BorderInfo object |

### setBordersIncluded(boolean value) {#setBordersIncluded-boolean-}
```
public final void setBordersIncluded(boolean value)
```


Sets border included in column widths.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setBreakText(TextFragment value) {#setBreakText-com.aspose.pdf.TextFragment-}
```
public final void setBreakText(TextFragment value)
```


Sets break text for table

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextFragment](../../com.aspose.pdf/textfragment) | TextFragment object |

### setBroken(boolean value) {#setBroken-boolean-}
```
public final void setBroken(boolean value)
```


Sets the table is broken - will be truncated for next page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setBroken(int value) {#setBroken-int-}
```
public final void setBroken(int value)
```


Gets or sets table vertial broken;

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | TableBroken value |

### setColumnAdjustment(int value) {#setColumnAdjustment-int-}
```
public final void setColumnAdjustment(int value)
```


Sets the table column adjustment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ColumnAdjustment value |

### setColumnTextState(int colNumber, TextState textState) {#setColumnTextState-int-com.aspose.pdf.TextState-}
```
public void setColumnTextState(int colNumber, TextState textState)
```


Set height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| colNumber | int | The column number. |
| textState | [TextState](../../com.aspose.pdf/textstate) | The text state for column. |

### setColumnWidths(String value) {#setColumnWidths-java.lang.String-}
```
public final void setColumnWidths(String value)
```


Gets the column widths of the table.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setCornerStyle(int value) {#setCornerStyle-int-}
```
public final void setCornerStyle(int value)
```


Gets or sets the styles of the border corners

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | BorderCornerStyle value |

### setDefaultCellBorder(BorderInfo value) {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
```
public final void setDefaultCellBorder(BorderInfo value)
```


Gets default cell border;

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | BorderInfo object |

### setDefaultCellPadding(MarginInfo value) {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
```
public final void setDefaultCellPadding(MarginInfo value)
```


Sets the default cell padding.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo object |

### setDefaultCellTextState(TextState value) {#setDefaultCellTextState-com.aspose.pdf.TextState-}
```
public final void setDefaultCellTextState(TextState value)
```


Sets the default cell text state.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | TextState value |

### setDefaultColumnWidth(String value) {#setDefaultColumnWidth-java.lang.String-}
```
public final void setDefaultColumnWidth(String value)
```


Gets default cell border;

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String object |

### setFirstParagraphInColumn(boolean value) {#setFirstParagraphInColumn-boolean-}
```
public void setFirstParagraphInColumn(boolean value)
```


Gets or sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

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

### setLeft(float value) {#setLeft-float-}
```
public final void setLeft(float value)
```


Sets the table left coordinate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | float value |

### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public void setMargin(MarginInfo value)
```


Sets a outer margin for paragraph (for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo object |

### setRepeatingColumnsCount(int value) {#setRepeatingColumnsCount-int-}
```
public final void setRepeatingColumnsCount(int value)
```


Gets or sets the maximum columns count for table

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setRepeatingRowsCount(int value) {#setRepeatingRowsCount-int-}
```
public final void setRepeatingRowsCount(int value)
```


Gets the first rows count repeated for several pages

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setRepeatingRowsStyle(TextState value) {#setRepeatingRowsStyle-com.aspose.pdf.TextState-}
```
public final void setRepeatingRowsStyle(TextState value)
```


Gets the style for repeating rows

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | TextState object |

### setTop(float value) {#setTop-float-}
```
public final void setTop(float value)
```


Sets the table top coordinate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | float value |

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int value)
```


Sets a vertical alignment of paragraph

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | VerticalAlignment element |

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

