---
title: Class RunStepResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.RunStepResponse klass. Representerar ett steg i utförandet av en körning
type: docs
weight: 1060
url: /sv/net/aspose.pdf.ai/runstepresponse/
---
## RunStepResponse klass

Representerar ett steg i utförandet av en körning.

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
| [AssistantId](../../aspose.pdf.ai/runstepresponse/assistantid/) { get; set; } | Hämtar eller ställer in ID:t för assistenten kopplad till körsteget. |
| [CancelledAt](../../aspose.pdf.ai/runstepresponse/cancelledat/) { get; set; } | Hämtar eller ställer in Unix-tidsstämpeln (i sekunder) för när körsteget avbröts. |
| [CompletedAt](../../aspose.pdf.ai/runstepresponse/completedat/) { get; set; } | Hämtar eller ställer in Unix-tidsstämpeln (i sekunder) för när körsteget slutfördes. |
| [CreatedAt](../../aspose.pdf.ai/runstepresponse/createdat/) { get; set; } | Hämtar eller ställer in Unix-tidsstämpeln (i sekunder) för när körsteget skapades. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Hämtar eller ställer in svaret detaljer. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Hämtar eller ställer in HTTP-svarsfel. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Hämtar eller ställer in felinformationen. |
| [ExpiredAt](../../aspose.pdf.ai/runstepresponse/expiredat/) { get; set; } | Hämtar eller ställer in Unix-tidsstämpeln (i sekunder) för när körsteget gick ut. Ett steg anses vara utgånget om den överordnade körningen har gått ut. |
| [FailedAt](../../aspose.pdf.ai/runstepresponse/failedat/) { get; set; } | Hämtar eller ställer in Unix-tidsstämpeln (i sekunder) för när körsteget misslyckades. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Hämtar eller ställer in HTTP-svarshuvuden. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Hämtar eller ställer in HTTP-statuskoden. |
| [Id](../../aspose.pdf.ai/runstepresponse/id/) { get; set; } | Hämtar eller ställer in identifieraren för körsteget, som kan refereras i API-slutpunkter. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indikerar om svaret var framgångsrikt. |
| [LastError](../../aspose.pdf.ai/runstepresponse/lasterror/) { get; set; } | Hämtar eller ställer in det senaste felet kopplat till detta körsteg. Kommer att vara null om det inte finns några fel. |
| [Metadata](../../aspose.pdf.ai/runstepresponse/metadata/) { get; set; } | Hämtar eller ställer in en uppsättning av 16 nyckel-värde-par som kan kopplas till ett objekt. Detta kan vara användbart för att lagra ytterligare information om objektet i ett strukturerat format. Nycklar kan vara maximalt 64 tecken långa och värden kan vara maximalt 512 tecken långa. |
| [Object](../../aspose.pdf.ai/runstepresponse/object/) { get; set; } | Hämtar eller ställer in objekttypen, som alltid är thread.run.step. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Hämtar felorsaksfrasen. |
| [RunId](../../aspose.pdf.ai/runstepresponse/runid/) { get; set; } | Hämtar eller ställer in ID:t för den körning som detta körsteg är en del av. |
| [RunStepType](../../aspose.pdf.ai/runstepresponse/runsteptype/) { get; set; } | Hämtar eller ställer in typen av körsteg, som kan vara antingen message_creation eller tool_calls. |
| [Status](../../aspose.pdf.ai/runstepresponse/status/) { get; set; } | Hämtar eller ställer in statusen för körsteget, som kan vara antingen in_progress, cancelled, failed, completed eller expired. |
| [StepDetails](../../aspose.pdf.ai/runstepresponse/stepdetails/) { get; set; } | Hämtar eller ställer in detaljerna för körsteget. |
| [ThreadId](../../aspose.pdf.ai/runstepresponse/threadid/) { get; set; } | Hämtar eller ställer in ID:t för den tråd som kördes. |
| [Usage](../../aspose.pdf.ai/runstepresponse/usage/) { get; set; } | Hämtar eller ställer in användningsstatistik relaterad till körsteget. Detta värde kommer att vara null medan körstegets status är in_progress. |

### Se Även

* klass [BaseResponse](../baseresponse/)
* namnrymd [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* sammansättning [Aspose.PDF](../../)