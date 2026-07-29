---
title: "类 PdfASymbolicFontEncodingStrategy.QueueItem"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.PdfASymbolicFontEncodingStrategyQueueItem 类。指定编码子表。每个编码子表具有 PlatformID 和 PlatformSpecificId 参数的唯一组合。实现了枚举 CMapEncodingTableType 和属性 CMapEncodingTable，以便更轻松地设置所需的编码子表。"
type: docs
weight: 8480
url: /zh/net/aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/
---
## PdfASymbolicFontEncodingStrategy.QueueItem class

指定编码子表。每个编码子表具有 (PlatformID, PlatformSpecificId) 参数的唯一组合。实现了枚举 [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) 和属性 [`CMapEncodingTable`](./cmapencodingtable/)，以便更轻松地设置所需的编码子表。

```csharp
public class QueueItem
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor)() | 构造函数，默认指定 mac 子表 (1,0)。 |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor_1)(CMapEncodingTableType) | 构造函数 |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor_2)(ushort, ushort) | 构造函数 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CMapEncodingTable](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/cmapencodingtable) { get; set; } | 通过枚举 [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) 指定编码子表。 |
| [PlatformId](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/platformid) { get; set; } | 编码子表的平台标识符 |
| [PlatformSpecificId](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/platformspecificid) { get; set; } | 编码子表的特定平台编码标识符 |

### 另请参见

* class [PdfASymbolicFontEncodingStrategy](../pdfasymbolicfontencodingstrategy/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


