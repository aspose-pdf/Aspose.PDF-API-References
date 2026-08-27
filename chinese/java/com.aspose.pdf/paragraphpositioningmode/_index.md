---
title: "ParagraphPositioningMode"
linktitle: "ParagraphPositioningMode"
second_title: "Aspose.PDF for Java API 参考"
description: "指定用于确定元素在页面上位置的变体。"
type: docs
weight: 3490
url: /zh/java/com.aspose.pdf/paragraphpositioningmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < ParagraphPositioningMode > com.aspose.pdf.ParagraphPositioningMode, java.lang.Enum < ParagraphPositioningMode >, com.aspose.pdf.ParagraphPositioningMode

**All Implemented Interfaces:**
Serializable, Comparable < ParagraphPositioningMode >

```
public enum ParagraphPositioningMode extends Enum < ParagraphPositioningMode >
```

指定用于确定元素在页面上位置的变体。

## 字段

| 字段 | 描述 |
| --- | --- |
| [Absolute](#Absolute) | 位置由 Left 和 Top 值指定，不依赖于先前的元素，也不影响后续元素的位置。 |
| [Default](#Default) | 位置由先前放置的元素决定。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | 返回此类型中具有指定名称的枚举常量。 |
| [values](#values--) | 返回一个数组，包含此枚举类型的常量，按声明顺序排列。 |

### Absolute {#Absolute}
```
public static final ParagraphPositioningMode Absolute
```

位置由 Left 和 Top 值指定，不依赖于先前的元素，也不影响后续元素的位置。

### Default {#Default}
```
public static final ParagraphPositioningMode Default
```

位置由先前放置的元素决定。

### getByValue {#getByValue-int-}
```
public static ParagraphPositioningMode getByValue(int value)
```



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
返回此类型中具有指定名称的枚举常量。

### values {#values--}
```
public static ParagraphPositioningMode [] values()
```

返回一个数组，包含此枚举类型的常量，按声明顺序排列。

**Returns:**
一个数组，包含此枚举类型的常量，按声明顺序排列
