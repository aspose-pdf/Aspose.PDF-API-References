---
title: "Klass ThreadResponse"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.AI.ThreadResponse-klass. Representerar en tråd som innehåller meddelanden."
type: docs
weight: 1270
url: /sv/net/aspose.pdf.ai/threadresponse/
---
## ThreadResponse class

Representerar en tråd som innehåller meddelanden.

```csharp
public class ThreadResponse : BaseResponse
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ThreadResponse](threadresponse/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/threadresponse/createdat/) { get; set; } | Hämtar eller anger Unix‑tidsstämpeln (i sekunder) för när tråden skapades. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Hämtar eller anger svarsdetaljen. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Hämtar eller anger HTTP‑svarsfelet. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Hämtar eller anger felinformationen. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Hämtar eller anger HTTP‑svarsrubriker. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Hämtar eller anger HTTP‑statuskoden. |
| [Id](../../aspose.pdf.ai/threadresponse/id/) { get; set; } | Hämtar eller anger identifieraren, som kan refereras i API‑slutpunkter. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indikerar om svaret var framgångsrikt. |
| [Metadata](../../aspose.pdf.ai/threadresponse/metadata/) { get; set; } | Hämtar eller anger en uppsättning av 16 nyckel‑värdepar som kan bifogas ett objekt. Detta kan vara användbart för att lagra ytterligare information om objektet i ett strukturerat format. Nycklar kan vara högst 64 tecken långa och värden kan vara högst 512 tecken långa. |
| [Object](../../aspose.pdf.ai/threadresponse/object/) { get; set; } | Hämtar eller anger objekttypen, som alltid är thread. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Hämtar felorsakens fras. |
| [ToolResources](../../aspose.pdf.ai/threadresponse/toolresources/) { get; set; } | Hämtar eller anger en uppsättning resurser som görs tillgängliga för assistentens verktyg i denna tråd. Resurserna är specifika för verktygstypen. Till exempel kräver verktyget code_interpreter en lista med fil‑ID:n, medan verktyget file_search kräver en lista med vektorlager‑ID:n. |

### Se även

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


