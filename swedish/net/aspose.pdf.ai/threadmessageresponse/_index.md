---
title: "Klass ThreadMessageResponse"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.AI.ThreadMessageResponse-klass. Representerar ett meddelande inom en tråd"
type: docs
weight: 1250
url: /sv/net/aspose.pdf.ai/threadmessageresponse/
---
## ThreadMessageResponse class

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
| [AssistantId](../../aspose.pdf.ai/threadmessageresponse/assistantid/) { get; set; } | Hämtar eller anger, om tillämpligt, ID för assistenten som skapade detta meddelande. |
| [Attachments](../../aspose.pdf.ai/threadmessageresponse/attachments/) { get; set; } | Hämtar eller anger en lista med filer som är bifogade till meddelandet. |
| [CompletedAt](../../aspose.pdf.ai/threadmessageresponse/completedat/) { get; set; } | Hämtar eller anger Unix‑tidsstämpeln (i sekunder) för när meddelandet slutfördes. |
| [Content](../../aspose.pdf.ai/threadmessageresponse/content/) { get; set; } | Hämtar eller anger innehållet i meddelandet i en array av text och/eller bilder. |
| [CreatedAt](../../aspose.pdf.ai/threadmessageresponse/createdat/) { get; set; } | Hämtar eller anger Unix‑tidsstämpeln (i sekunder) för när meddelandet skapades. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Hämtar eller anger svarsdetaljen. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Hämtar eller anger HTTP‑svarsfelet. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Hämtar eller anger felinformationen. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Hämtar eller anger HTTP‑svarsrubriker. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Hämtar eller anger HTTP‑statuskoden. |
| [Id](../../aspose.pdf.ai/threadmessageresponse/id/) { get; set; } | Hämtar eller anger identifieraren, som kan refereras i API‑slutpunkter. |
| [IncompleteAt](../../aspose.pdf.ai/threadmessageresponse/incompleteat/) { get; set; } | Hämtar eller anger Unix‑tidsstämpeln (i sekunder) för när meddelandet markerades som ofullständigt. |
| [IncompleteDetails](../../aspose.pdf.ai/threadmessageresponse/incompletedetails/) { get; set; } | Hämtar eller anger ett ofullständigt meddelande, detaljer om varför meddelandet är ofullständigt. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indikerar om svaret var framgångsrikt. |
| [Metadata](../../aspose.pdf.ai/threadmessageresponse/metadata/) { get; set; } | Hämtar eller anger en uppsättning av 16 nyckel‑värdepar som kan bifogas ett objekt. Detta kan vara användbart för att lagra ytterligare information om objektet i ett strukturerat format. Nycklar kan vara högst 64 tecken långa och värden kan vara högst 512 tecken långa. |
| [Object](../../aspose.pdf.ai/threadmessageresponse/object/) { get; set; } | Hämtar eller anger objekttypen, som alltid är "thread.message". |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Hämtar felorsakens fras. |
| [Role](../../aspose.pdf.ai/threadmessageresponse/role/) { get; set; } | Hämtar eller anger enheten som skapade meddelandet. En av "user" eller "assistant". |
| [RunId](../../aspose.pdf.ai/threadmessageresponse/runid/) { get; set; } | Hämtar eller anger ID för körningen som är associerad med skapandet av detta meddelande. Värdet är null när meddelanden skapas manuellt. |
| [Status](../../aspose.pdf.ai/threadmessageresponse/status/) { get; set; } | Hämtar eller anger statusen för meddelandet. En av queued, in_progress, requires_action eller completed. |
| [ThreadId](../../aspose.pdf.ai/threadmessageresponse/threadid/) { get; set; } | Hämtar eller anger ID för tråden som detta meddelande tillhör. |

### Se även

* class [BaseResponse](../baseresponse/)
* interface [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


