---
title: Class VectorStoreResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.VectorStoreResponse klass. Vektorbutiksobjektet
type: docs
weight: 1390
url: /sv/net/aspose.pdf.ai/vectorstoreresponse/
---
## VectorStoreResponse klass

Vektorbutiksobjektet.

```csharp
public class VectorStoreResponse : BaseResponse, IEntityId, IStatus
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [VectorStoreResponse](vectorstoreresponse/)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/vectorstoreresponse/createdat/) { get; set; } | Hämtar eller ställer in Unix-tidsstämpeln (i sekunder) för när vektorbutiken skapades. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Hämtar eller ställer in svaret detaljer. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Hämtar eller ställer in HTTP-svarsfel. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Hämtar eller ställer in felinformationen. |
| [ExpiresAfter](../../aspose.pdf.ai/vectorstoreresponse/expiresafter/) { get; set; } | Hämtar eller ställer in utgångspolicyn för en vektorbutik. |
| [ExpiresAt](../../aspose.pdf.ai/vectorstoreresponse/expiresat/) { get; set; } | Hämtar eller ställer in Unix-tidsstämpeln (i sekunder) för när vektorbutiken kommer att gå ut. |
| [FileCounts](../../aspose.pdf.ai/vectorstoreresponse/filecounts/) { get; set; } | Hämtar eller ställer in antalet filer som har bearbetats. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Hämtar eller ställer in HTTP-svarshuvuden. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Hämtar eller ställer in HTTP-statuskoden. |
| [Id](../../aspose.pdf.ai/vectorstoreresponse/id/) { get; set; } | Hämtar eller ställer in identifieraren, som kan refereras i API-slutpunkter. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indikerar om svaret var framgångsrikt. |
| [LastActiveAt](../../aspose.pdf.ai/vectorstoreresponse/lastactiveat/) { get; set; } | Hämtar eller ställer in Unix-tidsstämpeln (i sekunder) för när vektorbutiken senast var aktiv. |
| [Metadata](../../aspose.pdf.ai/vectorstoreresponse/metadata/) { get; set; } | Hämtar eller ställer in en uppsättning av 16 nyckel-värde-par som kan kopplas till ett objekt. Detta kan vara användbart för att lagra ytterligare information om objektet i ett strukturerat format. Nycklar kan vara maximalt 64 tecken långa och värden kan vara maximalt 512 tecken långa. |
| [Name](../../aspose.pdf.ai/vectorstoreresponse/name/) { get; set; } | Hämtar eller ställer in namnet på vektorbutiken. |
| [Object](../../aspose.pdf.ai/vectorstoreresponse/object/) { get; set; } | Hämtar eller ställer in objekttypen, som alltid är vector_store. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Hämtar felorsaksfrasen. |
| [Status](../../aspose.pdf.ai/vectorstoreresponse/status/) { get; set; } | Hämtar eller ställer in statusen för vektorbutiken, som kan vara antingen expired, in_progress eller completed. En status av completed indikerar att vektorbutiken är redo att användas. |
| [UsageBytes](../../aspose.pdf.ai/vectorstoreresponse/usagebytes/) { get; set; } | Hämtar eller ställer in det totala antalet byte som används av filerna i vektorbutiken. |

### Se Även

* klass [BaseResponse](../baseresponse/)
* gränssnitt [IEntityId](../ientityid/)
* gränssnitt [IStatus](../istatus/)
* namnrymd [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* samling [Aspose.PDF](../../)