---
title: "PdfPrintRange"
linktitle: "PdfPrintRange"
second_title: "Aspose.PDF for Java API 参考"
description: "指定要打印的文档部分。"
type: docs
weight: 60
url: /zh/java/com.aspose.pdf.printing/pdfprintrange/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PdfPrintRange

```
public final class PdfPrintRange extends Object
```

指定要打印的文档部分。

## 字段

| 字段 | 描述 |
| --- | --- |
| [AllPages](#AllPages) | 所有页面已打印。 |
| [CurrentPage](#CurrentPage) | 当前显示的页面已打印 |
| [Selection](#Selection) | 已打印所选页面。 |
| [SomePages](#SomePages) | 已打印 FromPage 与 ToPage 之间的页面。 |

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfPrintRange](#PdfPrintRange--) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getNames](#getNames--) | 获取 PdfPrintRange 的字符串名称 |
| [toString](#toString-int-) | 获取 PdfPrintRange 元素的字符串名称 |

### AllPages {#AllPages}
```
public static final int AllPages
```

所有页面已打印。

### CurrentPage {#CurrentPage}
```
public static final int CurrentPage
```

当前显示的页面已打印

### Selection {#Selection}
```
public static final int Selection
```

已打印所选页面。

### SomePages {#SomePages}
```
public static final int SomePages
```

已打印 FromPage 与 ToPage 之间的页面。

### PdfPrintRange {#PdfPrintRange--}
```
public PdfPrintRange()
```



### getNames {#getNames--}
```
public static String [] getNames()
```

获取 PdfPrintRange 的字符串名称

**Returns:**
String[] 对象

### toString {#toString-int-}
```
public static String toString(int pdfPrintRange)
```

获取 PdfPrintRange 元素的字符串名称

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pdfPrintRange |  | PdfPrintRange 元素 |

**Returns:**
String 对象 @see PdfPrintRange
