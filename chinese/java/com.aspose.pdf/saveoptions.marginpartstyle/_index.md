---
title: "SaveOptions.MarginPartStyle"
linktitle: "SaveOptions.MarginPartStyle"
second_title: "Aspose.PDF for Java API 参考"
description: "表示边距（上、下、左侧或右侧）某一部分的信息。"
type: docs
weight: 4420
url: /zh/java/com.aspose.pdf/saveoptions.marginpartstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions.MarginPartStyle

```
public static class SaveOptions.MarginPartStyle extends Object
```

表示边距（上、下、左侧或右侧）某一部分的信息。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MarginPartStyle](#MarginPartStyle-boolean-) | 创建 MarginPartStyle 类的实例并以点为单位初始化其值 |
| [MarginPartStyle](#MarginPartStyle-int-) | 创建 MarginPartStyle 类的实例并以点为单位设置其值 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getValueInPoints](#getValueInPoints--) | 表示以点为单位的边距。必须是大于零的数字。 |
| [isAuto](#isAuto--) | 获取或设置一个值，指示此实例是否为自动。值：{@code true} 表示此实例为自动；否则 {@code false}。 |
| [setAuto](#setAuto-boolean-) | 获取或设置一个值，指示此实例是否为自动。值：{@code true} 表示此实例为自动；否则 {@code false}。 |
| [setValueInPoints](#setValueInPoints-int-) | 表示以点为单位的边距。必须是大于零的数字。 |

### MarginPartStyle {#MarginPartStyle-boolean-}
```
public MarginPartStyle(boolean isAuto)
```

创建 MarginPartStyle 类的实例并以点为单位初始化其值

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isAuto |  | 标记边距自动 |

### MarginPartStyle {#MarginPartStyle-int-}
```
public MarginPartStyle(int valueInPoints)
```

创建 MarginPartStyle 类的实例并以点为单位设置其值

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| valueInPoints |  | 以点为单位的整数值 |

### getValueInPoints {#getValueInPoints--}
```
public final int getValueInPoints()
```

表示以点为单位的边距。必须是大于零的数字。

**Returns:**
int 值

### isAuto {#isAuto--}
```
public final boolean isAuto()
```

获取或设置一个值，指示此实例是否为自动。值：{@code true} 表示此实例为自动；否则 {@code false}。

**Returns:**
布尔值

### setAuto {#setAuto-boolean-}
```
public final void setAuto(boolean value)
```

获取或设置一个值，指示此实例是否为自动。值：{@code true} 表示此实例为自动；否则 {@code false}。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setValueInPoints {#setValueInPoints-int-}
```
public final void setValueInPoints(int value)
```

表示以点为单位的边距。必须是大于零的数字。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |
