---
title: "DuplexKind"
linktitle: "DuplexKind"
second_title: "Aspose.PDF for Java API 参考"
description: "指定打印机的双面设置。"
type: docs
weight: 20
url: /zh/java/com.aspose.pdf.printing/duplexkind/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.DuplexKind

```
public class DuplexKind extends Object
```

指定打印机的双面设置。

## 字段

| 字段 | 描述 |
| --- | --- |
| [Default](#Default) | 打印机的默认双面设置。 |
| [Horizontal](#Horizontal) | 双面，横向打印。 |
| [Simplex](#Simplex) | 单面打印。 |
| [Vertical](#Vertical) | 双面，纵向打印。 |

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DuplexKind](#DuplexKind--) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getNames](#getNames--) | Duplex 类型名称数组 |
| [toString](#toString-int-) | Duplex 类型名称 |

### Default {#Default}
```
public static final int Default
```

打印机的默认双面设置。

### Horizontal {#Horizontal}
```
public static final int Horizontal
```

双面，横向打印。

### Simplex {#Simplex}
```
public static final int Simplex
```

单面打印。

### Vertical {#Vertical}
```
public static final int Vertical
```

双面，纵向打印。

### DuplexKind {#DuplexKind--}
```
public DuplexKind()
```



### getNames {#getNames--}
```
public static String [] getNames()
```

Duplex 类型名称数组

**Returns:**
String[] 对象

### toString {#toString-int-}
```
public static String toString(int pdfPrintRange)
```

Duplex 类型名称

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pdfPrintRange |  | PaperKind 元素 |

**Returns:**
纸张格式名称
