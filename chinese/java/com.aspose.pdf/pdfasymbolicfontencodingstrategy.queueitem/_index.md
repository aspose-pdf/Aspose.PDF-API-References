---
title: "PdfASymbolicFontEncodingStrategy.QueueItem"
linktitle: "PdfASymbolicFontEncodingStrategy.QueueItem"
second_title: "Aspose.PDF for Java API 参考"
description: "指定编码子表。每个编码子表都有唯一的参数组合（PlatformID，PlatformSpecificID）。枚举 {@code CMapEncodingTableType} 和属性。"
type: docs
weight: 3700
url: /zh/java/com.aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfASymbolicFontEncodingStrategy.QueueItem

```
public static class PdfASymbolicFontEncodingStrategy.QueueItem extends Object
```

指定编码子表。每个编码子表都有唯一的参数组合 (PlatformID, PlatformSpecificID)。实现了枚举 {@code CMapEncodingTableType} 和属性 {@code CMapEncodingTable}，以便更容易设置所需的编码子表。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [QueueItem](#QueueItem--) | 构造函数，默认指定 mac 子表(1,0) |
| [QueueItem](#QueueItem-int-int-) | 构造函数 |
| [QueueItem](#QueueItem-short-) | 构造函数 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getCMapEncodingTable](#getCMapEncodingTable--) | 通过 {@code CMapEncodingTableType} 枚举指定编码子表 |
| [getPlatformId](#getPlatformId--) | 编码子表的平台标识符 |
| [getPlatformSpecificId](#getPlatformSpecificId--) | 编码子表的特定平台编码标识符 |
| [setCMapEncodingTable](#setCMapEncodingTable-short-) | 通过 {@code CMapEncodingTableType} 枚举指定编码子表 |
| [setPlatformId](#setPlatformId-int-) | 编码子表的平台标识符 |
| [setPlatformSpecificId](#setPlatformSpecificId-int-) | 编码子表的特定平台编码标识符 |

### QueueItem {#QueueItem--}
```
public QueueItem()
```

构造函数，默认指定 mac 子表(1,0)

### QueueItem {#QueueItem-int-int-}
```
public QueueItem(int platformID, int platformSpecificID)
```

构造函数

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| platformID |  | 编码子表的平台标识符 |
| platformSpecificID |  | 编码子表的特定平台编码标识符 |

### QueueItem {#QueueItem-short-}
```
public QueueItem(short cmapTable)
```

构造函数

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cmapTable |  | 编码子表 |

### getCMapEncodingTable {#getCMapEncodingTable--}
```
public short getCMapEncodingTable()
```

通过 {@code CMapEncodingTableType} 枚举指定编码子表

**Returns:**
编码子表

### getPlatformId {#getPlatformId--}
```
public int getPlatformId()
```

编码子表的平台标识符

**Returns:**
int 值

### getPlatformSpecificId {#getPlatformSpecificId--}
```
public int getPlatformSpecificId()
```

编码子表的特定平台编码标识符

**Returns:**
int 值

### setCMapEncodingTable {#setCMapEncodingTable-short-}
```
public void setCMapEncodingTable(short value)
```

通过 {@code CMapEncodingTableType} 枚举指定编码子表

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 编码子表 |

### setPlatformId {#setPlatformId-int-}
```
public void setPlatformId(int value)
```

编码子表的平台标识符

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setPlatformSpecificId {#setPlatformSpecificId-int-}
```
public void setPlatformSpecificId(int value)
```

编码子表的特定平台编码标识符

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |
