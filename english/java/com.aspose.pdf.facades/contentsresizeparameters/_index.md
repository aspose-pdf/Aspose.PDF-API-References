---
title: IPdfFileEditor.ContentsResizeParameters
second_title: Aspose.PDF for Java API Reference
description: Class for specifing page resize parameters.
type: docs
weight: 10
url: /java/com.aspose.pdf.facades/ipdffileeditor.contentsresizeparameters/
---
**Inheritance:**
java.lang.Object
```
public static class IPdfFileEditor.ContentsResizeParameters
```

Class for specifing page resize parameters. Allow to set the following parameters: Size of result page (width, height) in default space units or in percents of initial pages size; Left, Top, Bottom and Right margins in default space units or in percents of initial page size; Some values may be left null for automatic calculation. These values will be calculated from rest of page size after calculation explicitly specified values. For example: if page width = 100 and new page width specified 60 units then left and right margins are automatically calculated: (100 - 60) / 2 = 15. This class is used in ResizeContents method.
## Constructors

| Constructor | Description |
| --- | --- |
| [ContentsResizeParameters()](#ContentsResizeParameters--) | Creates resize parameters where al values are set to "auto". |
| [ContentsResizeParameters(IPdfFileEditor.ContentsResizeValue leftMargin, IPdfFileEditor.ContentsResizeValue contentsWidth, IPdfFileEditor.ContentsResizeValue rightMargin, IPdfFileEditor.ContentsResizeValue topMargin, IPdfFileEditor.ContentsResizeValue contentsHeight, IPdfFileEditor.ContentsResizeValue bottomMargin)](#ContentsResizeParameters-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Creates resize parameters with specified margin values and contents size. |
## Methods

| Method | Description |
| --- | --- |
| [contentSize(double width, double height)](#contentSize-double-double-) | Creates resize parameters with specified contents size. |
| [contentSizePercent(double width, double height)](#contentSizePercent-double-double-) | Creates resize parameters with specified conets size in percents of initial page size. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBottomMargin()](#getBottomMargin--) | Gets or sets bottom margin on the resultant page. |
| [getClass()](#getClass--) |  |
| [getContentsHeight()](#getContentsHeight--) | Gets or sets height of the content of the source page on the resultant page. |
| [getContentsWidth()](#getContentsWidth--) | Gets or sets width of the content of the source page on the resultant page. |
| [getLeftMargin()](#getLeftMargin--) | Gets or sets left margin on the resultant page. |
| [getRightMargin()](#getRightMargin--) | Gets or sets right margin on the resultant page. |
| [getTopMargin()](#getTopMargin--) | Gets or sets top margin on the resultant page. |
| [hashCode()](#hashCode--) |  |
| [margins(double left, double right, double top, double bottom)](#margins-double-double-double-double-) | Creates resize parameters with specifed margins value. |
| [marginsPercent(double left, double right, double top, double bottom)](#marginsPercent-double-double-double-double-) | Creates resize parameters. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [pageResize(double width, double height)](#pageResize-double-double-) | Creates resize paramters for page resize. |
| [pageResizePct(double widthPct, double heightPct)](#pageResizePct-double-double-) | Creates resize paramters for page resize. |
| [setBottomMargin(IPdfFileEditor.ContentsResizeValue value)](#setBottomMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Gets or sets bottom margin on the resultant page. |
| [setContentsHeight(IPdfFileEditor.ContentsResizeValue value)](#setContentsHeight-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Gets or sets height of the content of the source page on the resultant page. |
| [setContentsWidth(IPdfFileEditor.ContentsResizeValue value)](#setContentsWidth-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Gets or sets width of the content of the source page on the resultant page. |
| [setLeftMargin(IPdfFileEditor.ContentsResizeValue value)](#setLeftMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Gets or sets left margin on the resultant page. |
| [setRightMargin(IPdfFileEditor.ContentsResizeValue value)](#setRightMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Gets or sets right margin on the resultant page. |
| [setTopMargin(IPdfFileEditor.ContentsResizeValue value)](#setTopMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Gets or sets top margin on the resultant page. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ContentsResizeParameters() {#ContentsResizeParameters--}
```
public ContentsResizeParameters()
```


Creates resize parameters where al values are set to "auto". Later margins and contents size may be specified if required.

### ContentsResizeParameters(IPdfFileEditor.ContentsResizeValue leftMargin, IPdfFileEditor.ContentsResizeValue contentsWidth, IPdfFileEditor.ContentsResizeValue rightMargin, IPdfFileEditor.ContentsResizeValue topMargin, IPdfFileEditor.ContentsResizeValue contentsHeight, IPdfFileEditor.ContentsResizeValue bottomMargin) {#ContentsResizeParameters-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
```
public ContentsResizeParameters(IPdfFileEditor.ContentsResizeValue leftMargin, IPdfFileEditor.ContentsResizeValue contentsWidth, IPdfFileEditor.ContentsResizeValue rightMargin, IPdfFileEditor.ContentsResizeValue topMargin, IPdfFileEditor.ContentsResizeValue contentsHeight, IPdfFileEditor.ContentsResizeValue bottomMargin)
```


Creates resize parameters with specified margin values and contents size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| leftMargin | [ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) | Left margin value. |
| contentsWidth | [ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) | Contents width. |
| rightMargin | [ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) | Right margin. |
| topMargin | [ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) | Top margin. |
| contentsHeight | [ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) | Contents height. |
| bottomMargin | [ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) | Bottom margin. |

### contentSize(double width, double height) {#contentSize-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters contentSize(double width, double height)
```


Creates resize parameters with specified contents size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | double | New width of contents. |
| height | double | New height of contetns. |

**Returns:**
[ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) - Returns new resize parameters.
### contentSizePercent(double width, double height) {#contentSizePercent-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters contentSizePercent(double width, double height)
```


Creates resize parameters with specified conets size in percents of initial page size. Margins are caculated automatically.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | double | New content width in percents. |
| height | double | New contents height in percents. |

**Returns:**
[ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) - New resize parameters.
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
### getBottomMargin() {#getBottomMargin--}
```
public IPdfFileEditor.ContentsResizeValue getBottomMargin()
```


Gets or sets bottom margin on the resultant page.

**Returns:**
[ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) - ContentsResizeValue object
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContentsHeight() {#getContentsHeight--}
```
public IPdfFileEditor.ContentsResizeValue getContentsHeight()
```


Gets or sets height of the content of the source page on the resultant page.

**Returns:**
[ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) - ContentsResizeValue object
### getContentsWidth() {#getContentsWidth--}
```
public IPdfFileEditor.ContentsResizeValue getContentsWidth()
```


Gets or sets width of the content of the source page on the resultant page.

**Returns:**
[ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) - ContentsResizeValue object
### getLeftMargin() {#getLeftMargin--}
```
public IPdfFileEditor.ContentsResizeValue getLeftMargin()
```


Gets or sets left margin on the resultant page.

**Returns:**
[ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) - ContentsResizeValue object
### getRightMargin() {#getRightMargin--}
```
public IPdfFileEditor.ContentsResizeValue getRightMargin()
```


Gets or sets right margin on the resultant page.

**Returns:**
[ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) - ContentsResizeValue object
### getTopMargin() {#getTopMargin--}
```
public IPdfFileEditor.ContentsResizeValue getTopMargin()
```


Gets or sets top margin on the resultant page.

**Returns:**
[ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) - ContentsResizeValue object
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### margins(double left, double right, double top, double bottom) {#margins-double-double-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters margins(double left, double right, double top, double bottom)
```


Creates resize parameters with specifed margins value. Contents size is automatically calculated.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | double | Left margin. |
| right | double | Right margin. |
| top | double | Top margin. |
| bottom | double | Bottom margin. |

**Returns:**
[ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) - Created resize parameters.
### marginsPercent(double left, double right, double top, double bottom) {#marginsPercent-double-double-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters marginsPercent(double left, double right, double top, double bottom)
```


Creates resize parameters. Margins are specified in percents of initial page size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | double | Left margin (in percents of page width). |
| right | double | Right margin (in percents of page height). |
| top | double | Top margin (in percents of page height). |
| bottom | double | Bottom margin (in percents of page height). |

**Returns:**
[ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) - Returns new resize parameters.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### pageResize(double width, double height) {#pageResize-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters pageResize(double width, double height)
```


Creates resize paramters for page resize.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | double | New page width in units. |
| height | double | New page height in units. |

**Returns:**
[ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) - New resize paramteres.
### pageResizePct(double widthPct, double heightPct) {#pageResizePct-double-double-}
```
public IPdfFileEditor.ContentsResizeParameters pageResizePct(double widthPct, double heightPct)
```


Creates resize paramters for page resize. New sizes are specified in percent.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| widthPct | double | New page width in percents. |
| heightPct | double | New page height in percents. |

**Returns:**
[ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) - New resize paramteres.
### setBottomMargin(IPdfFileEditor.ContentsResizeValue value) {#setBottomMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
```
public void setBottomMargin(IPdfFileEditor.ContentsResizeValue value)
```


Gets or sets bottom margin on the resultant page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) | ContentsResizeValue object |

### setContentsHeight(IPdfFileEditor.ContentsResizeValue value) {#setContentsHeight-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
```
public void setContentsHeight(IPdfFileEditor.ContentsResizeValue value)
```


Gets or sets height of the content of the source page on the resultant page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) | ContentsResizeValue object |

### setContentsWidth(IPdfFileEditor.ContentsResizeValue value) {#setContentsWidth-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
```
public void setContentsWidth(IPdfFileEditor.ContentsResizeValue value)
```


Gets or sets width of the content of the source page on the resultant page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) | ContentsResizeValue object |

### setLeftMargin(IPdfFileEditor.ContentsResizeValue value) {#setLeftMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
```
public void setLeftMargin(IPdfFileEditor.ContentsResizeValue value)
```


Gets or sets left margin on the resultant page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) | ContentsResizeValue object |

### setRightMargin(IPdfFileEditor.ContentsResizeValue value) {#setRightMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
```
public void setRightMargin(IPdfFileEditor.ContentsResizeValue value)
```


Gets or sets right margin on the resultant page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) | ContentsResizeValue object |

### setTopMargin(IPdfFileEditor.ContentsResizeValue value) {#setTopMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
```
public void setTopMargin(IPdfFileEditor.ContentsResizeValue value)
```


Gets or sets top margin on the resultant page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) | ContentsResizeValue object |

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

