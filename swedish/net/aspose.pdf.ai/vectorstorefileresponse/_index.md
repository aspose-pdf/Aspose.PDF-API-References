---
title: "Klass VectorStoreFileResponse"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.AI.VectorStoreFileResponse klass. Ett svar för en vektorlagerfil"
type: docs
weight: 1440
url: /sv/net/aspose.pdf.ai/vectorstorefileresponse/
---
## VectorStoreFileResponse class

Ett svar för en vektorlagerfil.

```csharp
public class VectorStoreFileResponse : BaseResponse, IStatus
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [VectorStoreFileResponse](vectorstorefileresponse/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/vectorstorefileresponse/createdat/) { get; set; } | Hämtar eller anger Unix-tidsstämpeln (i sekunder) för när vektorlagerfilen skapades. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Hämtar eller anger svarsdetaljen. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Hämtar eller anger HTTP‑svarsfelet. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Hämtar eller anger felinformationen. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Hämtar eller anger HTTP‑svarsrubriker. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Hämtar eller anger HTTP‑statuskoden. |
| [Id](../../aspose.pdf.ai/vectorstorefileresponse/id/) { get; set; } | Hämtar eller anger identifieraren, som kan refereras i API-endpunkter. /// |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indikerar om svaret var framgångsrikt. |
| [LastError](../../aspose.pdf.ai/vectorstorefileresponse/lasterror/) { get; set; } | Hämtar eller anger det senaste felet som är associerat med denna vektorlagerfil. Kommer att vara null om det inte finns några fel. |
| [Object](../../aspose.pdf.ai/vectorstorefileresponse/object/) { get; set; } | Hämtar eller anger objekttypen, som alltid är vector_store.file. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Hämtar felorsakens fras. |
| [Status](../../aspose.pdf.ai/vectorstorefileresponse/status/) { get; set; } | Hämtar eller anger statusen för vektorlagerfilen, som kan vara in_progress, completed, cancelled eller failed. Statusen completed indikerar att vektorlagerfilen är klar för användning. |
| [UsageBytes](../../aspose.pdf.ai/vectorstorefileresponse/usagebytes/) { get; set; } | Hämtar eller anger den totala vektorlageranvändningen i byte. Observera att detta kan skilja sig från den ursprungliga filstorleken. |
| [VectorStoreId](../../aspose.pdf.ai/vectorstorefileresponse/vectorstoreid/) { get; set; } | Hämtar eller anger ID:t för vektorlageret som filen är bifogad till. |

### Se även

* class [BaseResponse](../baseresponse/)
* interface [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


