---
title: Class FileResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.FileResponse-Klasse. Das FileResponse-Objekt stellt ein Dokument dar, das bei OpenAI hochgeladen wurde.
type: docs
weight: 400
url: /de/net/aspose.pdf.ai/fileresponse/
---
## Klasse FileResponse

Das FileResponse-Objekt stellt ein Dokument dar, das bei OpenAI hochgeladen wurde.

```csharp
public class FileResponse : BaseResponse, IEntityId
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [FileResponse](fileresponse/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Bytes](../../aspose.pdf.ai/fileresponse/bytes/) { get; set; } | Ruft die Größe der Datei in Bytes ab oder legt sie fest. |
| [CreatedAt](../../aspose.pdf.ai/fileresponse/createdat/) { get; set; } | Ruft den Unix-Zeitstempel (in Sekunden) ab oder legt ihn fest, wann die Datei erstellt wurde. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Ruft die Antwortdetails ab oder legt sie fest. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Ruft den HTTP-Antwortfehler ab oder legt ihn fest. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Ruft die Fehlerinformationen ab oder legt sie fest. |
| [Filename](../../aspose.pdf.ai/fileresponse/filename/) { get; set; } | Ruft den Namen der Datei ab oder legt ihn fest. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Ruft die HTTP-Antwortheader ab oder legt sie fest. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Ruft den HTTP-Statuscode ab oder legt ihn fest. |
| [Id](../../aspose.pdf.ai/fileresponse/id/) { get; set; } | Ruft die Datei-ID ab oder legt sie fest, die in den API-Endpunkten referenziert werden kann. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Gibt an, ob die Antwort erfolgreich war. |
| [Object](../../aspose.pdf.ai/fileresponse/object/) { get; set; } | Ruft den Objekttyp ab oder legt ihn fest, der immer Datei ist. |
| [Purpose](../../aspose.pdf.ai/fileresponse/purpose/) { get; set; } | Ruft den beabsichtigten Zweck der Datei ab oder legt ihn fest. Unterstützte Werte sind assistants, assistants_output, batch, batch_output, fine-tune, fine-tune-results und vision. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Ruft den Fehlergrundsatz ab. |

### Siehe auch

* Klasse [BaseResponse](../baseresponse/)
* Schnittstelle [IEntityId](../ientityid/)
* Namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../)