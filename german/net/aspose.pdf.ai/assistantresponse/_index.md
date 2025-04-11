---
title: Class AssistantResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.AssistantResponse-Klasse. Stellt einen Assistenten dar, der das Modell aufrufen und Werkzeuge verwenden kann
type: docs
weight: 140
url: /de/net/aspose.pdf.ai/assistantresponse/
---
## Klasse AssistantResponse

Stellt einen Assistenten dar, der das Modell aufrufen und Werkzeuge verwenden kann.

```csharp
public class AssistantResponse : BaseResponse
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [AssistantResponse](assistantresponse/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/assistantresponse/createdat/) { get; set; } | Ruft den Unix-Zeitstempel (in Sekunden) ab oder setzt ihn, wann der Assistent erstellt wurde. |
| [Description](../../aspose.pdf.ai/assistantresponse/description/) { get; set; } | Ruft die Beschreibung des Assistenten ab oder setzt sie. Die maximale Länge beträgt 512 Zeichen. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Ruft die Antwortdetails ab oder setzt sie. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Ruft den HTTP-Antwortfehler ab oder setzt ihn. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Ruft die Fehlerinformationen ab oder setzt sie. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Ruft die HTTP-Antwortheader ab oder setzt sie. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Ruft den HTTP-Statuscode ab oder setzt ihn. |
| [Id](../../aspose.pdf.ai/assistantresponse/id/) { get; set; } | Ruft den Bezeichner ab oder setzt ihn, der in API-Endpunkten referenziert werden kann. |
| [Instructions](../../aspose.pdf.ai/assistantresponse/instructions/) { get; set; } | Ruft die Systemanweisungen ab oder setzt sie, die der Assistent verwendet. Die maximale Länge beträgt 256.000 Zeichen. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Gibt an, ob die Antwort erfolgreich war. |
| [Metadata](../../aspose.pdf.ai/assistantresponse/metadata/) { get; set; } | Ruft eine Menge von 16 Schlüssel-Wert-Paaren ab oder setzt sie, die an ein Objekt angehängt werden können. Dies kann nützlich sein, um zusätzliche Informationen über das Objekt in einem strukturierten Format zu speichern. Schlüssel können maximal 64 Zeichen lang sein und Werte maximal 512 Zeichen lang. |
| [Model](../../aspose.pdf.ai/assistantresponse/model/) { get; set; } | Ruft die ID des zu verwendenden Modells ab oder setzt sie. Sie können die API zum Auflisten von Modellen verwenden, um alle verfügbaren Modelle zu sehen, oder unsere Modellübersicht für Beschreibungen davon. |
| [Name](../../aspose.pdf.ai/assistantresponse/name/) { get; set; } | Ruft den Namen des Assistenten ab oder setzt ihn. Die maximale Länge beträgt 256 Zeichen. |
| [Object](../../aspose.pdf.ai/assistantresponse/object/) { get; set; } | Ruft den Objekttyp ab oder setzt ihn, der immer Assistent ist. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Ruft den Fehlergrundsatz ab. |
| [ResponseFormat](../../aspose.pdf.ai/assistantresponse/responseformat/) { get; set; } | Ruft das Format ab oder setzt es, das das Modell ausgeben muss. Kompatibel mit GPT-4o, GPT-4 Turbo und allen GPT-3.5 Turbo-Modellen seit gpt-3.5-turbo-1106. Das Setzen auf { "type": "json_object" } aktiviert den JSON-Modus, der garantiert, dass die vom Modell generierte Nachricht gültiges JSON ist. Wichtig: Wenn Sie den JSON-Modus verwenden, müssen Sie das Modell auch anweisen, JSON selbst über eine System- oder Benutzernachricht zu erzeugen. Andernfalls kann das Modell einen unendlichen Strom von Leerzeichen erzeugen, bis die Generierung das Token-Limit erreicht, was zu einer langwierigen und scheinbar "festgefahrenen" Anfrage führt. Beachten Sie auch, dass der Nachrichteninhalt teilweise abgeschnitten werden kann, wenn finish_reason="length" angezeigt wird, was darauf hinweist, dass die Generierung die max_tokens überschritt oder das Gespräch die maximale Kontextlänge überschritt. |
| [Temperature](../../aspose.pdf.ai/assistantresponse/temperature/) { get; set; } | Ruft die zu verwendende Abtasttemperatur ab oder setzt sie, zwischen 0 und 2. Höhere Werte wie 0.8 machen die Ausgabe zufälliger, während niedrigere Werte wie 0.2 sie fokussierter und deterministisch machen. |
| [ToolResources](../../aspose.pdf.ai/assistantresponse/toolresources/) { get; set; } | Ruft eine Menge von Ressourcen ab oder setzt sie, die von den Werkzeugen des Assistenten verwendet werden. Die Ressourcen sind spezifisch für den Typ des Werkzeugs. Zum Beispiel benötigt das Werkzeug code_interpreter eine Liste von Datei-IDs, während das Werkzeug file_search eine Liste von Vektor-Store-IDs benötigt. |
| [Tools](../../aspose.pdf.ai/assistantresponse/tools/) { get; set; } | Ruft eine Liste von Werkzeugen ab oder setzt sie, die im Assistenten aktiviert sind. Es kann maximal 128 Werkzeuge pro Assistenten geben. Werkzeuge können vom Typ code_interpreter, file_search oder function sein. |
| [TopP](../../aspose.pdf.ai/assistantresponse/topp/) { get; set; } | Ruft eine Alternative zur Abtastung mit Temperatur ab oder setzt sie, die als Nucleus-Sampling bezeichnet wird, bei der das Modell die Ergebnisse der Token mit der top_p-Wahrscheinlichkeitsmasse berücksichtigt. 0.1 bedeutet also, dass nur die Token berücksichtigt werden, die die obersten 10% der Wahrscheinlichkeitsmasse ausmachen. Wir empfehlen im Allgemeinen, dies oder die Temperatur zu ändern, aber nicht beides. |

### Siehe auch

* Klasse [BaseResponse](../baseresponse/)
* Namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../)