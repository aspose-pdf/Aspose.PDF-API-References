---
title: Class VectorStoreResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.VectorStoreResponse-Klasse. Das Vektorstore-Objekt
type: docs
weight: 1390
url: /de/net/aspose.pdf.ai/vectorstoreresponse/
---
## Klasse VectorStoreResponse

Das Vektorstore-Objekt.

```csharp
public class VectorStoreResponse : BaseResponse, IEntityId, IStatus
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [VectorStoreResponse](vectorstoreresponse/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/vectorstoreresponse/createdat/) { get; set; } | Ruft den Unix-Zeitstempel (in Sekunden) ab, wann das Vektorstore erstellt wurde. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Ruft die Antwortdetails ab oder legt sie fest. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Ruft den HTTP-Antwortfehler ab oder legt ihn fest. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Ruft die Fehlerinformationen ab. |
| [ExpiresAfter](../../aspose.pdf.ai/vectorstoreresponse/expiresafter/) { get; set; } | Ruft die Ablaufrichtlinie für ein Vektorstore ab oder legt sie fest. |
| [ExpiresAt](../../aspose.pdf.ai/vectorstoreresponse/expiresat/) { get; set; } | Ruft den Unix-Zeitstempel (in Sekunden) ab, wann das Vektorstore abläuft. |
| [FileCounts](../../aspose.pdf.ai/vectorstoreresponse/filecounts/) { get; set; } | Ruft die Anzahl der verarbeiteten Dateien ab oder legt sie fest. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Ruft die HTTP-Antwortheader ab oder legt sie fest. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Ruft den HTTP-Statuscode ab oder legt ihn fest. |
| [Id](../../aspose.pdf.ai/vectorstoreresponse/id/) { get; set; } | Ruft den Bezeichner ab oder legt ihn fest, der in API-Endpunkten referenziert werden kann. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Gibt an, ob die Antwort erfolgreich war. |
| [LastActiveAt](../../aspose.pdf.ai/vectorstoreresponse/lastactiveat/) { get; set; } | Ruft den Unix-Zeitstempel (in Sekunden) ab, wann das Vektorstore zuletzt aktiv war. |
| [Metadata](../../aspose.pdf.ai/vectorstoreresponse/metadata/) { get; set; } | Ruft ein Set von 16 Schlüssel-Wert-Paaren ab oder legt es fest, die an ein Objekt angehängt werden können. Dies kann nützlich sein, um zusätzliche Informationen über das Objekt in einem strukturierten Format zu speichern. Schlüssel können maximal 64 Zeichen lang sein und Werte maximal 512 Zeichen lang. |
| [Name](../../aspose.pdf.ai/vectorstoreresponse/name/) { get; set; } | Ruft den Namen des Vektorstores ab oder legt ihn fest. |
| [Object](../../aspose.pdf.ai/vectorstoreresponse/object/) { get; set; } | Ruft den Objekttyp ab oder legt ihn fest, der immer vector_store ist. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Ruft den Fehlergrundsatz ab. |
| [Status](../../aspose.pdf.ai/vectorstoreresponse/status/) { get; set; } | Ruft den Status des Vektorstores ab oder legt ihn fest, der entweder abgelaufen, in_bearbeitung oder abgeschlossen sein kann. Ein Status von abgeschlossen zeigt an, dass das Vektorstore zur Verwendung bereit ist. |
| [UsageBytes](../../aspose.pdf.ai/vectorstoreresponse/usagebytes/) { get; set; } | Ruft die Gesamtanzahl der von den Dateien im Vektorstore verwendeten Bytes ab oder legt sie fest. |

### Siehe auch

* Klasse [BaseResponse](../baseresponse/)
* Schnittstelle [IEntityId](../ientityid/)
* Schnittstelle [IStatus](../istatus/)
* Namensraum [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../)