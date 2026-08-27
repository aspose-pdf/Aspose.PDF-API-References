---
title: "BorderInfo"
linktitle: "BorderInfo"
second_title: "Aspose.PDF for Java API 参考"
description: "此类表示图形元素的边框。"
type: docs
weight: 370
url: /zh/java/com.aspose.pdf/borderinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BorderInfo

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class BorderInfo extends Object implements com.aspose.ms.System.ICloneable
```

此类表示图形元素的边框。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BorderInfo](#BorderInfo--) | 初始化 {@code BorderInfo} 类的新实例。 |
| [BorderInfo](#BorderInfo-int-) | 初始化 {@code BorderInfo} 类的新实例。 |
| [BorderInfo](#BorderInfo-int-com.aspose.pdf.Color-) | 初始化 {@code BorderInfo} 类的新实例。 |
| [BorderInfo](#BorderInfo-int-float-) | 初始化 {@code BorderInfo} 类的新实例。 |
| [BorderInfo](#BorderInfo-int-float-com.aspose.pdf.Color-) | 初始化 {@code BorderInfo} 类的新实例。 |
| [BorderInfo](#BorderInfo-int-com.aspose.pdf.GraphInfo-) | 初始化 {@code BorderInfo} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone](#deepClone--) | 克隆一个新的 BorderInfo 对象。 |
| [getBottom](#getBottom--) | 获取指示边框底部的对象。 |
| [getLeft](#getLeft--) | 获取指示边框左侧的 {@code GraphInfo} 对象。 |
| [getRight](#getRight--) | 获取指示边框右侧的 {@code GraphInfo} 对象。 |
| [getRoundedBorderRadius](#getRoundedBorderRadius--) | 获取圆角边框半径。 |
| [getTop](#getTop--) | 获取指示顶部边框的 {@code GraphInfo} 对象。 |
| [setBottom](#setBottom-com.aspose.pdf.GraphInfo-) | 设置指示边框底部的对象。 |
| [setLeft](#setLeft-com.aspose.pdf.GraphInfo-) | 设置指示边框左侧的 {@code GraphInfo} 对象。 |
| [setRight](#setRight-com.aspose.pdf.GraphInfo-) | 设置指示边框右侧的 {@code GraphInfo} 对象。 |
| [setRoundedBorderRadius](#setRoundedBorderRadius-double-) | 设置圆角边框半径。 |
| [setTop](#setTop-com.aspose.pdf.GraphInfo-) | 设置指示边框顶部的 {@code GraphInfo} 对象。 |

### BorderInfo {#BorderInfo--}
```
public BorderInfo()
```

初始化 {@code BorderInfo} 类的新实例。

### BorderInfo {#BorderInfo-int-}
```
public BorderInfo(int borderSide)
```

初始化 {@code BorderInfo} 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| borderSide |  | 指示边框侧信息。例如：(BorderSide.Left \ | BorderSide.Top). |

### BorderInfo {#BorderInfo-int-com.aspose.pdf.Color-}
初始化 {@code BorderInfo} 类的新实例。

### BorderInfo {#BorderInfo-int-float-}
```
public BorderInfo(int borderSide, float borderWidth)
```

初始化 {@code BorderInfo} 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| borderSide |  | 指示边框侧信息。例如：(BorderSide.Left \ | BorderSide.Top). |
| borderWidth |  | 边框的宽度。 |

### BorderInfo {#BorderInfo-int-float-com.aspose.pdf.Color-}
初始化 {@code BorderInfo} 类的新实例。

### BorderInfo {#BorderInfo-int-com.aspose.pdf.GraphInfo-}
初始化 {@code BorderInfo} 类的新实例。

### deepClone {#deepClone--}
```
public Object deepClone()
```

克隆一个新的 BorderInfo 对象。

**Returns:**
新的 BorderInfo 对象。

### getBottom {#getBottom--}
```
public GraphInfo getBottom()
```

获取指示边框底部的对象。

**Returns:**
bottom

### getLeft {#getLeft--}
```
public GraphInfo getLeft()
```

获取指示边框左侧的 {@code GraphInfo} 对象。

**Returns:**
指示边框左侧的对象。

### getRight {#getRight--}
```
public GraphInfo getRight()
```

获取指示边框右侧的 {@code GraphInfo} 对象。

**Returns:**
指示边框右侧的对象。

### getRoundedBorderRadius {#getRoundedBorderRadius--}
```
public double getRoundedBorderRadius()
```

获取圆角边框半径。

**Returns:**
值

### getTop {#getTop--}
```
public GraphInfo getTop()
```

获取指示顶部边框的 {@code GraphInfo} 对象。

**Returns:**
指示顶部边框的对象

### setBottom {#setBottom-com.aspose.pdf.GraphInfo-}
设置指示边框底部的对象。

### setLeft {#setLeft-com.aspose.pdf.GraphInfo-}
设置指示边框左侧的 {@code GraphInfo} 对象。

### setRight {#setRight-com.aspose.pdf.GraphInfo-}
设置指示边框右侧的 {@code GraphInfo} 对象。

### setRoundedBorderRadius {#setRoundedBorderRadius-double-}
```
public void setRoundedBorderRadius(double value)
```

设置圆角边框半径。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setTop {#setTop-com.aspose.pdf.GraphInfo-}
设置指示边框顶部的 {@code GraphInfo} 对象。
