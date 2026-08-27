---
title: "PdfASymbolicFontEncodingStrategy"
linktitle: "PdfASymbolicFontEncodingStrategy"
second_title: "Aspose.PDF for Java API 参考"
description: "此类描述了可用于调优复制编码数据过程的规则，适用于 TrueType 符号字体具有多个编码的情况。某些 PDF 文档之后。"
type: docs
weight: 3690
url: /zh/java/com.aspose.pdf/pdfasymbolicfontencodingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfASymbolicFontEncodingStrategy

```
public class PdfASymbolicFontEncodingStrategy extends Object
```

此类描述可用于调节在 TrueType 符号字体拥有多个编码时复制编码数据过程的规则。某些 PDF 文档在转换为 PDF/A 格式后可能会出现错误 "More than one encoding in symbolic TrueType font's cmap"。导致此错误的原因是什么？所有 TrueType 符号字体在其内部数据中都有特殊的 "cmap" 表。该表将字符代码映射到字形索引。该表还可能包含描述所使用编码的不同编码子表。有关 cmap 表的高级信息，请参阅 https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html。通常 cmap 表包含多个编码子表，但 PDF/A 标准要求在 PDF/A 文档中该字体只能保留一个编码子表，或者在该字体的子表中必须包含一个 (3,0) 编码子表。关键问题是——必须从其他子表中获取哪些数据复制到目标编码表 (3,0)？大多数字体拥有“良好构造”的 cmap 表，其中每个编码子表都与其他子表完全一致。但有些字体的 cmap 表存在冲突——例如，一个子表为 Unicode 100 提供字形索引 100，而另一个子表为相同的 Unicode 100 提供字形索引 200。为解决此问题需要特殊策略。默认使用以下策略：查找 mac 子表 (1,0)。如果找到该表，则仅使用此数据填充目标表 (3,0)。如果未找到 mac 子表，则遍历除 (3,0) 之外的所有子表，并将数据复制到目标 (3,0) 子表。此外，仅当目标表当前不包含某个 unicode 时，才会将每个 unicode（unicode，字形索引）的映射复制到目标表中。因此，例如如果第一个子表为 Unicode 100 提供字形索引 100，而下一个子表为相同的 Unicode 100 提供字形索引 200，则仅会复制第一个子表（unicode=100，字形索引=100）的数据。因此，每个前面的子表优先于后面的子表。此类的属性 { PdfASymbolicFontEncodingStrategy} 有助于调节默认行为。如果设置了类型为 { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} 的属性 {PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ { PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable})，则相关子表将在优先级上高于 mac 子表 (1,0)。枚举 {PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} 中的值 'MacTable' 在此情况下没有意义，因为它指向同一个默认使用的 mac 子表 (1,0)。属性 {CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ {PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) 会丢弃所有子表的优先级。如果设置了此属性，则仅按指定顺序使用声明队列中的子表。如果未找到指定的子表，则会使用所有子表的默认遍历以及上述复制策略。对象 { PdfASymbolicFontEncodingStrategy.QueueItem} 指定使用的编码子表。可以通过成员组合（PlatformID、PlatformSpecificId）或通过枚举 { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} 来设置此子表。如果字体没有 (3,0) 子表，则会使用其他子表以保持 PDF/A 兼容性。所使用的子表选择遵循前述相同规则，即使用 {@code PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ {PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) 和 {@code CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ { PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) 属性来确定最终子表；如果字体也没有请求的子表，则会使用任何现有的子表。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfASymbolicFontEncodingStrategy](#PdfASymbolicFontEncodingStrategy--) | 构造函数。设置默认子表 (mac 1,0) |
| [PdfASymbolicFontEncodingStrategy](#PdfASymbolicFontEncodingStrategy-com.aspose.ms.System.Collections.Generic.Queue-) | 构造函数。设置默认子表 (mac 1,0) |
| [PdfASymbolicFontEncodingStrategy](#PdfASymbolicFontEncodingStrategy-short-) | 构造函数 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getCmapEncodingTablesPriorityQueue](#getCmapEncodingTablesPriorityQueue--) | 指定要处理的编码子表队列。 |
| [getPreferredCmapEncodingTable](#getPreferredCmapEncodingTable--) | 指定将在优先于 mac 子表 (1,0) 时使用的子表。在此情况下，枚举 {@code QueueItem.CMapEncodingTableType} 中的值 'MacTable' 没有意义。 |
| [setCmapEncodingTablesPriorityQueue](#setCmapEncodingTablesPriorityQueue-com.aspose.ms.System.Collections.Generic.Queue-) | 指定要处理的编码子表队列。 |
| [setPreferredCmapEncodingTable](#setPreferredCmapEncodingTable-short-) | 指定将在优先于 mac 子表 (1,0) 时使用的子表。在此情况下，枚举 {@code QueueItem.CMapEncodingTableType} 中的值 'MacTable' 没有意义。 |

### PdfASymbolicFontEncodingStrategy {#PdfASymbolicFontEncodingStrategy--}
```
public PdfASymbolicFontEncodingStrategy()
```

构造函数。设置默认子表 (mac 1,0)

### PdfASymbolicFontEncodingStrategy {#PdfASymbolicFontEncodingStrategy-com.aspose.ms.System.Collections.Generic.Queue-}
构造函数。设置默认子表 (mac 1,0)

### PdfASymbolicFontEncodingStrategy {#PdfASymbolicFontEncodingStrategy-short-}
```
public PdfASymbolicFontEncodingStrategy(short preferredEncodingTable)
```

构造函数

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| preferredEncodingTable |  | 将在优先于 mac 子表 (1,0) 时使用的编码子表 @see PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType |

### getCmapEncodingTablesPriorityQueue {#getCmapEncodingTablesPriorityQueue--}
```
public com.aspose.ms.System.Collections.Generic.Queue< PdfASymbolicFontEncodingStrategy.QueueItem > getCmapEncodingTablesPriorityQueue()
```

指定要处理的编码子表队列。

**Returns:**
QueueItem 的队列

### getPreferredCmapEncodingTable {#getPreferredCmapEncodingTable--}
```
public short getPreferredCmapEncodingTable()
```

指定将在优先于 mac 子表 (1,0) 时使用的子表。在此情况下，枚举 {@code QueueItem.CMapEncodingTableType} 中的值 'MacTable' 没有意义。

**Returns:**
CMapEncodingTableType 元素 @see PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType

### setCmapEncodingTablesPriorityQueue {#setCmapEncodingTablesPriorityQueue-com.aspose.ms.System.Collections.Generic.Queue-}
指定要处理的编码子表队列。

### setPreferredCmapEncodingTable {#setPreferredCmapEncodingTable-short-}
```
public void setPreferredCmapEncodingTable(short value)
```

指定将在优先于 mac 子表 (1,0) 时使用的子表。在此情况下，枚举 {@code QueueItem.CMapEncodingTableType} 中的值 'MacTable' 没有意义。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | preferredEncodingTable 编码子表，将在优先于 mac 子表 (1,0) 时使用 @see PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType |
