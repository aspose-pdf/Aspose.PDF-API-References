---
title: Class ThreadMessageResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.ThreadMessageResponse klass. Representerar ett meddelande inom en tråd
type: docs
weight: 1160
url: /sv/net/aspose.pdf.ai/threadmessageresponse/
---
## ThreadMessageResponse klass

Representerar ett meddelande inom en tråd.

```csharp
public class ThreadMessageResponse : BaseResponse, IStatus
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ThreadMessageResponse](threadmessageresponse/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/threadmessageresponse/assistantid/) { get; set; } | Hämtar eller sätter, om tillämpligt, ID:t för assistenten som skapade detta meddelande. |
| [Attachments](../../aspose.pdf.ai/threadmessageresponse/attachments/) { get; set; } | Hämtar eller sätter en lista över filer som är bifogade till meddelandet. |
| [CompletedAt](../../aspose.pdf.ai/threadmessageresponse/completedat/) { get; set; } | Hämtar eller sätter Unix-tidsstämpeln (i sekunder) för när meddelandet slutfördes. |
| [Content](../../aspose.pdf.ai/threadmessageresponse/content/) { get; set; } | Hämtar eller sätter innehållet i meddelandet i en array av text och/eller bilder. |
| [CreatedAt](../../aspose.pdf.ai/threadmessageresponse/createdat/) { get; set; } | Hämtar eller sätter Unix-tidsstämpeln (i sekunder) för när meddelandet skapades. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Hämtar eller sätter svaret detaljer. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Hämtar eller sätter HTTP-svarsfel. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Hämtar eller sätter felinformation. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Hämtar eller sätter HTTP-svarshuvuden. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Hämtar eller sätter HTTP-statuskod. |
| [Id](../../aspose.pdf.ai/threadmessageresponse/id/) { get; set; } | Hämtar eller sätter identifieraren, som kan refereras i API-slutpunkter. |
| [IncompleteAt](../../aspose.pdf.ai/threadmessageresponse/incompleteat/) { get; set; } | Hämtar eller sätter Unix-tidsstämpeln (i sekunder) för när meddelandet markerades som ofullständigt. |
| [IncompleteDetails](../../aspose.pdf.ai/threadmessageresponse/incompletedetails/) { get; set; } | Hämtar eller sätter ett ofullständigt meddelande, detaljer om varför meddelandet är ofullständigt. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indikerar om svaret var framgångsrikt. |
| [Metadata](../../aspose.pdf.ai/threadmessageresponse/metadata/) { get; set; } | Hämtar eller sätter en uppsättning av 16 nyckel-värde-par som kan kopplas till ett objekt. Detta kan vara användbart för att lagra ytterligare information om objektet i ett strukturerat format. Nycklar kan vara maximalt 64 tecken långa och värden kan vara maximalt 512 tecken långa. |
| [Object](../../aspose.pdf.ai/threadmessageresponse/object/) { get; set; } | Hämtar eller sätter objekttypen, som alltid är "thread.message". |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Hämtar felorsaksfrasen. |
| [Role](../../aspose.pdf.ai/threadmessageresponse/role/) { get; set; } | Hämtar eller sätter enheten som producerade meddelandet. En av "user" eller "assistant". |
| [RunId](../../aspose.pdf.ai/threadmessageresponse/runid/) { get; set; } | Hämtar eller sätter ID:t för körningen kopplad till skapandet av detta meddelande. Värdet är null när meddelanden skapas manuellt. |
| [Status](../../aspose.pdf.ai/threadmessageresponse/status/) { get; set; } | Hämtar eller sätter statusen för meddelandet. En av queued , in_progress , requires_action , eller completed . |
| [ThreadId](../../aspose.pdf.ai/threadmessageresponse/threadid/) { get; set; } | Hämtar eller sätter ID:t för den tråd som detta meddelande tillhör. |

### Se Även

* klass [BaseResponse](../baseresponse/)
* gränssnitt [IStatus](../istatus/)
* namnrymd [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* samling [Aspose.PDF](../../)