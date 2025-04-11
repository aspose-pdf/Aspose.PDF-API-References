---
title: Class RunStepResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.RunStepResponse-Klasse. Stellt einen Schritt in der Ausführung eines Laufs dar
type: docs
weight: 1060
url: /de/net/aspose.pdf.ai/runstepresponse/
---
## RunStepResponse-Klasse

Stellt einen Schritt in der Ausführung eines Laufs dar.

```csharp
public class RunStepResponse : BaseResponse
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [RunStepResponse](runstepresponse/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runstepresponse/assistantid/) { get; set; } | Ruft die ID des mit dem Lauf Schritt verbundenen Assistenten ab oder legt sie fest. |
| [CancelledAt](../../aspose.pdf.ai/runstepresponse/cancelledat/) { get; set; } | Ruft den Unix-Zeitstempel (in Sekunden) ab oder legt ihn fest, wann der Lauf Schritt abgebrochen wurde. |
| [CompletedAt](../../aspose.pdf.ai/runstepresponse/completedat/) { get; set; } | Ruft den Unix-Zeitstempel (in Sekunden) ab oder legt ihn fest, wann der Lauf Schritt abgeschlossen wurde. |
| [CreatedAt](../../aspose.pdf.ai/runstepresponse/createdat/) { get; set; } | Ruft den Unix-Zeitstempel (in Sekunden) ab oder legt ihn fest, wann der Lauf Schritt erstellt wurde. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Ruft die Antwortdetails ab oder legt sie fest. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Ruft den HTTP-Antwortfehler ab oder legt ihn fest. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Ruft die Fehlerinformationen ab oder legt sie fest. |
| [ExpiredAt](../../aspose.pdf.ai/runstepresponse/expiredat/) { get; set; } | Ruft den Unix-Zeitstempel (in Sekunden) ab oder legt ihn fest, wann der Lauf Schritt abgelaufen ist. Ein Schritt wird als abgelaufen betrachtet, wenn der übergeordnete Lauf abgelaufen ist. |
| [FailedAt](../../aspose.pdf.ai/runstepresponse/failedat/) { get; set; } | Ruft den Unix-Zeitstempel (in Sekunden) ab oder legt ihn fest, wann der Lauf Schritt fehlgeschlagen ist. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Ruft die HTTP-Antwortheader ab oder legt sie fest. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Ruft den HTTP-Statuscode ab oder legt ihn fest. |
| [Id](../../aspose.pdf.ai/runstepresponse/id/) { get; set; } | Ruft den Bezeichner des Lauf Schrittes ab oder legt ihn fest, der in API-Endpunkten referenziert werden kann. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Gibt an, ob die Antwort erfolgreich war. |
| [LastError](../../aspose.pdf.ai/runstepresponse/lasterror/) { get; set; } | Ruft den letzten Fehler ab oder legt ihn fest, der mit diesem Lauf Schritt verbunden ist. Wird null sein, wenn keine Fehler vorliegen. |
| [Metadata](../../aspose.pdf.ai/runstepresponse/metadata/) { get; set; } | Ruft eine Menge von 16 Schlüssel-Wert-Paaren ab oder legt sie fest, die an ein Objekt angehängt werden können. Dies kann nützlich sein, um zusätzliche Informationen über das Objekt in einem strukturierten Format zu speichern. Schlüssel können maximal 64 Zeichen lang sein und Werte maximal 512 Zeichen lang. |
| [Object](../../aspose.pdf.ai/runstepresponse/object/) { get; set; } | Ruft den Objekttyp ab oder legt ihn fest, der immer thread.run.step ist. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Ruft den Fehlergrundsatz ab. |
| [RunId](../../aspose.pdf.ai/runstepresponse/runid/) { get; set; } | Ruft die ID des Laufs ab oder legt sie fest, zu dem dieser Lauf Schritt gehört. |
| [RunStepType](../../aspose.pdf.ai/runstepresponse/runsteptype/) { get; set; } | Ruft den Typ des Lauf Schrittes ab oder legt ihn fest, der entweder message_creation oder tool_calls sein kann. |
| [Status](../../aspose.pdf.ai/runstepresponse/status/) { get; set; } | Ruft den Status des Lauf Schrittes ab oder legt ihn fest, der entweder in_progress, cancelled, failed, completed oder expired sein kann. |
| [StepDetails](../../aspose.pdf.ai/runstepresponse/stepdetails/) { get; set; } | Ruft die Details des Lauf Schrittes ab oder legt sie fest. |
| [ThreadId](../../aspose.pdf.ai/runstepresponse/threadid/) { get; set; } | Ruft die ID des Threads ab oder legt sie fest, der ausgeführt wurde. |
| [Usage](../../aspose.pdf.ai/runstepresponse/usage/) { get; set; } | Ruft die Nutzungsstatistiken ab oder legt sie fest, die mit dem Lauf Schritt verbunden sind. Dieser Wert wird null sein, solange der Status des Lauf Schrittes in_progress ist. |

### Siehe auch

* Klasse [BaseResponse](../baseresponse/)
* Namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../)