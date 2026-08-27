---
title: "Classe PdfASymbolicFontEncodingStrategy.QueueItem"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.PdfASymbolicFontEncodingStrategyQueueItem. Specifica la sottotabella di codifica. Ogni sottotabella di codifica ha una combinazione unica di parametri PlatformID PlatformSpecificId. L'enumerazione CMapEncodingTableType e la proprietà CMapEncodingTable sono state implementate per semplificare la creazione della sottotabella di codifica necessaria."
type: docs
weight: 8480
url: /it/net/aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/
---
## PdfASymbolicFontEncodingStrategy.QueueItem class

Specifica la sottotabella di codifica. Ogni sottotabella di codifica ha una combinazione unica di parametri (PlatformID, PlatformSpecificId). L'enumerazione [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) e la proprietà [`CMapEncodingTable`](./cmapencodingtable/) sono state implementate per semplificare la creazione della sottotabella di codifica necessaria.

```csharp
public class QueueItem
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor)() | Costruttore, specifica la sottotabella mac (1,0) per impostazione predefinita |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor_1)(CMapEncodingTableType) | Costruttore |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor_2)(ushort, ushort) | Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CMapEncodingTable](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/cmapencodingtable) { get; set; } | Specifica la sottotabella di codifica tramite l'enumerazione [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) |
| [PlatformId](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/platformid) { get; set; } | Identificatore della piattaforma per la sottotabella di codifica |
| [PlatformSpecificId](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/platformspecificid) { get; set; } | Identificatore di codifica specifico della piattaforma per la sottotabella di codifica |

### Vedi anche

* class [PdfASymbolicFontEncodingStrategy](../pdfasymbolicfontencodingstrategy/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


