---
title: "Klass RunStepResponse"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.AI.RunStepResponse-klass. Representerar ett steg i körningens exekvering"
type: docs
weight: 1140
url: /sv/net/aspose.pdf.ai/runstepresponse/
---
## RunStepResponse class

Representerar ett steg i exekveringen av en körning.

```csharp
public class RunStepResponse : BaseResponse
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [RunStepResponse](runstepresponse/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runstepresponse/assistantid/) { get; set; } | Hämtar eller anger ID för assistenten som är associerad med körningssteget. |
| [CancelledAt](../../aspose.pdf.ai/runstepresponse/cancelledat/) { get; set; } | Hämtar eller anger Unix‑tidsstämpeln (i sekunder) för när körningssteget avbröts. |
| [CompletedAt](../../aspose.pdf.ai/runstepresponse/completedat/) { get; set; } | Hämtar eller anger Unix‑tidsstämpeln (i sekunder) för när körningssteget slutfördes. |
| [CreatedAt](../../aspose.pdf.ai/runstepresponse/createdat/) { get; set; } | Hämtar eller anger Unix‑tidsstämpeln (i sekunder) för när körningssteget skapades. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Hämtar eller anger svarsdetaljen. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Hämtar eller anger HTTP‑svarsfelet. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Hämtar eller anger felinformationen. |
| [ExpiredAt](../../aspose.pdf.ai/runstepresponse/expiredat/) { get; set; } | Hämtar eller anger Unix‑tidsstämpeln (i sekunder) för när körningssteget gick ut. Ett steg anses gå ut om den överordnade körningen har gått ut. |
| [FailedAt](../../aspose.pdf.ai/runstepresponse/failedat/) { get; set; } | Hämtar eller anger Unix‑tidsstämpeln (i sekunder) för när körningssteget misslyckades. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Hämtar eller anger HTTP‑svarsrubriker. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Hämtar eller anger HTTP‑statuskoden. |
| [Id](../../aspose.pdf.ai/runstepresponse/id/) { get; set; } | Hämtar eller anger identifieraren för körningssteget, som kan refereras i API‑ändpunkter. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indikerar om svaret var framgångsrikt. |
| [LastError](../../aspose.pdf.ai/runstepresponse/lasterror/) { get; set; } | Hämtar eller anger det senaste felet som är associerat med detta körningssteg. Kommer att vara null om det inte finns några fel. |
| [Metadata](../../aspose.pdf.ai/runstepresponse/metadata/) { get; set; } | Hämtar eller anger en uppsättning av 16 nyckel‑värdepar som kan bifogas ett objekt. Detta kan vara användbart för att lagra ytterligare information om objektet i ett strukturerat format. Nycklar kan vara högst 64 tecken långa och värden kan vara högst 512 tecken långa. |
| [Object](../../aspose.pdf.ai/runstepresponse/object/) { get; set; } | Hämtar eller anger objekttypen, som alltid är thread.run.step. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Hämtar felorsakens fras. |
| [RunId](../../aspose.pdf.ai/runstepresponse/runid/) { get; set; } | Hämtar eller anger ID för körningen som detta körsteg är en del av. |
| [RunStepType](../../aspose.pdf.ai/runstepresponse/runsteptype/) { get; set; } | Hämtar eller anger typen av körsteg, som kan vara antingen message_creation eller tool_calls. |
| [Status](../../aspose.pdf.ai/runstepresponse/status/) { get; set; } | Hämtar eller anger status för körsteget, som kan vara antingen in_progress, cancelled, failed, completed eller expired. |
| [StepDetails](../../aspose.pdf.ai/runstepresponse/stepdetails/) { get; set; } | Hämtar eller anger detaljerna för körsteget. |
| [ThreadId](../../aspose.pdf.ai/runstepresponse/threadid/) { get; set; } | Hämtar eller anger ID för tråden som kördes. |
| [Usage](../../aspose.pdf.ai/runstepresponse/usage/) { get; set; } | Hämtar eller anger användningsstatistik relaterad till körsteget. Detta värde kommer att vara null medan körstegets status är in_progress. |

### Se även

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


