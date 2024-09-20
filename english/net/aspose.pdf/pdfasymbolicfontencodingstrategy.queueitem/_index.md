---
title: Class PdfASymbolicFontEncodingStrategy.QueueItem
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfASymbolicFontEncodingStrategyQueueItem class. Specifies encoding subtable. Each encoding subtable has unique combination of parameters PlatformID PlatformSpecificId. Enumeration CMapEncodingTableType and property CMapEncodingTable were implemented to make easier set of encoding subtable needed
type: docs
weight: 6600
url: /net/aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/
---
## PdfASymbolicFontEncodingStrategy.QueueItem class

Specifies encoding subtable. Each encoding subtable has unique combination of parameters (PlatformID, PlatformSpecificId). Enumeration [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) and property [`CMapEncodingTable`](./cmapencodingtable/) were implemented to make easier set of encoding subtable needed.

```csharp
public class QueueItem
```

## Constructors

| Name | Description |
| --- | --- |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor)() | Constructor, specifies mac subtable(1,0) by default |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor_1)(CMapEncodingTableType) | Constructor |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor_2)(ushort, ushort) | Constructor |

## Properties

| Name | Description |
| --- | --- |
| [CMapEncodingTable](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/cmapencodingtable) { get; set; } | Specifies encoding subtable via [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/)enumeration |
| [PlatformId](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/platformid) { get; set; } | Platform identifier for encoding subtable |
| [PlatformSpecificId](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/platformspecificid) { get; set; } | Platform-specific encoding identifier for encoding subtable |

### See Also

* class [PdfASymbolicFontEncodingStrategy](../pdfasymbolicfontencodingstrategy/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


