---
title: Class VectorStoreFileBatchFileListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.VectorStoreFileBatchFileListQueryParameters klass. Frågeparametrar objekt för att lista vektorbutikens batchfiler
type: docs
weight: 1290
url: /sv/net/aspose.pdf.ai/vectorstorefilebatchfilelistqueryparameters/
---
## VectorStoreFileBatchFileListQueryParameters klass

Frågeparametrar objekt för att lista vektorbutikens batchfiler.

```csharp
public class VectorStoreFileBatchFileListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [VectorStoreFileBatchFileListQueryParameters](vectorstorefilebatchfilelistqueryparameters/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Hämtar eller sätter en markör för användning i paginering. after är ett objekt-ID som definierar din plats i listan. Till exempel, om du gör en listförfrågan och får 100 objekt, som slutar med obj_foo, kan din efterföljande anrop inkludera after=obj_foo för att hämta nästa sida av listan. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Hämtar eller sätter en markör för användning i paginering. before är ett objekt-ID som definierar din plats i listan. Till exempel, om du gör en listförfrågan och får 100 objekt, som slutar med obj_foo, kan din efterföljande anrop inkludera before=obj_foo för att hämta föregående sida av listan. |
| [Filter](../../aspose.pdf.ai/vectorstorefilebatchfilelistqueryparameters/filter/) { get; set; } | Hämtar eller sätter ett filter efter filstatus. En av in_progress, completed, failed, cancelled. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Hämtar eller sätter en gräns för antalet objekt som ska returneras. Limit kan variera mellan 1 och 100, och standardvärdet är 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Hämtar eller sätter sorteringsordning efter created_at tidsstämpeln för objekten. asc för stigande ordning och desc för fallande ordning. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/vectorstorefilebatchfilelistqueryparameters/getqueryparameters/)() | Hämtar frågeparametrarna för att lista butikens batchfiler. |

### Se Även

* klass [BaseListQueryParameters](../baselistqueryparameters/)
* gränssnitt [IQueryParameters](../iqueryparameters/)
* namnrymd [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* sammansättning [Aspose.PDF](../../)