---
title: Class VectorStoreFileResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.VectorStoreFileResponse-Klasse. Eine Vektorspeicher-Dateiantwort
type: docs
weight: 1350
url: /de/net/aspose.pdf.ai/vectorstorefileresponse/
---
## Klasse VectorStoreFileResponse

Eine Vektorspeicher-Dateiantwort.

```csharp
public class VectorStoreFileResponse : BaseResponse, IStatus
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [VectorStoreFileResponse](vectorstorefileresponse/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/vectorstorefileresponse/createdat/) { get; set; } | Ruft den Unix-Zeitstempel (in Sekunden) ab oder setzt ihn, wann die Vektorspeicher-Datei erstellt wurde. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Ruft die Antwortdetails ab oder setzt sie. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Ruft den HTTP-Antwortfehler ab oder setzt ihn. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Ruft die Fehlerinformationen ab oder setzt sie. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Ruft die HTTP-Antwortheader ab oder setzt sie. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Ruft den HTTP-Statuscode ab oder setzt ihn. |
| [Id](../../aspose.pdf.ai/vectorstorefileresponse/id/) { get; set; } | Ruft den Bezeichner ab oder setzt ihn, der in API-Endpunkten referenziert werden kann. /// |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Gibt an, ob die Antwort erfolgreich war. |
| [LastError](../../aspose.pdf.ai/vectorstorefileresponse/lasterror/) { get; set; } | Ruft den letzten Fehler ab oder setzt ihn, der mit dieser Vektorspeicher-Datei verbunden ist. Wird null sein, wenn keine Fehler vorliegen. |
| [Object](../../aspose.pdf.ai/vectorstorefileresponse/object/) { get; set; } | Ruft den Objekttyp ab oder setzt ihn, der immer vector_store.file ist. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Ruft den Fehlergrundsatz ab. |
| [Status](../../aspose.pdf.ai/vectorstorefileresponse/status/) { get; set; } | Ruft den Status der Vektorspeicher-Datei ab oder setzt ihn, der entweder in_progress, completed, cancelled oder failed sein kann. Der Status completed zeigt an, dass die Vektorspeicher-Datei zur Verwendung bereit ist. |
| [UsageBytes](../../aspose.pdf.ai/vectorstorefileresponse/usagebytes/) { get; set; } | Ruft die gesamte Vektorspeichernutzung in Bytes ab oder setzt sie. Beachten Sie, dass dies von der ursprünglichen Dateigröße abweichen kann. |
| [VectorStoreId](../../aspose.pdf.ai/vectorstorefileresponse/vectorstoreid/) { get; set; } | Ruft die ID des Vektorspeichers ab oder setzt sie, an den die Datei angehängt ist. |

### Siehe auch

* Klasse [BaseResponse](../baseresponse/)
* Schnittstelle [IStatus](../istatus/)
* Namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../)