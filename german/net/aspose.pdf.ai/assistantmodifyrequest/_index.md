---
title: Class AssistantModifyRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.AssistantModifyRequest-Klasse. Anforderungsobjekt zur Modifizierung eines Assistenten
type: docs
weight: 130
url: /de/net/aspose.pdf.ai/assistantmodifyrequest/
---
## AssistantModifyRequest-Klasse

Anforderungsobjekt zur Modifizierung eines Assistenten.

```csharp
public class AssistantModifyRequest : AssistantCreateRequest
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [AssistantModifyRequest](assistantmodifyrequest/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Description](../../aspose.pdf.ai/assistantcreaterequest/description/) { get; set; } | Ruft die Beschreibung des Assistenten ab oder legt sie fest. Die maximale Länge beträgt 512 Zeichen. |
| [Instructions](../../aspose.pdf.ai/assistantcreaterequest/instructions/) { get; set; } | Ruft die Systemanweisungen ab oder legt sie fest, die der Assistent verwendet. Die maximale Länge beträgt 256.000 Zeichen. |
| [Metadata](../../aspose.pdf.ai/assistantcreaterequest/metadata/) { get; set; } | Ruft ein Set von 16 Schlüssel-Wert-Paaren ab oder legt es fest, das an ein Objekt angehängt werden kann. Dies kann nützlich sein, um zusätzliche Informationen über das Objekt in einem strukturierten Format zu speichern. Schlüssel können maximal 64 Zeichen lang sein und Werte maximal 512 Zeichen lang. |
| [Model](../../aspose.pdf.ai/assistantcreaterequest/model/) { get; set; } | Ruft die ID des zu verwendenden Modells ab oder legt sie fest. Sie können die API zur Auflistung von Modellen verwenden, um alle verfügbaren Modelle zu sehen, oder unsere Modellübersicht für Beschreibungen davon. |
| [Name](../../aspose.pdf.ai/assistantcreaterequest/name/) { get; set; } | Ruft den Namen des Assistenten ab oder legt ihn fest. Die maximale Länge beträgt 256 Zeichen. |
| [ResponseFormat](../../aspose.pdf.ai/assistantcreaterequest/responseformat/) { get; set; } | Ruft das Format ab oder legt es fest, das das Modell ausgeben muss. Kompatibel mit GPT-4o, GPT-4 Turbo und allen GPT-3.5 Turbo-Modellen seit gpt-3.5-turbo-1106. Das Setzen auf { "type": "json_object" } aktiviert den JSON-Modus, der garantiert, dass die vom Modell generierte Nachricht gültiges JSON ist. Wichtig: Wenn Sie den JSON-Modus verwenden, müssen Sie das Modell auch anweisen, selbst JSON über eine System- oder Benutzernachricht zu erzeugen. Andernfalls kann das Modell einen unendlichen Strom von Leerzeichen erzeugen, bis die Generierung das Token-Limit erreicht, was zu einer langwierigen und scheinbar "festgefahrenen" Anfrage führt. Beachten Sie auch, dass der Nachrichteninhalt teilweise abgeschnitten werden kann, wenn finish_reason="length" angezeigt wird, was darauf hinweist, dass die Generierung das max_tokens überschritten hat oder das Gespräch die maximale Kontextlänge überschritten hat. |
| [Temperature](../../aspose.pdf.ai/assistantcreaterequest/temperature/) { get; set; } | Ruft die zu verwendende Abtasttemperatur ab oder legt sie fest, zwischen 0 und 2. Höhere Werte wie 0.8 machen die Ausgabe zufälliger, während niedrigere Werte wie 0.2 sie fokussierter und deterministisch machen. |
| [ToolResources](../../aspose.pdf.ai/assistantcreaterequest/toolresources/) { get; set; } | Ruft Ressourcen ab oder legt sie fest, die von den Werkzeugen des Assistenten verwendet werden. Die Ressourcen sind spezifisch für den Typ des Werkzeugs. Zum Beispiel benötigt das Werkzeug code_interpreter eine Liste von Datei-IDs, während das Werkzeug file_search eine Liste von Vektor-Store-IDs benötigt. |
| [Tools](../../aspose.pdf.ai/assistantcreaterequest/tools/) { get; set; } | Ruft eine Liste von Werkzeugen ab oder legt sie fest, die im Assistenten aktiviert sind. Es können maximal 128 Werkzeuge pro Assistenten vorhanden sein. Werkzeuge können von den Typen code_interpreter, file_search oder function sein. |
| [TopP](../../aspose.pdf.ai/assistantcreaterequest/topp/) { get; set; } | Ruft eine Alternative zur Abtastung mit Temperatur ab oder legt sie fest, die als Kernabstimmung bezeichnet wird, bei der das Modell die Ergebnisse der Token mit der top_p-Wahrscheinlichkeitsmasse berücksichtigt. 0.1 bedeutet also, dass nur die Token berücksichtigt werden, die die obersten 10% der Wahrscheinlichkeitsmasse ausmachen. Wir empfehlen im Allgemeinen, dies oder die Temperatur zu ändern, jedoch nicht beides. |

### Siehe auch

* Klasse [AssistantCreateRequest](../assistantcreaterequest/)
* Namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../)