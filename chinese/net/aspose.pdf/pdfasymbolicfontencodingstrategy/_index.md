---
title: Class PdfASymbolicFontEncodingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfASymbolicFontEncodingStrategy 类。该类描述了用于调整在 TrueType 符号字体具有多种编码时复制编码数据过程的规则。有些 PDF 文档转换为 PDF/A 格式后可能会报错 "More than one encoding in symbolic TrueType font's cmap"。该错误的原因是什么？所有 TrueType 符号字体在其内部数据中都有一个特殊表 "cmap"，该表将字符代码映射到字形索引，并且该表可以包含描述所用编码的不同编码子表。请参阅 https//developer.apple.com/fonts/TrueTypeReferenceManual/RM06/Chap6cmap.html 获取有关 cmap 表的高级信息。通常 cmap 表包含多个编码子表，但 PDF/A 标准要求在 PDF/A 文档中该字体只能保留一个编码子表，或在该字体的子表中必须存在 (3,0) 编码子表。这里的关键问题是——应从其他子表中复制哪些数据到目标编码表 (3,0)？大多数字体的 cmap 表都是“格式良好”的，其中每个编码子表彼此完全一致。但有些字体的 cmap 表存在冲突——例如，一个子表对于 unicode 100 使用字形索引 100，而另一个子表对于相同 unicode 100 使用字形索引 200。为了解决这些问题，需要采用特殊策略。默认情况下，采用以下策略：查找 mac 子表 (1,0)。如果找到该表，则仅使用其数据填充目标表 (3,0)；如果未找到 mac 子表，则迭代除 (3,0) 以外的所有子表，并将数据复制到目标 (3,0) 子表。此外，每个 (unicode, glyph index) 的映射仅在目标表当前不存在该 unicode 时复制到目标表中。例如，如果第一个子表对于 unicode 100 的字形索引为 100，而下一个子表对于相同 unicode 100 的字形索引为 200，则只会复制来自第一个子表的 (unicode=100, glyph index=100) 数据。因此，每个前面的子表都优先于后面的子表。该类 PdfASymbolicFontEncodingStrategy 的属性有助于调整默认行为。如果将类型为 CMapEncodingTableType 的属性 PreferredCmapEncodingTable 设置为特定值，则相应的子表将优先于 mac 子表 (1,0) 被使用。在这种情况下，枚举 CMapEncodingTableType 中的值 'MacTable' 没有意义，因为它指向默认使用的 mac 子表 (1,0)。属性 CmapEncodingTablesPriorityQueue 会丢弃所有子表的优先级；如果设置了此属性，则仅会按照指定顺序使用声明队列中的子表。如果未找到指定的子表，则将采用上述的默认迭代和复制策略。对象 QueueItem 指定了所使用的编码子表。该子表可以通过成员 (PlatformID, PlatformSpecificId) 的组合或通过 CMapEncodingTableType 枚举设置。如果字体没有 (3,0) 子表，则将使用其他子表来维持 PDF/A 兼容性。选择使用哪个子表的规则与前述规则相同，因此属性 PreferredCmapEncodingTable 和 CmapEncodingTablesPriorityQueue 用于确定最终子表，如果字体中也没有请求的子表，则将使用任何存在的子表。
type: docs
weight: 8330
url: /zh/net/aspose.pdf/pdfasymbolicfontencodingstrategy/
---
## PdfASymbolicFontEncodingStrategy 类

该类描述了用于调整在 TrueType 符号字体具有多种编码时复制编码数据过程的规则。有些 PDF 文档转换为 PDF/A 格式后可能会报错 "More than one encoding in symbolic TrueType font's cmap"。该错误的原因是什么？所有 TrueType 符号字体在其内部数据中都有一个特殊表 "cmap"，该表将字符代码映射到字形索引，而且该表可能包含描述所使用编码的不同编码子表。有关 cmap 表的高级信息，请参阅 https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html。通常 cmap 表包含多个编码子表，但 PDF/A 标准要求在 PDF/A 文档中该字体只能保留一个编码子表，或该字体的子表中必须存在一个 (3,0) 编码子表。这里的关键问题是 —— 应从其他子表中复制哪些数据到目标编码表 (3,0)？大多数字体拥有“格式良好”的 cmap 表，其中每个编码子表彼此完全一致。但有些字体的 cmap 表存在冲突 —— 例如，一个子表对于 unicode 100 的字形索引为 100，而另一个子表对于相同的 unicode 100 的字形索引为 200。为了解决这些问题，需要采用特殊策略。默认情况下，采用以下策略：查找 mac 子表 (1,0)。如果找到该表，则仅使用其数据填充目标表 (3,0)；如果未找到 mac 子表，则迭代除 (3,0) 外的所有子表，并将数据复制到目标 (3,0) 子表。此外，每个 (unicode, glyph index) 的映射仅在目标表当前不存在该 unicode 时复制到目标表中。例如，如果第一个子表对于 unicode 100 的字形索引为 100，而下一个子表对于相同 unicode 100 的字形索引为 200，则只会复制来自第一个子表的 (unicode=100, glyph index=100) 数据。因此，每个前面的子表都优先于后面的子表。类 `PdfASymbolicFontEncodingStrategy` 的属性有助于调整默认行为。如果将类型为 [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) 的属性 [`PreferredCmapEncodingTable`](./preferredcmapencodingtable/) 设置为特定值，则相应的子表将优先于 mac 子表 (1,0) 被使用。在这种情况下，枚举 [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) 中的值 'MacTable' 没有意义，因为它指向默认使用的 mac 子表 (1,0)。属性 [`CmapEncodingTablesPriorityQueue`](./cmapencodingtablespriorityqueue/) 会丢弃所有子表的优先级；如果设置了此属性，则仅会按照指定顺序使用声明队列中的子表。如果未找到指定的子表，则将采用上述的默认迭代和复制策略。对象 [`QueueItem`](../pdfasymbolicfontencodingstrategy.queueitem/) 指定了所使用的编码子表。该子表可以通过成员 (PlatformID, PlatformSpecificId) 的组合或通过枚举 [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) 设置。如果字体没有 (3,0) 子表，则将使用其他子表来维持 PDF/A 兼容性。选择使用哪个子表的规则与前述规则相同，因此 [`PreferredCmapEncodingTable`](./preferredcmapencodingtable/) 和 [`CmapEncodingTablesPriorityQueue`](./cmapencodingtablespriorityqueue/) 属性用于确定最终子表，如果字体中也没有请求的子表，则将使用任何存在的子表。

```csharp
public class PdfASymbolicFontEncodingStrategy
```

## 构造函数

| Name | Description |
| --- | --- |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor)() | 构造函数。设置默认子表 (mac 1,0) |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor_1)(CMapEncodingTableType) | 构造函数 |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor_2)(Queue&lt;QueueItem&gt;) | 构造函数 |

## 属性

| Name | Description |
| --- | --- |
| [CmapEncodingTablesPriorityQueue](../../aspose.pdf/pdfasymbolicfontencodingstrategy/cmapencodingtablespriorityqueue/) { get; set; } | 指定要处理的编码子表队列。 |
| [PreferredCmapEncodingTable](../../aspose.pdf/pdfasymbolicfontencodingstrategy/preferredcmapencodingtable/) { get; set; } | 指定将优先于 mac 子表 (1,0) 使用的子表。在这种情况下，枚举 [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) 中的值 'MacTable' 没有意义。 |

### 另请参阅

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)