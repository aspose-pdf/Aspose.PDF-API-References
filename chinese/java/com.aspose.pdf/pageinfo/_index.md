---
title: "PageInfo"
linktitle: "PageInfo"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 pdf 生成器的页面信息。"
type: docs
weight: 3370
url: /zh/java/com.aspose.pdf/pageinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageInfo

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class PageInfo extends Object implements com.aspose.ms.System.ICloneable
```

表示 pdf 生成器的页面信息。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PageInfo](#PageInfo--) | 默认构造函数 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone](#deepClone--) | 克隆页面信息。 |
| [getAnyMargin](#getAnyMargin--) | 获取或设置除第一页之外的任何页面的页边距。 |
| [getDefaultTextState](#getDefaultTextState--) | 获取默认字体。 |
| [getHeight](#getHeight--) | 获取页面高度。 |
| [getMargin](#getMargin--) | 获取页面边距。 |
| [getPureHeight](#getPureHeight--) | 获取不含边距的页面纯高度。 |
| [getWidth](#getWidth--) | 获取页面宽度。 |
| [isLandscape](#isLandscape--) | 获取页面是否为横向。 |
| [setAnyMargin](#setAnyMargin-com.aspose.pdf.MarginInfo-) | 获取或设置除第一页之外的任何页面的页边距。 |
| [setDefaultTextState](#setDefaultTextState-com.aspose.pdf.TextState-) | 设置默认字体。 |
| [setHeight](#setHeight-double-) | 设置页面高度。 |
| [setLandscape](#setLandscape-boolean-) | 设置页面是否为横向。 |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | 设置页面边距。 |
| [setWidth](#setWidth-double-) | 设置页面宽度。 |

### PageInfo {#PageInfo--}
```
public PageInfo()
```

默认构造函数

### deepClone {#deepClone--}
```
public Object deepClone()
```

克隆页面信息。

**Returns:**
克隆的对象。

### getAnyMargin {#getAnyMargin--}
```
public final MarginInfo getAnyMargin()
```

获取或设置除第一页之外的任何页面的页边距。

**Returns:**
MarginInfo 实例

### getDefaultTextState {#getDefaultTextState--}
```
public TextState getDefaultTextState()
```

获取默认字体。

**Returns:**
TextState 实例

### getHeight {#getHeight--}
```
public double getHeight()
```

获取页面高度。

**Returns:**
double 值

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

获取页面边距。

**Returns:**
MarginInfo 值

### getPureHeight {#getPureHeight--}
```
public double getPureHeight()
```

获取不含边距的页面纯高度。

**Returns:**
double 值

### getWidth {#getWidth--}
```
public double getWidth()
```

获取页面宽度。

**Returns:**
double 值

### isLandscape {#isLandscape--}
```
public boolean isLandscape()
```

获取页面是否为横向。

**Returns:**
布尔值

### setAnyMargin {#setAnyMargin-com.aspose.pdf.MarginInfo-}
获取或设置除第一页之外的任何页面的页边距。

### setDefaultTextState {#setDefaultTextState-com.aspose.pdf.TextState-}
设置默认字体。

### setHeight {#setHeight-double-}
```
public final void setHeight(double value)
```

设置页面高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setLandscape {#setLandscape-boolean-}
```
public void setLandscape(boolean value)
```

设置页面是否为横向。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
设置页面边距。

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

设置页面宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |
