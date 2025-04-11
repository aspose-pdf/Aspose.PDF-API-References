---
title: Class VectorStoreFileResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.VectorStoreFileResponse klass. Ett vektorbutik filsvar
type: docs
weight: 1350
url: /sv/net/aspose.pdf.ai/vectorstorefileresponse/
---
## VectorStoreFileResponse klass

Ett vektorbutik filsvar.

```csharp
public class VectorStoreFileResponse : BaseResponse, IStatus
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [VectorStoreFileResponse](vectorstorefileresponse/)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/vectorstorefileresponse/createdat/) { get; set; } | Hämtar eller sätter Unix-tidsstämpeln (i sekunder) för när vektorbutikfilen skapades. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Hämtar eller sätter svardetaljen. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Hämtar eller sätter HTTP-svarsfel. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Hämtar eller sätter felinformationen. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Hämtar eller sätter HTTP-svarshuvuden. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Hämtar eller sätter HTTP-statuskoden. |
| [Id](../../aspose.pdf.ai/vectorstorefileresponse/id/) { get; set; } | Hämtar eller sätter identifieraren, som kan refereras i API-slutpunkter. /// |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indikerar om svaret var framgångsrikt. |
| [LastError](../../aspose.pdf.ai/vectorstorefileresponse/lasterror/) { get; set; } | Hämtar eller sätter det senaste felet som är kopplat till denna vektorbutikfil. Kommer att vara null om det inte finns några fel. |
| [Object](../../aspose.pdf.ai/vectorstorefileresponse/object/) { get; set; } | Hämtar eller sätter objekttypen, som alltid är vector_store.file. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Hämtar felorsaksfrasen. |
| [Status](../../aspose.pdf.ai/vectorstorefileresponse/status/) { get; set; } | Hämtar eller sätter statusen för vektorbutikfilen, som kan vara antingen in_progress, completed, cancelled eller failed. Statusen completed indikerar att vektorbutikfilen är redo att användas. |
| [UsageBytes](../../aspose.pdf.ai/vectorstorefileresponse/usagebytes/) { get; set; } | Hämtar eller sätter den totala vektorbutiksanvändningen i byte. Observera att detta kan vara annorlunda än den ursprungliga filstorleken. |
| [VectorStoreId](../../aspose.pdf.ai/vectorstorefileresponse/vectorstoreid/) { get; set; } | Hämtar eller sätter ID:t för vektorbutiken som filen är kopplad till. |

### Se Även

* klass [BaseResponse](../baseresponse/)
* gränssnitt [IStatus](../istatus/)
* namnrymd [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* sammansättning [Aspose.PDF](../../)