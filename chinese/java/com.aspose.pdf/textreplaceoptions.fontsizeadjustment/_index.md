---
title: "TextReplaceOptions.FontSizeAdjustment"
linktitle: "TextReplaceOptions.FontSizeAdjustment"
second_title: "Aspose.PDF for Java API 参考"
description: "指定文本字体大小应如何调整以适应包含区域的策略。"
type: docs
weight: 5260
url: /zh/java/com.aspose.pdf/textreplaceoptions.fontsizeadjustment/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < TextReplaceOptions.FontSizeAdjustment > com.aspose.pdf.TextReplaceOptions.FontSizeAdjustment, java.lang.Enum < TextReplaceOptions.FontSizeAdjustment >, com.aspose.pdf.TextReplaceOptions.FontSizeAdjustment

**All Implemented Interfaces:**
Serializable, Comparable < TextReplaceOptions.FontSizeAdjustment >

```
public static enum TextReplaceOptions.FontSizeAdjustment extends Enum < TextReplaceOptions.FontSizeAdjustment >
```

指定文本字体大小应如何调整以适应包含区域的策略。

## 字段

| 字段 | 描述 |
| --- | --- |
| [None](#None) | 字体大小未更改。 |
| [ScaleToFill](#ScaleToFill) | 字体大小已调整（包括缩小和放大），以使文本尽可能填满矩形的边界。 |
| [ShrinkToFit](#ShrinkToFit) | 如果文本太大而无法适应边界，则会减小字体大小。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | 返回此类型中具有指定名称的枚举常量。 |
| [values](#values--) | 返回一个数组，包含此枚举类型的常量，按声明顺序排列。 |

### None {#None}
```
public static final TextReplaceOptions.FontSizeAdjustment None
```

字体大小未更改。

### ScaleToFill {#ScaleToFill}
```
public static final TextReplaceOptions.FontSizeAdjustment ScaleToFill
```

字体大小已调整（包括缩小和放大），以使文本尽可能填满矩形的边界。

### ShrinkToFit {#ShrinkToFit}
```
public static final TextReplaceOptions.FontSizeAdjustment ShrinkToFit
```

如果文本太大而无法适应边界，则会减小字体大小。

### getByValue {#getByValue-int-}
```
public static TextReplaceOptions.FontSizeAdjustment getByValue(int value)
```



### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
返回此类型中具有指定名称的枚举常量。

### values {#values--}
```
public static TextReplaceOptions.FontSizeAdjustment [] values()
```

返回一个数组，包含此枚举类型的常量，按声明顺序排列。

**Returns:**
一个数组，包含此枚举类型的常量，按声明顺序排列
