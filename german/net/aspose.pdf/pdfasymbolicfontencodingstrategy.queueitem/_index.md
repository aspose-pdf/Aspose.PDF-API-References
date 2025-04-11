---
title: Class PdfASymbolicFontEncodingStrategy.QueueItem
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfASymbolicFontEncodingStrategyQueueItem-Klasse. Gibt die Kodierungssubtabelle an. Jede Kodierungssubtabelle hat eine einzigartige Kombination von Parametern PlatformID PlatformSpecificId. Die Enumeration [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) und die Eigenschaft [`CMapEncodingTable`](./cmapencodingtable/) wurden implementiert, um die benötigte Kodierungssubtabelle einfacher festzulegen.
type: docs
weight: 8340
url: /de/net/aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/
---
## Klasse PdfASymbolicFontEncodingStrategy.QueueItem

Gibt die Kodierungssubtabelle an. Jede Kodierungssubtabelle hat eine einzigartige Kombination von Parametern (PlatformID, PlatformSpecificId). Die Enumeration [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) und die Eigenschaft [`CMapEncodingTable`](./cmapencodingtable/) wurden implementiert, um die benötigte Kodierungssubtabelle einfacher festzulegen.

```csharp
public class QueueItem
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor)() | Konstruktor, gibt standardmäßig die mac-Subtabelle (1,0) an |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor_1)(CMapEncodingTableType) | Konstruktor |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor_2)(ushort, ushort) | Konstruktor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CMapEncodingTable](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/cmapencodingtable) { get; set; } | Gibt die Kodierungssubtabelle über die Enumeration [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) an |
| [PlatformId](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/platformid) { get; set; } | Plattform-Identifikator für die Kodierungssubtabelle |
| [PlatformSpecificId](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/platformspecificid) { get; set; } | Plattform-spezifischer Kodierungsidentifikator für die Kodierungssubtabelle |

### Siehe auch

* Klasse [PdfASymbolicFontEncodingStrategy](../pdfasymbolicfontencodingstrategy/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)