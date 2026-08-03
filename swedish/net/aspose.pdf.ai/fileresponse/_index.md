---
title: "Klass FileResponse"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.AI.FileResponse-klass. FileResponse-objektet representerar ett dokument som har laddats upp till OpenAI."
type: docs
weight: 420
url: /sv/net/aspose.pdf.ai/fileresponse/
---
## FileResponse class

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
| [Bytes](../../aspose.pdf.ai/fileresponse/bytes/) { get; set; } | Hämtar eller anger storleken på filen, i byte. |
| [CreatedAt](../../aspose.pdf.ai/fileresponse/createdat/) { get; set; } | Hämtar eller anger Unix-tidsstämpeln (i sekunder) för när filen skapades. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Hämtar eller anger svarsdetaljen. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Hämtar eller anger HTTP‑svarsfelet. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Hämtar eller anger felinformationen. |
| [Filename](../../aspose.pdf.ai/fileresponse/filename/) { get; set; } | Hämtar eller anger filens namn. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Hämtar eller anger HTTP‑svarsrubriker. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Hämtar eller anger HTTP‑statuskoden. |
| [Id](../../aspose.pdf.ai/fileresponse/id/) { get; set; } | Hämtar eller anger filidentifieraren, som kan refereras till i API‑ändpunkterna. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indikerar om svaret var framgångsrikt. |
| [Object](../../aspose.pdf.ai/fileresponse/object/) { get; set; } | Hämtar eller anger objekttypen, som alltid är file. |
| [Purpose](../../aspose.pdf.ai/fileresponse/purpose/) { get; set; } | Hämtar eller anger det avsedda syftet med filen. Stödda värden är assistants, assistants_output, batch, batch_output, fine-tune, fine-tune-results och vision. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Hämtar felorsakens fras. |

### Se även

* class [BaseResponse](../baseresponse/)
* interface [IEntityId](../ientityid/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


