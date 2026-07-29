---
title: "TextEditOptions.NoCharacterAction"
linktitle: "TextEditOptions.NoCharacterAction"
second_title: "Aspose.PDF for Java API 参考"
description: "当字体不包含所需字符时要执行的操作"
type: docs
weight: 5010
url: /zh/java/com.aspose.pdf/texteditoptions.nocharacteraction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < TextEditOptions.NoCharacterAction > com.aspose.pdf.TextEditOptions.NoCharacterAction, java.lang.Enum < TextEditOptions.NoCharacterAction >, com.aspose.pdf.TextEditOptions.NoCharacterAction

**All Implemented Interfaces:**
Serializable, Comparable < TextEditOptions.NoCharacterAction >

```
public static enum TextEditOptions.NoCharacterAction extends Enum < TextEditOptions.NoCharacterAction >
```

当字体不包含所需字符时要执行的操作

## 字段

| 字段 | 描述 |
| --- | --- |
| [ReplaceAnyway](#ReplaceAnyway) | 仍然替换文本而不进行字体替换 |
| [ReplaceFonts](#ReplaceFonts) | 根据需要替换字体，以确保文本中的所有字符都能显示。 |
| [ThrowException](#ThrowException) | 抛出异常 |
| [UseCustomReplacementFont](#UseCustomReplacementFont) | 将字体替换为定义的替代字体 |
| [UseStandardFont](#UseStandardFont) | 将字体替换为包含所需字符的标准字体 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | 返回此类型中具有指定名称的枚举常量。 |
| [values](#values--) | 返回一个数组，包含此枚举类型的常量，按声明顺序排列。 |

### ReplaceAnyway {#ReplaceAnyway}
```
public static final TextEditOptions.NoCharacterAction ReplaceAnyway
```

仍然替换文本而不进行字体替换

### ReplaceFonts {#ReplaceFonts}
```
public static final TextEditOptions.NoCharacterAction ReplaceFonts
```

根据需要替换字体，以确保文本中的所有字符都能显示。

### ThrowException {#ThrowException}
```
public static final TextEditOptions.NoCharacterAction ThrowException
```

抛出异常

### UseCustomReplacementFont {#UseCustomReplacementFont}
```
public static final TextEditOptions.NoCharacterAction UseCustomReplacementFont
```

将字体替换为定义的替代字体

### UseStandardFont {#UseStandardFont}
```
public static final TextEditOptions.NoCharacterAction UseStandardFont
```

将字体替换为包含所需字符的标准字体

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
返回此类型中具有指定名称的枚举常量。

### values {#values--}
```
public static TextEditOptions.NoCharacterAction [] values()
```

返回一个数组，包含此枚举类型的常量，按声明顺序排列。

**Returns:**
一个数组，包含此枚举类型的常量，按声明顺序排列
