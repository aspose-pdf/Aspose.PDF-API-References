---
title: "ColorType"
linktitle: "ColorType"
second_title: "Aspose.PDF for Java API 参考"
description: "指定页面上元素的颜色类型。"
type: docs
weight: 710
url: /zh/java/com.aspose.pdf/colortype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < ColorType > com.aspose.pdf.ColorType, java.lang.Enum < ColorType >, com.aspose.pdf.ColorType

**All Implemented Interfaces:**
可序列化，可比较 < ColorType >

```
public enum ColorType extends Enum < ColorType >
```

指定页面上元素的颜色类型。

## 字段

| 字段 | 描述 |
| --- | --- |
| [BlackAndWhite](#BlackAndWhite) | 黑白颜色类型。 |
| [Grayscale](#Grayscale) | 灰度颜色类型。 |
| [Rgb](#Rgb) | RGB 颜色类型。 |
| [Undefined](#Undefined) | 未定义的颜色类型值。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getName](#getName-int-) | <p> 返回枚举值的字符串名称。 </p> <hr> 示例: <br> {@code String s = ColorType.getName(ColorType.Grayscale); } |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | 返回此类型中具有指定名称的枚举常量。 |
| [values](#values--) | 返回一个数组，包含此枚举类型的常量，按声明顺序排列。 |

### BlackAndWhite {#BlackAndWhite}
```
public static final ColorType BlackAndWhite
```

黑白颜色类型。

### Grayscale {#Grayscale}
```
public static final ColorType Grayscale
```

灰度颜色类型。

### Rgb {#Rgb}
```
public static final ColorType Rgb
```

RGB 颜色类型。

### Undefined {#Undefined}
```
public static final ColorType Undefined
```

未定义的颜色类型值。

### getByValue {#getByValue-int-}
```
public static ColorType getByValue(int value)
```



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  |  |

### getName {#getName-int-}
```
public static String getName(int value)
```

<p> 返回枚举值的字符串名称。 </p> <hr> 示例: <br> {@code String s = ColorType.getName(ColorType.Grayscale); }

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 枚举值 |

**Returns:**
值的名称

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
返回此类型中具有指定名称的枚举常量。

### values {#values--}
```
public static ColorType [] values()
```

返回一个数组，包含此枚举类型的常量，按声明顺序排列。

**Returns:**
一个数组，包含此枚举类型的常量，按声明顺序排列
