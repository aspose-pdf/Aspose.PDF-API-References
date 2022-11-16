---
title: IPdfFileEditor.ContentsResizeParameters
second_title: 用于 Java API 参考的 Aspose.PDF
description: 用于指定页面大小调整参数的类。
type: docs
weight: 10
url: /zh/java/com.aspose.pdf.facades/ipdffileeditor.contentsresizeparameters/
---
**遗产：**
java.lang.Object
```
public static class IPdfFileEditor.ContentsResizeParameters
```

用于指定页面大小调整参数的类。允许设置以下参数：结果页面的大小（宽度、高度），以默认空间单位或初始页面大小的百分比表示；默认空间单位或初始页面大小百分比的左、上、下和右页边距；某些值可能会留空以进行自动计算。这些值将在计算明确指定的值后根据其余页面大小计算。例如：如果页面宽度 = 100 并且新页面宽度指定为 60 个单位，则自动计算左右边距：(100 - 60) / 2 = 15。此类在 ResizeContents 方法中使用。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ContentsResizeParameters()](#ContentsResizeParameters--) | 创建调整大小参数，其中 al 值设置为“自动”。 |
| [ContentsResizeParameters(IPdfFileEditor.ContentsResizeValue leftMargin, IPdfFileEditor.ContentsResizeValue contentsWidth, IPdfFileEditor.ContentsResizeValue rightMargin, IPdfFileEditor.ContentsResizeValue topMargin, IPdfFileEditor.ContentsResizeValue contentsHeight, IPdfFileEditor.ContentsResizeValue bottomMargin)](#ContentsResizeParameters-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | 创建具有指定边距值和内容大小的调整大小参数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [contentSize(double width, double height)](#contentSize-double-double-) | 创建具有指定内容大小的调整大小参数。 |
| [contentSizePercent(double width, double height)](#contentSizePercent-double-double-) | 创建具有以初始页面大小的百分比指定的 conets 大小的调整大小参数。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBottomMargin()](#getBottomMargin--) | 获取或设置结果页面的下边距。 |
| [getClass()](#getClass--) |  |
| [getContentsHeight()](#getContentsHeight--) | 获取或设置结果页面上源页面内容的高度。 |
| [getContentsWidth()](#getContentsWidth--) | 获取或设置结果页面上源页面内容的宽度。 |
| [getLeftMargin()](#getLeftMargin--) | 获取或设置结果页面的左边距。 |
| [getRightMargin()](#getRightMargin--) | 获取或设置结果页面的右边距。 |
| [getTopMargin()](#getTopMargin--) | 获取或设置结果页面的上边距。 |
| [hashCode()](#hashCode--) |  |
| [margins(double left, double right, double top, double bottom)](#margins-double-double-double-double-) | 创建具有指定边距值的调整大小参数。 |
| [marginsPercent(double left, double right, double top, double bottom)](#marginsPercent-double-double-double-double-) | 创建调整大小参数。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [pageResize(double width, double height)](#pageResize-double-double-) | 为页面调整大小创建调整大小参数。 |
| [pageResizePct(double widthPct, double heightPct)](#pageResizePct-double-double-) | 为页面调整大小创建调整大小参数。 |
| [setBottomMargin(IPdfFileEditor.ContentsResizeValue value)](#setBottomMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | 获取或设置结果页面的下边距。 |
| [setContentsHeight(IPdfFileEditor.ContentsResizeValue value)](#setContentsHeight-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | 获取或设置结果页面上源页面内容的高度。 |
| [setContentsWidth(IPdfFileEditor.ContentsResizeValue value)](#setContentsWidth-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | 获取或设置结果页面上源页面内容的宽度。 |
| [setLeftMargin(IPdfFileEditor.ContentsResizeValue value)](#setLeftMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | 获取或设置结果页面的左边距。 |
| [setRightMargin(IPdfFileEditor.ContentsResizeValue value)](#setRightMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | 获取或设置结果页面的右边距。 |
| [setTopMargin(IPdfFileEditor.ContentsResizeValue value)](#setTopMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | 获取或设置结果页面的上边距。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ContentsResizeParameters() {#ContentsResizeParameters--}
```
public ContentsResizeParameters()
```


创建调整大小参数，其中 al 值设置为“自动”。如果需要，可以指定后面的边距和内容大小。

### ContentsResizeParameters(IPdfFileEditor.ContentsResizeValue leftMargin, IPdfFileEditor.ContentsResizeValue contentsWidth, IPdfFileEditor.ContentsResizeValue rightMargin, IPdfFileEditor.ContentsResizeValue topMargin, IPdfFileEditor.ContentsResizeValue contentsHeight, IPdfFileEditor.ContentsResizeValue bottomMargin) {#ContentsResizeParameters-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
```
public ContentsResizeParameters(IPdfFileEditor.ContentsResizeValue leftMargin, IPdfFileEditor.ContentsResizeValue contentsWidth, IPdfFileEditor.ContentsResizeValue rightMargin, IPdfFileEditor.ContentsResizeValue topMargin, IPdfFileEditor.ContentsResizeValue contentsHeight, IPdfFileEditor.ContentsResizeValue bottomMargin)
```


创建具有指定边距值和内容大小的调整大小参数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| leftMargin | [ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) | 左边距值。 |
| contentsWidth | [ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) | 内容宽度。 |
| rightMargin | [ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) | 右边距。 |
| topMargin | [ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) | 上边距。 |
| contentsHeight | [ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) | 内容高度。 |
| bottomMargin | [ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) | 底边距。 |

### contentSize(double width, double height) {#contentSize-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters contentSize(double width, double height)
```


创建具有指定内容大小的调整大小参数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| width | double | 内容的新宽度。 |
| height | double | 内容新高度。 |

**退货：**
[ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) - 返回新的调整大小参数。
### contentSizePercent(double width, double height) {#contentSizePercent-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters contentSizePercent(double width, double height)
```


创建具有以初始页面大小的百分比指定的 conets 大小的调整大小参数。保证金是自动计算的。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| width | double | 以百分比表示的新内容宽度。 |
| height | double | 以百分比表示的新内容高度。 |

**退货：**
[ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) - 新的调整大小参数。
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**退货：**
布尔值
### getBottomMargin() {#getBottomMargin--}
```
public IPdfFileEditor.ContentsResizeValue getBottomMargin()
```


获取或设置结果页面的下边距。

**退货：**
[ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) - ContentsResizeValue 对象
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getContentsHeight() {#getContentsHeight--}
```
public IPdfFileEditor.ContentsResizeValue getContentsHeight()
```


获取或设置结果页面上源页面内容的高度。

**退货：**
[ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) - ContentsResizeValue 对象
### getContentsWidth() {#getContentsWidth--}
```
public IPdfFileEditor.ContentsResizeValue getContentsWidth()
```


获取或设置结果页面上源页面内容的宽度。

**退货：**
[ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) - ContentsResizeValue 对象
### getLeftMargin() {#getLeftMargin--}
```
public IPdfFileEditor.ContentsResizeValue getLeftMargin()
```


获取或设置结果页面的左边距。

**退货：**
[ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) - ContentsResizeValue 对象
### getRightMargin() {#getRightMargin--}
```
public IPdfFileEditor.ContentsResizeValue getRightMargin()
```


获取或设置结果页面的右边距。

**退货：**
[ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) - ContentsResizeValue 对象
### getTopMargin() {#getTopMargin--}
```
public IPdfFileEditor.ContentsResizeValue getTopMargin()
```


获取或设置结果页面的上边距。

**退货：**
[ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) - ContentsResizeValue 对象
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### margins(double left, double right, double top, double bottom) {#margins-double-double-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters margins(double left, double right, double top, double bottom)
```


创建具有指定边距值的调整大小参数。内容大小是自动计算的。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| left | double | 左边距。 |
| right | double | 右边距。 |
| top | double | 上边距。 |
| bottom | double | 底边距。 |

**退货：**
[ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) - 创建调整大小参数。
### marginsPercent(double left, double right, double top, double bottom) {#marginsPercent-double-double-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters marginsPercent(double left, double right, double top, double bottom)
```


创建调整大小参数。边距以初始页面大小的百分比指定。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| left | double | 左边距（以页面宽度的百分比表示）。 |
| right | double | 右边距（以页面高度的百分比表示）。 |
| top | double | 上边距（以页面高度的百分比表示）。 |
| bottom | double | 下边距（以页面高度的百分比表示）。 |

**退货：**
[ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) - 返回新的调整大小参数。
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


为页面调整大小创建调整大小参数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| width | double | 以单位为单位的新页面宽度。 |
| height | double | 以单位为单位的新页面高度。 |

**退货：**
[ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) - 新的调整参数。
### pageResizePct(double widthPct, double heightPct) {#pageResizePct-double-double-}
```
public IPdfFileEditor.ContentsResizeParameters pageResizePct(double widthPct, double heightPct)
```


为页面调整大小创建调整大小参数。新尺寸以百分比指定。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| widthPct | double | 以百分比表示的新页面宽度。 |
| heightPct | double | 以百分比表示的新页面高度。 |

**退货：**
[ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) - 新的调整参数。
### setBottomMargin(IPdfFileEditor.ContentsResizeValue value) {#setBottomMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
```
public void setBottomMargin(IPdfFileEditor.ContentsResizeValue value)
```


获取或设置结果页面的下边距。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) | ContentsResizeValue 对象 |

### setContentsHeight(IPdfFileEditor.ContentsResizeValue value) {#setContentsHeight-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
```
public void setContentsHeight(IPdfFileEditor.ContentsResizeValue value)
```


获取或设置结果页面上源页面内容的高度。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) | ContentsResizeValue 对象 |

### setContentsWidth(IPdfFileEditor.ContentsResizeValue value) {#setContentsWidth-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
```
public void setContentsWidth(IPdfFileEditor.ContentsResizeValue value)
```


获取或设置结果页面上源页面内容的宽度。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) | ContentsResizeValue 对象 |

### setLeftMargin(IPdfFileEditor.ContentsResizeValue value) {#setLeftMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
```
public void setLeftMargin(IPdfFileEditor.ContentsResizeValue value)
```


获取或设置结果页面的左边距。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) | ContentsResizeValue 对象 |

### setRightMargin(IPdfFileEditor.ContentsResizeValue value) {#setRightMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
```
public void setRightMargin(IPdfFileEditor.ContentsResizeValue value)
```


获取或设置结果页面的右边距。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) | ContentsResizeValue 对象 |

### setTopMargin(IPdfFileEditor.ContentsResizeValue value) {#setTopMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
```
public void setTopMargin(IPdfFileEditor.ContentsResizeValue value)
```


获取或设置结果页面的上边距。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) | ContentsResizeValue 对象 |

### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
