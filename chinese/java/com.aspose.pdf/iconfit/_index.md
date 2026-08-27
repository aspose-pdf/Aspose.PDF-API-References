---
title: "IconFit"
linktitle: "IconFit"
second_title: "Aspose.PDF for Java API 参考"
description: "描述小部件注释的图标应如何显示在其注释矩形内。"
type: docs
weight: 2210
url: /zh/java/com.aspose.pdf/iconfit/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.IconFit

```
public final class IconFit extends Object
```

描述小部件注释的图标应如何显示在其注释矩形内。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getLeftoverBottom](#getLeftoverBottom--) | 获取在图标底部分配的空间。 |
| [getLeftoverLeft](#getLeftoverLeft--) | 获取在图标左侧分配的空间。 |
| [getScalingMode](#getScalingMode--) | 应使用的缩放类型。 |
| [getScalingReason](#getScalingReason--) | 获取缩放原因。 |
| [isSpreadOnBorder](#isSpreadOnBorder--) | 如果为 true，则表示按钮外观应缩放以完全适应注释的边界，而不考虑边框的线宽。 |
| [nameToScalingMode](#nameToScalingMode-java.lang.String-) | 将缩放模式名称转换为 ScalingMode 对象。 |
| [nameToScalingReason](#nameToScalingReason-java.lang.String-) | 将缩放原因的名称转换为 ScalingReason 对象。 |
| [scalingModeToName](#scalingModeToName-int-) | 将缩放模式对象转换为名称。 |
| [scalingReasonToName](#scalingReasonToName-int-) | 将缩放原因对象转换为名称。 |
| [setLeftoverBottom](#setLeftoverBottom-double-) | 设置在图标底部分配的空间。 |
| [setLeftoverLeft](#setLeftoverLeft-double-) | 设置在图标左侧分配的空间。 |
| [setScalingMode](#setScalingMode-int-) | 应使用的缩放类型。 |
| [setScalingReason](#setScalingReason-int-) | 设置缩放原因。 |
| [setSpreadOnBorder](#setSpreadOnBorder-boolean-) | 如果为 true，则表示按钮外观应缩放以完全适应注释的边界，而不考虑边框的线宽。 |

### getLeftoverBottom {#getLeftoverBottom--}
```
public double getLeftoverBottom()
```

获取在图标底部分配的空间。

**Returns:**
在底部分配的空间

### getLeftoverLeft {#getLeftoverLeft--}
```
public double getLeftoverLeft()
```

获取在图标左侧分配的空间。

**Returns:**
在图标左侧分配的空间。

### getScalingMode {#getScalingMode--}
```
public int getScalingMode()
```

应使用的缩放类型。

**Returns:**
ScalingMode 值 @see ScalingMode

### getScalingReason {#getScalingReason--}
```
public int getScalingReason()
```

获取缩放原因。

**Returns:**
ScalingReason 值 @see ScalingReason

### isSpreadOnBorder {#isSpreadOnBorder--}
```
public boolean isSpreadOnBorder()
```

如果为 true，则表示按钮外观应缩放以完全适应注释的边界，而不考虑边框的线宽。

**Returns:**
布尔值

### nameToScalingMode {#nameToScalingMode-java.lang.String-}
将缩放模式名称转换为 ScalingMode 对象。

### nameToScalingReason {#nameToScalingReason-java.lang.String-}
将缩放原因的名称转换为 ScalingReason 对象。

### scalingModeToName {#scalingModeToName-int-}
```
public static String scalingModeToName(int mode)
```

将缩放模式对象转换为名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 模式 |  | 缩放模式对象。 |

**Returns:**
缩放模式名称。

### scalingReasonToName {#scalingReasonToName-int-}
```
public static String scalingReasonToName(int reason)
```

将缩放原因对象转换为名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 原因 |  | 要转换的缩放原因对象。 |

**Returns:**
缩放 reasong 的名称。

### setLeftoverBottom {#setLeftoverBottom-double-}
```
public void setLeftoverBottom(double value)
```

设置在图标底部分配的空间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 在底部分配的空间 |

### setLeftoverLeft {#setLeftoverLeft-double-}
```
public void setLeftoverLeft(double value)
```

设置在图标左侧分配的空间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 在图标左侧分配的空间。 |

### setScalingMode {#setScalingMode-int-}
```
public void setScalingMode(int value)
```

应使用的缩放类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | ScalingMode 值 @see ScalingMode |

### setScalingReason {#setScalingReason-int-}
```
public void setScalingReason(int value)
```

设置缩放原因。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | ScalingReason 值 @see ScalingReason |

### setSpreadOnBorder {#setSpreadOnBorder-boolean-}
```
public void setSpreadOnBorder(boolean value)
```

如果为 true，则表示按钮外观应缩放以完全适应注释的边界，而不考虑边框的线宽。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |
