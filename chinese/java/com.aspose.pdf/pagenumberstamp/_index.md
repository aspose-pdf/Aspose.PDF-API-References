---
title: "PageNumberStamp"
linktitle: "PageNumberStamp"
second_title: "Aspose.PDF for Java API 参考"
description: "表示页码戳记，用于给页面编号。"
type: docs
weight: 3440
url: /zh/java/com.aspose.pdf/pagenumberstamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp com.aspose.pdf.TextStamp com.aspose.pdf.PageNumberStamp, com.aspose.pdf.Stamp, com.aspose.pdf.TextStamp com.aspose.pdf.PageNumberStamp, com.aspose.pdf.TextStamp, com.aspose.pdf.PageNumberStamp

```
public final class PageNumberStamp extends TextStamp
```

表示页码戳记，用于给页面编号。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PageNumberStamp](#PageNumberStamp--) | 初始化 {@code PageNumberStamp} 类的新实例。格式设置为 "#"。 |
| [PageNumberStamp](#PageNumberStamp-com.aspose.pdf.facades.FormattedText-) | 初始化 {@code PageNumberStamp} 类的新实例。格式设置为 "#"。 |
| [PageNumberStamp](#PageNumberStamp-java.lang.String-) | 初始化 {@code PageNumberStamp} 类的新实例。格式设置为 "#"。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getFormat](#getFormat--) | 获取用于标记页码的字符串值。该值必须包含字符 '#'，在标记过程中会被页码替换。 |
| [getNumberingStyle](#getNumberingStyle--) | 此标记使用的编号样式。 |
| [getStartingNumber](#getStartingNumber--) | 获取起始页的页码值。其他页将从该值开始编号。 |
| [put](#put-com.aspose.pdf.Page-) | 添加页码。 |
| [setFormat](#setFormat-java.lang.String-) | 设置用于标记页码的字符串值。该值必须包含字符 '#'，在标记过程中会被页码替换。 |
| [setNumberingStyle](#setNumberingStyle-com.aspose.pdf.NumberingStyle-) | 此标记使用的编号样式。 |
| [setStartingNumber](#setStartingNumber-int-) | 设置起始页的页码值。其他页将从该值开始编号。 |

### PageNumberStamp {#PageNumberStamp--}
```
public PageNumberStamp()
```

初始化 {@code PageNumberStamp} 类的新实例。格式设置为 "#"。

### PageNumberStamp {#PageNumberStamp-com.aspose.pdf.facades.FormattedText-}
初始化 {@code PageNumberStamp} 类的新实例。格式设置为 "#"。

### PageNumberStamp {#PageNumberStamp-java.lang.String-}
初始化 {@code PageNumberStamp} 类的新实例。格式设置为 "#"。

### getFormat {#getFormat--}
```
public String getFormat()
```

获取用于标记页码的字符串值。该值必须包含字符 '#'，在标记过程中会被页码替换。

**Returns:**
字符串值

### getNumberingStyle {#getNumberingStyle--}
```
public NumberingStyle getNumberingStyle()
```

此标记使用的编号样式。

**Returns:**
NumberingStyle 值 @see NumberingStyle

### getStartingNumber {#getStartingNumber--}
```
public int getStartingNumber()
```

获取起始页的页码值。其他页将从该值开始编号。

**Returns:**
int 值

### put {#put-com.aspose.pdf.Page-}
添加页码。

### setFormat {#setFormat-java.lang.String-}
设置用于标记页码的字符串值。该值必须包含字符 '#'，在标记过程中会被页码替换。

### setNumberingStyle {#setNumberingStyle-com.aspose.pdf.NumberingStyle-}
此标记使用的编号样式。

### setStartingNumber {#setStartingNumber-int-}
```
public void setStartingNumber(int value)
```

设置起始页的页码值。其他页将从该值开始编号。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |
