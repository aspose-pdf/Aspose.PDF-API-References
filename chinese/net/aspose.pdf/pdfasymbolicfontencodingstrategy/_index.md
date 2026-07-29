---
title: "类 PdfASymbolicFontEncodingStrategy"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.PdfASymbolicFontEncodingStrategy 类。此类描述了可用于调优在 TrueType 符号字体拥有多个编码时复制编码数据过程的规则。某些 PDF 文档在转换为 PDF/A 格式后可能会出现错误 “More than one encoding in symbolic TrueType fonts cmap”。导致此错误的原因是所有 TrueType 符号字体在其内部数据中都有一个特殊的 cmap 表。该表将字符代码映射到字形索引，并且可能包含描述所使用编码的不同子表。有关 cmap 表的高级信息，请参阅 https//developer.apple.com/fonts/TrueTypeReferenceManual/RM06/Chap6cmap.html。通常 cmap 表包含多个编码子表，但 PDF/A 标准要求在 PDF/A 文档中该字体只能保留一个编码子表，或者在该字体的子表中必须存在一个 30 编码子表。关键问题在于应从其他子表中取哪些数据复制到目标编码表 30。大多数字体的 cmap 表结构良好，所有编码子表之间完全一致。但有些字体的 cmap 表存在冲突，例如一个子表为 Unicode 100 提供字形索引 100，而另一个子表为相同的 Unicode 100 提供字形索引 200。为解决此类问题需要特殊策略。默认使用的策略是查找 mac 子表 10。如果找到该表，则仅使用其数据填充目标表 30；如果未找到 mac 子表，则遍历除 30 之外的所有子表，并将数据复制到目标 30 子表。此外，仅在目标表当前未包含该 Unicode 时，才会将每个 Unicode‑glyph 索引的映射复制到目标表。因此，例如如果第一个子表为 Unicode 100 提供字形索引 100，而下一个子表为相同的 Unicode 100 提供字形索引 200，则仅会复制第一个子表的 Unicode 100‑字形索引 100 数据。每个前置子表均优先于后续子表。PdfASymbolicFontEncodingStrategy 的属性有助于调节默认行为。如果设置了类型为 CMapEncodingTableType 的属性 PreferredCmapEncodingTable，则相关子表将在优先级上高于 mac 子表 10。枚举 CMapEncodingTableType 中的值 MacTable 在此情况下没有意义，因为它指向同一个默认使用的 mac 子表 10。属性 CmapEncodingTablesPriorityQueue 会丢弃对任何子表的所有优先级。如果设置了此属性，则仅使用声明队列中的子表，按指定顺序使用。如果未找到指定的子表，则会使用所有子表的默认遍历以及上述复制策略。对象 QueueItem 指定使用的编码子表。该子表可以通过成员 PlatformID、PlatformSpecificId 的组合或通过 CMapEncodingTableType 枚举来设置。当字体没有 30 子表时，将使用其他子表以保持 PDF/A 兼容性。子表的选择遵循前述相同规则，即使用 PreferredCmapEncodingTable 和 CmapEncodingTablesPriorityQueue 属性来确定最终子表；如果字体既没有请求的子表，也没有其他可用子表，则会使用任何现存的子表。"
type: docs
weight: 8470
url: /zh/net/aspose.pdf/pdfasymbolicfontencodingstrategy/
---
## PdfASymbolicFontEncodingStrategy class

此类描述了可用于微调复制编码数据过程的规则，适用于 TrueType 符号字体拥有多个编码的情况。某些 PDF 文档在转换为 PDF/A 格式后可能会出现错误 \"More than one encoding in symbolic TrueType font's cmap\"。导致此错误的原因是什么？所有 TrueType 符号字体在其内部数据中都有特殊的 \"cmap\" 表。该表将字符码映射到字形索引，并且可能包含描述所使用编码的不同子表。请参阅 https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html 获取关于 cmap 表的高级信息。通常 cmap 表包含多个编码子表，但 PDF/A 标准要求在 PDF/A 文档中该字体只能保留一个编码子表，或者在该字体的子表中必须存在一个 (3,0) 编码子表。关键问题是——应从其他子表中提取哪些数据复制到目标编码表 (3,0)？大多数字体的 cmap 表是\'良构\'的，即每个编码子表都与其他子表完全一致。但有些字体的 cmap 表存在冲突，例如一个子表为 Unicode 100 提供字形索引 100，而另一个子表为同一 Unicode 100 提供字形索引 200。为解决此类问题需要特殊策略。默认使用以下策略：查找 mac 子表 (1,0)。如果找到该表，则仅使用其数据填充目标表 (3,0)。如果未找到 mac 子表，则遍历除 (3,0) 之外的所有子表，并将数据复制到目标 (3,0) 子表。且仅当目标表当前未包含某个 Unicode 时，才会复制该 Unicode（Unicode，字形索引）的映射。因此，例如如果第一个子表为 Unicode 100 提供字形索引 100，而下一个子表为同一 Unicode 100 提供字形索引 200，则只会复制第一个子表的数据（unicode=100，字形索引=100）。因此每个前面的子表优先于后面的子表。类 `PdfASymbolicFontEncodingStrategy` 的属性可用于微调默认行为。如果设置了属性 [`PreferredCmapEncodingTable`](./preferredcmapencodingtable/)（类型为 [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/)），则相关子表将在优先级上高于 mac 子表 (1,0)。枚举 [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) 中的值 'MacTable' 在此情况下没有意义，因为它指向同一 mac 子表 (1,0)，该子表默认已使用。属性 [`CmapEncodingTablesPriorityQueue`](./cmapencodingtablespriorityqueue/) 会丢弃所有子表的优先级。如果设置了此属性，则仅按声明的队列顺序使用这些子表。如果未找到指定的子表，则会使用所有子表的默认迭代并采用上述复制策略。对象 [`QueueItem`](../pdfasymbolicfontencodingstrategy.queueitem/) 指定使用的编码子表。该子表可以通过成员组合（PlatformID、PlatformSpecificId）或通过枚举 [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) 来设置。如果字体没有 (3,0) 子表，则会使用其他子表以保持 PDF/A 兼容性。子表的选择遵循前述相同规则，因此会使用 [`PreferredCmapEncodingTable`](./preferredcmapencodingtable/) 和 [`CmapEncodingTablesPriorityQueue`](./cmapencodingtablespriorityqueue/) 属性来确定最终子表；如果字体不存在请求的子表，则会使用任何现有子表。

```csharp
public class PdfASymbolicFontEncodingStrategy
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor)() | 构造函数。设置默认子表 (mac 1,0) |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor_1)(CMapEncodingTableType) | 构造函数 |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor_2)(Queue&lt;QueueItem&gt;) | 构造函数 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CmapEncodingTablesPriorityQueue](../../aspose.pdf/pdfasymbolicfontencodingstrategy/cmapencodingtablespriorityqueue/) { get; set; } | 指定要处理的编码子表队列。 |
| [PreferredCmapEncodingTable](../../aspose.pdf/pdfasymbolicfontencodingstrategy/preferredcmapencodingtable/) { get; set; } | 指定将在 mac 子表 (1,0) 之前使用的子表。枚举 [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) 中的值 'MacTable' 在此情况下没有意义。 |

### 另请参见

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


