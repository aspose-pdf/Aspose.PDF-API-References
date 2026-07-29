---
title: "TextReplaceOptions.Scope"
linktitle: "TextReplaceOptions.Scope"
second_title: "Aspose.PDF for Java API 参考"
description: "替换文本操作应用的范围，默认使用 REPLACE_FIRST。此已废弃选项为兼容性保留。它影响 PdfContentEditor，但对其他无效。"
type: docs
weight: 5280
url: /zh/java/com.aspose.pdf/textreplaceoptions.scope/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < TextReplaceOptions.Scope > com.aspose.pdf.TextReplaceOptions.Scope, java.lang.Enum < TextReplaceOptions.Scope >, com.aspose.pdf.TextReplaceOptions.Scope

**All Implemented Interfaces:**
Serializable, Comparable < TextReplaceOptions.Scope >

```
public static enum TextReplaceOptions.Scope extends Enum < TextReplaceOptions.Scope >
```

替换文本操作的作用范围，默认使用 REPLACE_FIRST。此已废弃选项为兼容性保留。它影响 PdfContentEditor，但对 TextFragmentAbsorber 没有影响。

## 字段

| 字段 | 描述 |
| --- | --- |
| [REPLACE_ALL](#REPLACE_ALL) | 在所有受影响的页面上替换所有文本出现位置 |
| [REPLACE_FIRST](#REPLACE_FIRST) | 在每个受影响的页面上仅替换文本的第一次出现 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | 返回此类型中具有指定名称的枚举常量。 |
| [values](#values--) | 返回一个数组，包含此枚举类型的常量，按声明顺序排列。 |

### REPLACE_ALL {#REPLACE_ALL}
```
public static final TextReplaceOptions.Scope REPLACE_ALL
```

在所有受影响的页面上替换所有文本出现位置

### REPLACE_FIRST {#REPLACE_FIRST}
```
public static final TextReplaceOptions.Scope REPLACE_FIRST
```

在每个受影响的页面上仅替换文本的第一次出现

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
返回此类型中具有指定名称的枚举常量。

### values {#values--}
```
public static TextReplaceOptions.Scope [] values()
```

返回一个数组，包含此枚举类型的常量，按声明顺序排列。

**Returns:**
一个数组，包含此枚举类型的常量，按声明顺序排列
