---
title: "PdfASymbolicFontEncodingStrategy"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "此类描述了可用于调节在 TrueType 符号字体拥有多个编码时复制编码数据过程的规则。某些 PDF 文档在转换为 PDF/A 格式后可能出现错误 More than one encoding in symbolic TrueType fonts cmap。导致此错误的原因是所有 TrueType 符号字体在其内部数据中都有一个特殊的 cmap 表。该表将字符代码映射到字形索引，并且可能包含描述所使用编码的不同子表。请参阅关于 cmap 表的高级信息：https//developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html。通常 cmap 表包含多个编码子表，但 PDF/A 标准要求在 PDF/A 文档中只能保留该字体的一个编码子表（30）。关键问题在于——必须从其他子表中提取哪些数据复制到目标编码表 30。大多数字体的 cmap 表结构良好，所有编码子表之间完全一致。但某些字体的 cmap 表存在冲突，例如一个子表为 Unicode 100 提供字形索引 100，而另一个子表为相同的 Unicode 100 提供字形索引 200。为解决此类问题需要特殊策略。默认使用的策略是查找 mac 子表 10。如果找到该表，则仅使用其数据填充目标表 30；如果未找到 mac 子表，则遍历除 30 之外的所有子表，并将数据复制到目标子表 30。仅当目标表当前没有对应的 Unicode 时，才会将每个 Unicode 的字形索引复制到目标表。因此，例如如果第一个子表为 Unicode 100 提供字形索引 100，而下一个子表为相同的 Unicode 100 提供字形索引 200，则仅会复制第一个子表的 Unicode 100 字形索引 100。每个前面的子表优先于后面的子表。PdfASymbolicFontEncodingStrategy 的属性帮助调节默认行为。如果设置属性 PreferredCmapEncodingTable（类型为 CMapEncodingTableType）则相关子表将在优先级上高于 mac 子表 10。枚举 CMapEncodingTableType 中的值 MacTable 在此情况下没有意义，因为它指向同一个 mac 子表 10，默认会使用该子表。属性 CmapEncodingTablesPriorityQueue 会丢弃所有子表的优先级。如果设置此属性，则仅使用声明队列中的子表，并按指定顺序使用。如果未找到指定的子表，则会使用上述默认的遍历所有子表并复制的策略。对象 QueueItem 指定使用的编码子表。该子表可以通过成员 PlatformID、PlatformSpecificId 的组合或通过 CMapEncodingTableType 枚举来设置。"
type: docs
weight: 1190
url: /zh/python-net/aspose.pdf/pdfasymbolicfontencodingstrategy/
---

## PdfASymbolicFontEncodingStrategy class

此类描述可用于调优复制编码数据过程的规则，适用于 TrueType 符号字体拥有多个编码的情况。<br/>            某些 PDF 文档在转换为 PDF/A 格式后可能出现错误<br/>            "符号 TrueType 字体的 cmap 中存在多个编码"。<br/>            该错误的原因是什么？所有 TrueType 符号字体在其内部数据中都有一个特殊的表 "cmap"。<br/>            该表将字符代码映射到字形索引。<br/>            此表可能包含不同的编码子表，描述所使用的编码。请参阅关于 cmap 表的高级信息：<br/>            https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html。<br/>            通常 cmap 表包含多个编码子表，但 PDF/A 标准要求在 PDF/A 文档中该字体只能保留一个编码子表 (3,0)。<br/>            关键问题在于——必须从其他子表中提取哪些数据复制到目标编码表 (3,0)？大多数字体拥有“良好构造”的 cmap 表，所有编码子表之间完全一致。<br/>            但有些字体的 cmap 表存在冲突——例如一个子表为 Unicode 100 提供字形索引 100，而另一个子表为相同的 Unicode 100 提供字形索引 200。<br/>            为解决此问题需要特殊策略。<br/>            默认使用以下策略：<br/>            查找 mac 子表 (1,0)。如果找到该表，仅使用其数据填充目标表 (3,0)。<br/>            如果未找到 mac 子表，则遍历除 (3,0) 之外的所有子表，并将数据复制到目标表 (3,0)。<br/>            同时，仅在目标表当前没有该 Unicode 时，才将每个 Unicode（unicode, 字形索引）的映射复制到目标表。<br/>            因此，例如如果第一个子表为 Unicode 100 提供字形索引 100，而下一个子表为相同的 Unicode 100 提供字形索引 200，则仅复制第一个子表（unicode=100, 字形索引=100）的数据。<br/>            每个之前的子表优先于后面的子表。<br/>            此类的属性 [PdfASymbolicFontEncodingStrategy](/pdf/python-net/aspose.pdf/pdfasymbolicfontencodingstrategy/) 有助于调节默认行为。<br/>            如果设置属性 [preferred_cmap_encoding_table](/pdf/python-net/aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/cmapencodingtabletype/) ，则相关子表将在优先级上高于 mac 子表 (1,0)。枚举 [CMapEncodingTableType](/pdf/python-net/aspose.pdf.pdfasymbolicfontencodingstrategy.queueitem/cmapencodingtabletype/) 中的值 "MacTable" 在此情况下没有意义，因为它指向同一个 mac 子表 (1,0)，该子表默认已使用。<br/>            属性 [None](/pdf/python-net/aspose.pdf/pdfasymbolicfontencodingstrategy/) 会放弃所有子表的优先级。<br/>            如果设置此属性，则仅按声明的队列顺序使用相应的子表。<br/>            如果未找到指定的子表，则会使用所有子表的默认遍历以及上述复制策略。<br/>            对象 [QueueItem](/pdf/python-net/aspose.pdf.pdfasymbolicfontencodingstrategy/queueitem/) 指定使用的编码子表。可以通过成员组合（PlatformID、PlatformSpecificId）或通过枚举 [CMapEncodingTableType](/pdf/python-net/aspose.pdf.pdfasymbolicfontencodingstrategy.queueitem/cmapencodingtabletype/) 来设置此子表。

PdfASymbolicFontEncodingStrategy 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| PdfASymbolicFontEncodingStrategy() | 构造函数。设置默认子表 (mac 1,0)。 |
| PdfASymbolicFontEncodingStrategy(preferred_encoding_table) | 初始化 PdfASymbolicFontEncodingStrategy 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| preferred_cmap_encoding_table | 指定将在优先于 mac 子表(1,0) 时使用的子表。来自<br/>枚举 [CMapEncodingTableType](/pdf/python-net/aspose.pdf.pdfasymbolicfontencodingstrategy.queueitem/cmapencodingtabletype/) 的值 'MacTable' 在此情况下没有意义。 |

### 另请参阅

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

