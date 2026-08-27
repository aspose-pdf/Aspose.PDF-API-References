---
title: "HorizontalAlignment"
linktitle: "HorizontalAlignment"
second_title: "Aspose.PDF for Java API 参考"
description: "描述水平对齐方式。"
type: docs
weight: 1930
url: /zh/java/com.aspose.pdf/horizontalalignment/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < HorizontalAlignment > com.aspose.pdf.HorizontalAlignment, java.lang.Enum < HorizontalAlignment >, com.aspose.pdf.HorizontalAlignment

**All Implemented Interfaces:**
Serializable, Comparable < HorizontalAlignment >

```
public enum HorizontalAlignment extends Enum < HorizontalAlignment >
```

描述水平对齐方式。

## 字段

| 字段 | 描述 |
| --- | --- |
| [Center](#Center) | 居中对齐。 |
| [FullJustify](#FullJustify) | 类似于 'Justify' 对齐方式，但在 'Justify' 模式下，最后一行仅左对齐，而在 'FullJustify' 模式下，所有行都将左对齐和右对齐。 |
| [Justify](#Justify) | 两端对齐。 |
| [Left](#Left) | 左对齐。 |
| [None](#None) | 无对齐。 |
| [Right](#Right) | 右对齐。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getValue](#getValue--) | 获取数量 |
| [valueOf](#valueOf-int-) |  |
| [valueOf](#valueOf-java.lang.String-) | 返回此类型中具有指定名称的枚举常量。 |
| [values](#values--) | 返回一个数组，包含此枚举类型的常量，按声明顺序排列。 |

### Center {#Center}
```
public static final HorizontalAlignment Center
```

居中对齐。

### FullJustify {#FullJustify}
```
public static final HorizontalAlignment FullJustify
```

类似于 'Justify' 对齐方式，但在 'Justify' 模式下，最后一行仅左对齐，而在 'FullJustify' 模式下，所有行都将左对齐和右对齐。

### Justify {#Justify}
```
public static final HorizontalAlignment Justify
```

两端对齐。

### Left {#Left}
```
public static final HorizontalAlignment Left
```

左对齐。

### None {#None}
```
public static final HorizontalAlignment None
```

无对齐。

### Right {#Right}
```
public static final HorizontalAlignment Right
```

右对齐。

### getValue {#getValue--}
```
public int getValue()
```

获取数量

**Returns:**
HorizontalAlignment 元素的 int 值

### valueOf {#valueOf-int-}
```
public static HorizontalAlignment valueOf(int alignmentType)
```



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| alignmentType |  |  |

### valueOf {#valueOf-java.lang.String-}
返回此类型中具有指定名称的枚举常量。

### values {#values--}
```
public static HorizontalAlignment [] values()
```

返回一个数组，包含此枚举类型的常量，按声明顺序排列。

**Returns:**
一个数组，包含此枚举类型的常量，按声明顺序排列
