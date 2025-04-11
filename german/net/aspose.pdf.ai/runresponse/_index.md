---
title: Class RunResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.RunResponse-Klasse. Stellt einen Ausführungsdurchlauf auf einem Thread dar
type: docs
weight: 1020
url: /de/net/aspose.pdf.ai/runresponse/
---
## RunResponse-Klasse

Stellt einen Ausführungsdurchlauf auf einem Thread dar.

```csharp
public class RunResponse : BaseResponse, IStatus
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [RunResponse](runresponse/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runresponse/assistantid/) { get; set; } | Ruft die ID des Assistenten ab oder legt sie fest, die für die Ausführung dieses Durchlaufs verwendet wurde. |
| [CancelledAt](../../aspose.pdf.ai/runresponse/cancelledat/) { get; set; } | Ruft den Unix-Zeitstempel (in Sekunden) ab oder legt ihn fest, wann der Durchlauf abgebrochen wurde. |
| [CompletedAt](../../aspose.pdf.ai/runresponse/completedat/) { get; set; } | Ruft den Unix-Zeitstempel (in Sekunden) ab oder legt ihn fest, wann der Durchlauf abgeschlossen wurde. |
| [CreatedAt](../../aspose.pdf.ai/runresponse/createdat/) { get; set; } | Ruft den Unix-Zeitstempel (in Sekunden) ab oder legt ihn fest, wann der Durchlauf erstellt wurde. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Ruft die Antwortdetails ab oder legt sie fest. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Ruft den HTTP-Antwortfehler ab oder legt ihn fest. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Ruft die Fehlerinformationen ab oder legt sie fest. |
| [ExpiresAt](../../aspose.pdf.ai/runresponse/expiresat/) { get; set; } | Ruft den Unix-Zeitstempel (in Sekunden) ab oder legt ihn fest, wann der Durchlauf abläuft. |
| [FailedAt](../../aspose.pdf.ai/runresponse/failedat/) { get; set; } | Ruft den Unix-Zeitstempel (in Sekunden) ab oder legt ihn fest, wann der Durchlauf fehlgeschlagen ist. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Ruft die HTTP-Antwortheader ab oder legt sie fest. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Ruft den HTTP-Statuscode ab oder legt ihn fest. |
| [Id](../../aspose.pdf.ai/runresponse/id/) { get; set; } | Ruft den Bezeichner ab oder legt ihn fest, der in API-Endpunkten referenziert werden kann. |
| [IncompleteDetails](../../aspose.pdf.ai/runresponse/incompletedetails/) { get; set; } | Ruft die Details ab oder legt sie fest, warum der Durchlauf unvollständig ist. Wird null sein, wenn der Durchlauf nicht unvollständig ist. |
| [Instructions](../../aspose.pdf.ai/runresponse/instructions/) { get; set; } | Ruft die Anweisungen ab oder legt sie fest, die der Assistent für diesen Durchlauf verwendet hat. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Gibt an, ob die Antwort erfolgreich war. |
| [LastError](../../aspose.pdf.ai/runresponse/lasterror/) { get; set; } | Ruft den letzten Fehler ab oder legt ihn fest, der mit diesem Durchlauf verbunden ist. Wird null sein, wenn keine Fehler vorliegen. |
| [MaxCompletionTokens](../../aspose.pdf.ai/runresponse/maxcompletiontokens/) { get; set; } | Ruft die maximale Anzahl von Abschluss-Token ab oder legt sie fest, die während des Durchlaufs verwendet wurden. |
| [MaxPromptTokens](../../aspose.pdf.ai/runresponse/maxprompttokens/) { get; set; } | Ruft die maximale Anzahl von Eingabe-Token ab oder legt sie fest, die während des Durchlaufs verwendet wurden. |
| [Metadata](../../aspose.pdf.ai/runresponse/metadata/) { get; set; } | Ruft eine Menge von 16 Schlüssel-Wert-Paaren ab oder legt sie fest, die an ein Objekt angehängt werden können. Dies kann nützlich sein, um zusätzliche Informationen über das Objekt in einem strukturierten Format zu speichern. Schlüssel können maximal 64 Zeichen lang sein und Werte maximal 512 Zeichen lang. |
| [Model](../../aspose.pdf.ai/runresponse/model/) { get; set; } | Ruft das Modell ab oder legt es fest, das der Assistent für diesen Durchlauf verwendet hat. |
| [Object](../../aspose.pdf.ai/runresponse/object/) { get; set; } | Ruft den Objekttyp ab oder legt ihn fest, der immer thread.run ist. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Ruft den Fehlergrundsatz ab. |
| [RequiredAction](../../aspose.pdf.ai/runresponse/requiredaction/) { get; set; } | Ruft die Details zur erforderlichen Aktion ab oder legt sie fest, um den Durchlauf fortzusetzen. Wird null sein, wenn keine Aktion erforderlich ist. |
| [ResponseFormat](../../aspose.pdf.ai/runresponse/responseformat/) { get; set; } | Ruft das Format ab oder legt es fest, das das Modell ausgeben muss. Kompatibel mit GPT-4o, GPT-4 Turbo und allen GPT-3.5 Turbo-Modellen seit gpt-3.5-turbo-1106. Das Setzen auf { "type": "json_object" } aktiviert den JSON-Modus, der garantiert, dass die vom Modell generierte Nachricht gültiges JSON ist. Wichtig: Wenn Sie den JSON-Modus verwenden, müssen Sie das Modell auch anweisen, selbst JSON über eine System- oder Benutzernachricht zu erzeugen. Andernfalls kann das Modell einen unendlichen Strom von Leerzeichen erzeugen, bis die Generierung das Token-Limit erreicht, was zu einer langwierigen und scheinbar "festgefahrenen" Anfrage führt. Beachten Sie auch, dass der Nachrichteninhalt teilweise abgeschnitten werden kann, wenn finish_reason="length" angezeigt wird, was darauf hinweist, dass die Generierung das max_tokens überschreitet oder die Konversation die maximale Kontextlänge überschreitet. |
| [StartedAt](../../aspose.pdf.ai/runresponse/startedat/) { get; set; } | Ruft den Unix-Zeitstempel (in Sekunden) ab oder legt ihn fest, wann der Durchlauf gestartet wurde. |
| [Status](../../aspose.pdf.ai/runresponse/status/) { get; set; } | Ruft den Status des Durchlaufs ab oder legt ihn fest, der entweder queued, in_progress, requires_action, cancelling, cancelled, failed, completed, incomplete oder expired sein kann. |
| [Temperature](../../aspose.pdf.ai/runresponse/temperature/) { get; set; } | Ruft die verwendete Abtasttemperatur für diesen Durchlauf ab oder legt sie fest. Wenn nicht festgelegt, beträgt der Standardwert 1. |
| [ThreadId](../../aspose.pdf.ai/runresponse/threadid/) { get; set; } | Ruft die ID des Threads ab oder legt sie fest, der im Rahmen dieses Durchlaufs ausgeführt wurde. |
| [ToolChoice](../../aspose.pdf.ai/runresponse/toolchoice/) { get; set; } | Ruft ab oder legt fest, welches (falls vorhanden) Werkzeug vom Modell aufgerufen wird. none bedeutet, dass das Modell keine Werkzeuge aufruft und stattdessen eine Nachricht generiert. auto ist der Standardwert und bedeutet, dass das Modell zwischen der Generierung einer Nachricht oder dem Aufruf eines oder mehrerer Werkzeuge wählen kann. required bedeutet, dass das Modell ein oder mehrere Werkzeuge aufrufen muss, bevor es auf den Benutzer antwortet. Das Festlegen eines bestimmten Werkzeugs wie {"type": "file_search"} oder {"type": "function", "function": {"name": "my_function"}} zwingt das Modell, dieses Werkzeug aufzurufen. |
| [Tools](../../aspose.pdf.ai/runresponse/tools/) { get; set; } | Ruft die Liste der Werkzeuge ab oder legt sie fest, die der Assistent für diesen Durchlauf verwendet hat. |
| [TopP](../../aspose.pdf.ai/runresponse/topp/) { get; set; } | Ruft den Nucleus-Sampling-Wert ab oder legt ihn fest, der für diesen Durchlauf verwendet wird. Wenn nicht festgelegt, beträgt der Standardwert 1. |
| [TruncationStrategy](../../aspose.pdf.ai/runresponse/truncationstrategy/) { get; set; } | Ruft die Trunkierungsstrategie ab oder legt sie fest, die steuert, wie ein Thread vor dem Durchlauf gekürzt wird. Verwenden Sie dies, um das anfängliche Kontextfenster des Durchlaufs zu steuern. |
| [Usage](../../aspose.pdf.ai/runresponse/usage/) { get; set; } | Ruft die Nutzungsstatistiken ab oder legt sie fest, die mit dem Durchlauf verbunden sind. Dieser Wert wird null sein, wenn der Durchlauf sich nicht in einem terminalen Zustand befindet (d.h. in_progress, queued usw.). |

### Siehe auch

* Klasse [BaseResponse](../baseresponse/)
* Schnittstelle [IStatus](../istatus/)
* Namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../)