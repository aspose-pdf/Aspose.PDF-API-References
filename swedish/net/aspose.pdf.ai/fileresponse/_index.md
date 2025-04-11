---
title: Class FileResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.FileResponse klass. FileResponse-objektet representerar ett dokument som har laddats upp till OpenAI
type: docs
weight: 400
url: /sv/net/aspose.pdf.ai/fileresponse/
---
## FileResponse klass

FileResponse-objektet representerar ett dokument som har laddats upp till OpenAI.

```csharp
public class FileResponse : BaseResponse, IEntityId
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [FileResponse](fileresponse/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Bytes](../../aspose.pdf.ai/fileresponse/bytes/) { get; set; } | Hämtar eller ställer in storleken på filen, i byte. |
| [CreatedAt](../../aspose.pdf.ai/fileresponse/createdat/) { get; set; } | Hämtar eller ställer in Unix-tidsstämpeln (i sekunder) för när filen skapades. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Hämtar eller ställer in svaret detaljer. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Hämtar eller ställer in HTTP-svarsfel. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Hämtar eller ställer in felinformationen. |
| [Filename](../../aspose.pdf.ai/fileresponse/filename/) { get; set; } | Hämtar eller ställer in namnet på filen. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Hämtar eller ställer in HTTP-svarshuvuden. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Hämtar eller ställer in HTTP-statuskoden. |
| [Id](../../aspose.pdf.ai/fileresponse/id/) { get; set; } | Hämtar eller ställer in filidentifieraren, som kan refereras i API-slutpunkterna. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indikerar om svaret var framgångsrikt. |
| [Object](../../aspose.pdf.ai/fileresponse/object/) { get; set; } | Hämtar eller ställer in objekttypen, som alltid är fil. |
| [Purpose](../../aspose.pdf.ai/fileresponse/purpose/) { get; set; } | Hämtar eller ställer in den avsedda användningen av filen. Stödda värden är assistants, assistants_output, batch, batch_output, fine-tune, fine-tune-results och vision. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Hämtar felorsaksfrasen. |

### Se Även

* klass [BaseResponse](../baseresponse/)
* gränssnitt [IEntityId](../ientityid/)
* namnrymd [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* sammansättning [Aspose.PDF](../../)