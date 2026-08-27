---
title: "IPdfFileEditor.ContentsResizeParameters"
linktitle: "IPdfFileEditor.ContentsResizeParameters"
second_title: "Aspose.PDF for Java API 参考"
description: "用于指定页面调整大小参数的类。允许设置以下参数：结果页面的尺寸（宽度、高度），使用默认空间单位或初始页面的百分比。"
type: docs
weight: 300
url: /zh/java/com.aspose.pdf.facades/ipdffileeditor.contentsresizeparameters/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters

```
public static class IPdfFileEditor.ContentsResizeParameters extends Object
```

用于指定页面调整参数的类。允许设置以下参数：结果页面的尺寸（宽度、高度），使用默认空间单位或初始页面尺寸的百分比；左、上、下、右边距，使用默认空间单位或初始页面尺寸的百分比；某些值可以为 null，以便自动计算。这些值将在显式指定的值计算后，根据剩余页面尺寸进行计算。例如：如果页面宽度 = 100，且新页面宽度指定为 60 单位，则左、右边距会自动计算为：(100 - 60) / 2 = 15。此类在 ResizeContents 方法中使用。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ContentsResizeParameters](#ContentsResizeParameters--) | 创建调整大小参数，其中所有值均设置为 "auto"。如有需要，后续可以指定边距和内容尺寸。 |
| [ContentsResizeParameters](#ContentsResizeParameters-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | 创建调整大小参数，其中所有值均设置为 "auto"。如有需要，后续可以指定边距和内容尺寸。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [contentSize](#contentSize-double-double-) | 创建具有指定内容尺寸的调整大小参数。 |
| [contentSizePercent](#contentSizePercent-double-double-) | 创建以初始页面尺寸百分比指定内容尺寸的调整大小参数。边距会自动计算。 |
| [getBottomMargin](#getBottomMargin--) | 获取或设置结果页面的底部边距。 |
| [getContentsHeight](#getContentsHeight--) | 获取或设置源页面内容在结果页面上的高度。 |
| [getContentsWidth](#getContentsWidth--) | 获取或设置源页面内容在结果页面上的宽度。 |
| [getLeftMargin](#getLeftMargin--) | 获取或设置结果页面的左侧边距。 |
| [getRightMargin](#getRightMargin--) | 获取或设置结果页面的右侧边距。 |
| [getTopMargin](#getTopMargin--) | 获取或设置结果页面的顶部边距。 |
| [isChangeMediaBox](#isChangeMediaBox--) | 获取在调整大小操作期间是否调整 PDF 页面 的 MediaBox。默认值为 {@code false}。设置此参数可在调整大小时将 MediaBox 适配到 CropBox 的值。 |
| [margins](#margins-double-double-double-double-) | 创建具有指定边距值的调整大小参数。内容尺寸会自动计算。 |
| [marginsPercent](#marginsPercent-double-double-double-double-) | 创建调整大小参数。边距以初始页面尺寸的百分比指定。 |
| [pageResize](#pageResize-double-double-) | 创建页面调整大小的参数。 |
| [pageResizePct](#pageResizePct-double-double-) | 创建页面调整大小的参数。新尺寸以百分比指定。 |
| [setBottomMargin](#setBottomMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | 获取或设置结果页面的底部边距。 |
| [setChangeMediaBox](#setChangeMediaBox-boolean-) | 设置在调整大小操作期间是否调整 PDF 页面 的 MediaBox。默认值为 {@code false}。设置此参数可在调整大小时将 MediaBox 适配到 CropBox 的值。 |
| [setContentsHeight](#setContentsHeight-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | 获取或设置源页面内容在结果页面上的高度。 |
| [setContentsWidth](#setContentsWidth-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | 获取或设置源页面内容在结果页面上的宽度。 |
| [setLeftMargin](#setLeftMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | 获取或设置结果页面的左侧边距。 |
| [setRightMargin](#setRightMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | 获取或设置结果页面的右侧边距。 |
| [setTopMargin](#setTopMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | 获取或设置结果页面的顶部边距。 |

### ContentsResizeParameters {#ContentsResizeParameters--}
```
public ContentsResizeParameters()
```

创建调整大小参数，其中所有值均设置为 "auto"。如有需要，后续可以指定边距和内容尺寸。

### ContentsResizeParameters {#ContentsResizeParameters-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
创建调整大小参数，其中所有值均设置为 "auto"。如有需要，后续可以指定边距和内容尺寸。

### contentSize {#contentSize-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters contentSize(double width, double height)
```

创建具有指定内容尺寸的调整大小参数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 |  | 内容的新宽度。 |
| 高度 |  | 内容的新高度。 |

**Returns:**
返回新的调整大小参数。

### contentSizePercent {#contentSizePercent-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters contentSizePercent(double width, double height)
```

创建以初始页面尺寸百分比指定内容尺寸的调整大小参数。边距会自动计算。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 |  | 内容宽度的新百分比。 |
| 高度 |  | 新内容高度（百分比）。 |

**Returns:**
新的调整大小参数。

### getBottomMargin {#getBottomMargin--}
```
public IPdfFileEditor.ContentsResizeValue getBottomMargin()
```

获取或设置结果页面的底部边距。

**Returns:**
ContentsResizeValue 对象

### getContentsHeight {#getContentsHeight--}
```
public IPdfFileEditor.ContentsResizeValue getContentsHeight()
```

获取或设置源页面内容在结果页面上的高度。

**Returns:**
ContentsResizeValue 对象

### getContentsWidth {#getContentsWidth--}
```
public IPdfFileEditor.ContentsResizeValue getContentsWidth()
```

获取或设置源页面内容在结果页面上的宽度。

**Returns:**
ContentsResizeValue 对象

### getLeftMargin {#getLeftMargin--}
```
public IPdfFileEditor.ContentsResizeValue getLeftMargin()
```

获取或设置结果页面的左侧边距。

**Returns:**
ContentsResizeValue 对象

### getRightMargin {#getRightMargin--}
```
public IPdfFileEditor.ContentsResizeValue getRightMargin()
```

获取或设置结果页面的右侧边距。

**Returns:**
ContentsResizeValue 对象

### getTopMargin {#getTopMargin--}
```
public IPdfFileEditor.ContentsResizeValue getTopMargin()
```

获取或设置结果页面的顶部边距。

**Returns:**
ContentsResizeValue 对象

### isChangeMediaBox {#isChangeMediaBox--}
```
public final boolean isChangeMediaBox()
```

获取在调整大小操作期间是否调整 PDF 页面 的 MediaBox。默认值为 {@code false}。设置此参数可在调整大小时将 MediaBox 适配到 CropBox 的值。

**Returns:**
是否在调整大小操作期间调整 PDF 页面 的 MediaBox。

### margins {#margins-double-double-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters margins(double left, double right, double top, double bottom)
```

创建具有指定边距值的调整大小参数。内容尺寸会自动计算。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left |  | 左侧页边距。 |
| 右 |  | 右侧页边距。 |
| 顶部 |  | 顶部页边距。 |
| bottom |  | 底部边距。 |

**Returns:**
已创建的调整大小参数。

### marginsPercent {#marginsPercent-double-double-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters marginsPercent(double left, double right, double top, double bottom)
```

创建调整大小参数。边距以初始页面尺寸的百分比指定。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left |  | 左边距（占页面宽度的百分比）。 |
| 右 |  | 右边距（占页面高度的百分比）。 |
| 顶部 |  | 顶部边距（占页面高度的百分比）。 |
| bottom |  | 底部边距（占页面高度的百分比）。 |

**Returns:**
返回新的调整大小参数。

### pageResize {#pageResize-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters pageResize(double width, double height)
```

创建页面调整大小的参数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 |  | 新页面宽度（单位）。 |
| 高度 |  | 新页面高度（单位）。 |

**Returns:**
新的调整大小参数。

### pageResizePct {#pageResizePct-double-double-}
```
public IPdfFileEditor.ContentsResizeParameters pageResizePct(double widthPct, double heightPct)
```

创建页面调整大小的参数。新尺寸以百分比指定。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| widthPct |  | 新页面宽度（百分比）。 |
| heightPct |  | 新页面高度（百分比）。 |

**Returns:**
新的调整大小参数。

### setBottomMargin {#setBottomMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
获取或设置结果页面的底部边距。

### setChangeMediaBox {#setChangeMediaBox-boolean-}
```
public final void setChangeMediaBox(boolean value)
```

设置在调整大小操作期间是否调整 PDF 页面 的 MediaBox。默认值为 {@code false}。设置此参数可在调整大小时将 MediaBox 适配到 CropBox 的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 是否在调整大小操作期间调整 PDF 页面 的 MediaBox。 |

### setContentsHeight {#setContentsHeight-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
获取或设置源页面内容在结果页面上的高度。

### setContentsWidth {#setContentsWidth-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
获取或设置源页面内容在结果页面上的宽度。

### setLeftMargin {#setLeftMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
获取或设置结果页面的左侧边距。

### setRightMargin {#setRightMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
获取或设置结果页面的右侧边距。

### setTopMargin {#setTopMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
获取或设置结果页面的顶部边距。
