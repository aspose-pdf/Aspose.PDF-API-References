---
title: Class RunListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.RunListQueryParameters klass. Frågeparametrar objekt för att lista körningar
type: docs
weight: 990
url: /sv/net/aspose.pdf.ai/runlistqueryparameters/
---
## RunListQueryParameters klass

Frågeparametrar objekt för att lista körningar.

```csharp
public class RunListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [RunListQueryParameters](runlistqueryparameters/)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Hämtar eller sätter en markör för användning i paginering. after är ett objekt-ID som definierar din plats i listan. Till exempel, om du gör en listförfrågan och får 100 objekt, som slutar med obj_foo, kan din efterföljande anrop inkludera after=obj_foo för att hämta nästa sida av listan. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Hämtar eller sätter en markör för användning i paginering. before är ett objekt-ID som definierar din plats i listan. Till exempel, om du gör en listförfrågan och får 100 objekt, som slutar med obj_foo, kan din efterföljande anrop inkludera before=obj_foo för att hämta föregående sida av listan. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Hämtar eller sätter en gräns för antalet objekt som ska returneras. Limit kan variera mellan 1 och 100, och standardvärdet är 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Hämtar eller sätter sorteringsordning efter created_at tidsstämpeln för objekten. asc för stigande ordning och desc för fallande ordning. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/runlistqueryparameters/getqueryparameters/)() | Hämtar frågeparametrarna för att lista körningar. |

### Se Även

* klass [BaseListQueryParameters](../baselistqueryparameters/)
* gränssnitt [IQueryParameters](../iqueryparameters/)
* namnrymd [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* sammansättning [Aspose.PDF](../../)