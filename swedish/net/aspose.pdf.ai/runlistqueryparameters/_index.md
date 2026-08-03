---
title: "Klass RunListQueryParameters"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.AI.RunListQueryParameters-klass. Objekt för frågeparametrar för att lista körningar"
type: docs
weight: 1070
url: /sv/net/aspose.pdf.ai/runlistqueryparameters/
---
## RunListQueryParameters class

Objekt för frågeparametrar för att lista körningar.

```csharp
public class RunListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [RunListQueryParameters](runlistqueryparameters/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Hämtar eller anger en markör för användning i paginering. after är ett objekt‑ID som definierar din position i listan. Till exempel, om du gör en listförfrågan och får 100 objekt, avslutade med obj_foo, kan ditt efterföljande anrop inkludera after=obj_foo för att hämta nästa sida av listan. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Hämtar eller anger en markör för användning i paginering. before är ett objekt‑ID som definierar din position i listan. Till exempel, om du gör en listförfrågan och får 100 objekt, avslutade med obj_foo, kan ditt efterföljande anrop inkludera before=obj_foo för att hämta föregående sida av listan. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Hämtar eller anger en gräns för antalet objekt som ska returneras. Gränsen kan ligga mellan 1 och 100, och standardvärdet är 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Hämtar eller anger sorteringsordning efter objektens created_at‑tidsstämpel. asc för stigande ordning och desc för fallande ordning. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/runlistqueryparameters/getqueryparameters/)() | Hämtar frågeparametrarna för att lista körningar. |

### Se även

* class [BaseListQueryParameters](../baselistqueryparameters/)
* interface [IQueryParameters](../iqueryparameters/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


