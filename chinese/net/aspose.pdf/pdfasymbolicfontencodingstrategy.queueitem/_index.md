---
title: Class PdfASymbolicFontEncodingStrategy.QueueItem
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfASymbolicFontEncodingStrategyQueueItem 类。指定编码子表。每个编码子表具有唯一的参数组合 PlatformID PlatformSpecificId。枚举 [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) 和属性 [`CMapEncodingTable`](./cmapencodingtable/) 的实现旨在简化所需编码子表的设置。
type: docs
weight: 8340
url: /zh/net/aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/
---
## PdfASymbolicFontEncodingStrategy.QueueItem 类

指定编码子表。每个编码子表具有唯一的参数组合（PlatformID，PlatformSpecificId）。枚举 [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) 和属性 [`CMapEncodingTable`](./cmapencodingtable/) 的实现旨在简化所需编码子表的设置。

```csharp
public class QueueItem
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor)() | 构造函数，默认指定 mac 子表（1,0） |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor_1)(CMapEncodingTableType) | 构造函数 |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor_2)(ushort, ushort) | 构造函数 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CMapEncodingTable](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/cmapencodingtable) { get; set; } | 通过 [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) 枚举指定编码子表 |
| [PlatformId](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/platformid) { get; set; } | 编码子表的平台标识符 |
| [PlatformSpecificId](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/platformspecificid) { get; set; } | 编码子表的特定平台编码标识符 |

### 另请参阅

* 类 [PdfASymbolicFontEncodingStrategy](../pdfasymbolicfontencodingstrategy/)
* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)