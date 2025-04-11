---
title: Class PdfASymbolicFontEncodingStrategy.QueueItem
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfASymbolicFontEncodingStrategyQueueItem klass. Anger kodningssubtabell. Varje kodningssubtabell har en unik kombination av parametrar PlatformID PlatformSpecificId. Uppräkningen CMapEncodingTableType och egenskapen CMapEncodingTable implementerades för att underlätta uppsättningen av den nödvändiga kodningssubtabellen.
type: docs
weight: 8340
url: /sv/net/aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/
---
## PdfASymbolicFontEncodingStrategy.QueueItem klass

Anger kodningssubtabell. Varje kodningssubtabell har en unik kombination av parametrar (PlatformID, PlatformSpecificId). Uppräkningen [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) och egenskapen [`CMapEncodingTable`](./cmapencodingtable/) implementerades för att underlätta uppsättningen av den nödvändiga kodningssubtabellen.

```csharp
public class QueueItem
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor)() | Konstruktör, anger mac subtabell(1,0) som standard |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor_1)(CMapEncodingTableType) | Konstruktör |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor_2)(ushort, ushort) | Konstruktör |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CMapEncodingTable](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/cmapencodingtable) { get; set; } | Anger kodningssubtabell via [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) uppräkning |
| [PlatformId](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/platformid) { get; set; } | Plattformidentifierare för kodningssubtabell |
| [PlatformSpecificId](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/platformspecificid) { get; set; } | Plattformsspecifik kodningsidentifierare för kodningssubtabell |

### Se Även

* klass [PdfASymbolicFontEncodingStrategy](../pdfasymbolicfontencodingstrategy/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* samling [Aspose.PDF](../../)