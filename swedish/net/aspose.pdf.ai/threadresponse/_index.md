---
title: Class ThreadResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.ThreadResponse klass. Representerar en tråd som innehåller meddelanden
type: docs
weight: 1180
url: /sv/net/aspose.pdf.ai/threadresponse/
---
## ThreadResponse klass

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
| [CreatedAt](../../aspose.pdf.ai/threadresponse/createdat/) { get; set; } | Hämtar eller ställer in Unix-tidsstämpeln (i sekunder) för när tråden skapades. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Hämtar eller ställer in svaret detaljer. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Hämtar eller ställer in HTTP-svarsfel. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Hämtar eller ställer in felinformation. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Hämtar eller ställer in HTTP-svarshuvuden. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Hämtar eller ställer in HTTP-statuskod. |
| [Id](../../aspose.pdf.ai/threadresponse/id/) { get; set; } | Hämtar eller ställer in identifieraren, som kan refereras i API-slutpunkter. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indikerar om svaret var framgångsrikt. |
| [Metadata](../../aspose.pdf.ai/threadresponse/metadata/) { get; set; } | Hämtar eller ställer in en uppsättning av 16 nyckel-värde-par som kan kopplas till ett objekt. Detta kan vara användbart för att lagra ytterligare information om objektet i ett strukturerat format. Nycklar kan vara maximalt 64 tecken långa och värden kan vara maximalt 512 tecken långa. |
| [Object](../../aspose.pdf.ai/threadresponse/object/) { get; set; } | Hämtar eller ställer in objekttypen, som alltid är tråd. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Hämtar felorsaksfrasen. |
| [ToolResources](../../aspose.pdf.ai/threadresponse/toolresources/) { get; set; } | Hämtar eller ställer in en uppsättning resurser som görs tillgängliga för assistentens verktyg i denna tråd. Resurserna är specifika för typen av verktyg. Till exempel kräver verktyget code_interpreter en lista över fil-ID:n, medan verktyget file_search kräver en lista över vektorbutiks-ID:n. |

### Se Även

* klass [BaseResponse](../baseresponse/)
* namnrymd [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* sammansättning [Aspose.PDF](../../)