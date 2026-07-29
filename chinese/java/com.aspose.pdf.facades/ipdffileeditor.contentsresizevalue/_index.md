---
title: "IPdfFileEditor.ContentsResizeValue"
linktitle: "IPdfFileEditor.ContentsResizeValue"
second_title: "Aspose.PDF for Java API 参考"
description: "以默认空间单位的百分比指定的边距或内容尺寸值。此类在 ContentsResizeParameters 中使用。"
type: docs
weight: 310
url: /zh/java/com.aspose.pdf.facades/ipdffileeditor.contentsresizevalue/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue

```
public static class IPdfFileEditor.ContentsResizeValue extends Object
```

以默认空间单位的百分比指定的边距或内容尺寸值。此类在 ContentsResizeParameters 中使用。

## 方法

| 方法 | 描述 |
| --- | --- |
| [auto](#auto--) | 初始化自动计算的值。 |
| [getValue](#getValue--) | 获取指定的值。使用 Unit 属性获取值的单位。 |
| [isPercent](#isPercent--) | 如果值以百分比表示则返回 true；如果值以默认单位表示则返回 false。 |
| [percents](#percents-double-) | 以百分比初始化值。 |
| [setPercentValue](#setPercentValue-double-) | 设置页面尺寸百分比的值。 |
| [setUnitValue](#setUnitValue-double-) | 以默认空间单位设置值。 |
| [units](#units-double-) | 在默认空间单位中初始化值。 |

### auto {#auto--}
```
public static IPdfFileEditor.ContentsResizeValue auto()
```

初始化自动计算的值。

**Returns:**
新值实例。

### getValue {#getValue--}
```
public final double getValue()
```

获取指定的值。使用 Unit 属性获取值的单位。

**Returns:**
double 值

### isPercent {#isPercent--}
```
public final boolean isPercent()
```

如果值以百分比表示则返回 true；如果值以默认单位表示则返回 false。

**Returns:**
布尔值

### percents {#percents-double-}
```
public static IPdfFileEditor.ContentsResizeValue percents(double value)
```

以百分比初始化值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 以百分比表示的值。 |

**Returns:**
新值实例。

### setPercentValue {#setPercentValue-double-}
```
public final void setPercentValue(double value)
```

设置页面尺寸百分比的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setUnitValue {#setUnitValue-double-}
```
public final void setUnitValue(double value)
```

以默认空间单位设置值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### units {#units-double-}
```
public static IPdfFileEditor.ContentsResizeValue units(double value)
```

在默认空间单位中初始化值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 以单位表示的值。 |

**Returns:**
新值实例。
