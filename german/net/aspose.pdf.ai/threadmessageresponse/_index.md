---
title: Class ThreadMessageResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.ThreadMessageResponse-Klasse. Stellt eine Nachricht innerhalb eines Threads dar
type: docs
weight: 1160
url: /de/net/aspose.pdf.ai/threadmessageresponse/
---
## Klasse ThreadMessageResponse

Stellt eine Nachricht innerhalb eines Threads dar.

```csharp
public class ThreadMessageResponse : BaseResponse, IStatus
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ThreadMessageResponse](threadmessageresponse/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/threadmessageresponse/assistantid/) { get; set; } | Ruft die ID des Assistenten ab oder legt sie fest, der diese Nachricht verfasst hat, falls zutreffend. |
| [Attachments](../../aspose.pdf.ai/threadmessageresponse/attachments/) { get; set; } | Ruft eine Liste von Dateien ab oder legt sie fest, die an die Nachricht angehängt sind. |
| [CompletedAt](../../aspose.pdf.ai/threadmessageresponse/completedat/) { get; set; } | Ruft den Unix-Zeitstempel (in Sekunden) ab oder legt ihn fest, wann die Nachricht abgeschlossen wurde. |
| [Content](../../aspose.pdf.ai/threadmessageresponse/content/) { get; set; } | Ruft den Inhalt der Nachricht in einem Array von Text und/oder Bildern ab oder legt ihn fest. |
| [CreatedAt](../../aspose.pdf.ai/threadmessageresponse/createdat/) { get; set; } | Ruft den Unix-Zeitstempel (in Sekunden) ab oder legt ihn fest, wann die Nachricht erstellt wurde. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Ruft die Antwortdetails ab oder legt sie fest. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Ruft den HTTP-Antwortfehler ab oder legt ihn fest. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Ruft die Fehlerinformationen ab oder legt sie fest. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Ruft die HTTP-Antwortheader ab oder legt sie fest. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Ruft den HTTP-Statuscode ab oder legt ihn fest. |
| [Id](../../aspose.pdf.ai/threadmessageresponse/id/) { get; set; } | Ruft den Bezeichner ab oder legt ihn fest, der in API-Endpunkten referenziert werden kann. |
| [IncompleteAt](../../aspose.pdf.ai/threadmessageresponse/incompleteat/) { get; set; } | Ruft den Unix-Zeitstempel (in Sekunden) ab oder legt ihn fest, wann die Nachricht als unvollständig markiert wurde. |
| [IncompleteDetails](../../aspose.pdf.ai/threadmessageresponse/incompletedetails/) { get; set; } | Ruft eine unvollständige Nachricht ab oder legt sie fest, die Details darüber enthält, warum die Nachricht unvollständig ist. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Gibt an, ob die Antwort erfolgreich war. |
| [Metadata](../../aspose.pdf.ai/threadmessageresponse/metadata/) { get; set; } | Ruft eine Menge von 16 Schlüssel-Wert-Paaren ab oder legt sie fest, die an ein Objekt angehängt werden können. Dies kann nützlich sein, um zusätzliche Informationen über das Objekt in einem strukturierten Format zu speichern. Schlüssel können maximal 64 Zeichen lang sein und Werte maximal 512 Zeichen lang. |
| [Object](../../aspose.pdf.ai/threadmessageresponse/object/) { get; set; } | Ruft den Objekttyp ab oder legt ihn fest, der immer "thread.message" ist. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Ruft den Fehlergrundsatz ab. |
| [Role](../../aspose.pdf.ai/threadmessageresponse/role/) { get; set; } | Ruft die Entität ab oder legt sie fest, die die Nachricht erzeugt hat. Eine von "user" oder "assistant". |
| [RunId](../../aspose.pdf.ai/threadmessageresponse/runid/) { get; set; } | Ruft die ID des Laufs ab oder legt sie fest, die mit der Erstellung dieser Nachricht verbunden ist. Der Wert ist null, wenn Nachrichten manuell erstellt werden. |
| [Status](../../aspose.pdf.ai/threadmessageresponse/status/) { get; set; } | Ruft den Status der Nachricht ab oder legt ihn fest. Eine von queued, in_progress, requires_action oder completed. |
| [ThreadId](../../aspose.pdf.ai/threadmessageresponse/threadid/) { get; set; } | Ruft die ID des Threads ab oder legt sie fest, zu dem diese Nachricht gehört. |

### Siehe auch

* Klasse [BaseResponse](../baseresponse/)
* Schnittstelle [IStatus](../istatus/)
* Namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../)