---
title: Class RunThreadCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.RunThreadCreateRequest-Klasse. Stellt eine Anfrage zum Erstellen eines Threads und dessen Ausführung in einer Anfrage dar
type: docs
weight: 1070
url: /de/net/aspose.pdf.ai/runthreadcreaterequest/
---
## Klasse RunThreadCreateRequest

Stellt eine Anfrage zum Erstellen eines Threads und dessen Ausführung in einer Anfrage dar.

```csharp
public class RunThreadCreateRequest
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [RunThreadCreateRequest](runthreadcreaterequest/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runthreadcreaterequest/assistantid/) { get; set; } | Ruft die ID des Assistenten ab oder legt sie fest, die zur Ausführung dieses Laufs verwendet werden soll. |
| [Instructions](../../aspose.pdf.ai/runthreadcreaterequest/instructions/) { get; set; } | Ruft die Anweisungen ab oder legt sie fest, die die Anweisungen des Assistenten überschreiben. Dies ist nützlich, um das Verhalten pro Lauf zu ändern. |
| [MaxCompletionTokens](../../aspose.pdf.ai/runthreadcreaterequest/maxcompletiontokens/) { get; set; } | Ruft die maximale Anzahl von Abschluss-Token ab oder legt sie fest, die im Verlauf des Laufs verwendet werden dürfen. Der Lauf wird sich bemühen, nur die angegebene Anzahl von Abschluss-Token über mehrere Runden des Laufs zu verwenden. Wenn der Lauf die angegebene Anzahl von Abschluss-Token überschreitet, endet der Lauf mit dem Status unvollständig. Siehe incomplete_details für weitere Informationen. |
| [MaxPromptTokens](../../aspose.pdf.ai/runthreadcreaterequest/maxprompttokens/) { get; set; } | Ruft die maximale Anzahl von Eingabe-Token ab oder legt sie fest, die im Verlauf des Laufs verwendet werden dürfen. Der Lauf wird sich bemühen, nur die angegebene Anzahl von Eingabe-Token über mehrere Runden des Laufs zu verwenden. Wenn der Lauf die angegebene Anzahl von Eingabe-Token überschreitet, endet der Lauf mit dem Status unvollständig. Siehe incomplete_details für weitere Informationen. |
| [Metadata](../../aspose.pdf.ai/runthreadcreaterequest/metadata/) { get; set; } | Ruft ein Set von 16 Schlüssel-Wert-Paaren ab oder legt es fest, die an ein Objekt angehängt werden können. Dies kann nützlich sein, um zusätzliche Informationen über das Objekt in einem strukturierten Format zu speichern. Schlüssel können maximal 64 Zeichen lang sein und Werte maximal 512 Zeichen lang. |
| [Model](../../aspose.pdf.ai/runthreadcreaterequest/model/) { get; set; } | Ruft die ID des Modells ab oder legt sie fest, die zur Ausführung dieses Laufs verwendet werden soll. Wenn hier ein Wert angegeben wird, überschreibt er das mit dem Assistenten verbundene Modell. Andernfalls wird das mit dem Assistenten verbundene Modell verwendet. |
| [ResponseFormat](../../aspose.pdf.ai/runthreadcreaterequest/responseformat/) { get; set; } | Ruft das Format ab oder legt es fest, das das Modell ausgeben muss. Kompatibel mit GPT-4o, GPT-4 Turbo und allen GPT-3.5 Turbo-Modellen seit gpt-3.5-turbo-1106. Das Setzen auf { "type": "json_object" } aktiviert den JSON-Modus, der garantiert, dass die vom Modell generierte Nachricht gültiges JSON ist. Wichtig: Wenn Sie den JSON-Modus verwenden, müssen Sie das Modell auch anweisen, selbst über eine System- oder Benutzernachricht JSON zu erzeugen. Andernfalls kann das Modell einen unendlichen Strom von Leerzeichen erzeugen, bis die Generierung das Token-Limit erreicht, was zu einer lang laufenden und scheinbar "festgefahrenen" Anfrage führt. Beachten Sie auch, dass der Nachrichteninhalt teilweise abgeschnitten werden kann, wenn finish_reason="length" angegeben ist, was darauf hinweist, dass die Generierung das max_tokens überschritten hat oder das Gespräch die maximale Kontextlänge überschritten hat. |
| [Stream](../../aspose.pdf.ai/runthreadcreaterequest/stream/) { get; set; } | Ruft ab oder legt fest, ob Streaming verwendet werden soll. Wenn wahr, gibt es einen Stream von Ereignissen zurück, die während des Laufs als servergesendete Ereignisse auftreten, und endet, wenn der Lauf einen terminalen Zustand mit einer data: [DONE]-Nachricht erreicht. |
| [Temperature](../../aspose.pdf.ai/runthreadcreaterequest/temperature/) { get; set; } | Ruft die zu verwendende Abtasttemperatur ab oder legt sie fest, zwischen 0 und 2. Höhere Werte wie 0.8 machen die Ausgabe zufälliger, während niedrigere Werte wie 0.2 sie fokussierter und deterministisch machen. |
| [Thread](../../aspose.pdf.ai/runthreadcreaterequest/thread/) { get; set; } | Ruft eine Anfrage zum Erstellen eines Threads ab oder legt sie fest. |
| [ToolChoice](../../aspose.pdf.ai/runthreadcreaterequest/toolchoice/) { get; set; } | Ruft ab oder legt fest, welches (falls vorhanden) Werkzeug vom Modell aufgerufen wird. none bedeutet, dass das Modell keine Werkzeuge aufruft und stattdessen eine Nachricht generiert. auto ist der Standardwert und bedeutet, dass das Modell zwischen der Generierung einer Nachricht oder dem Aufruf eines oder mehrerer Werkzeuge wählen kann. required bedeutet, dass das Modell ein oder mehrere Werkzeuge aufrufen muss, bevor es auf den Benutzer antwortet. Das Angeben eines bestimmten Werkzeugs wie {"type": "file_search"} oder {"type": "function", "function": {"name": "my_function"}} zwingt das Modell, dieses Werkzeug aufzurufen. |
| [ToolResources](../../aspose.pdf.ai/runthreadcreaterequest/toolresources/) { get; set; } | Ruft ein Set von Ressourcen ab oder legt es fest, die von den Werkzeugen des Assistenten verwendet werden. |
| [Tools](../../aspose.pdf.ai/runthreadcreaterequest/tools/) { get; set; } | Ruft die Werkzeuge ab oder legt sie fest, die die Werkzeuge des Assistenten für diesen Lauf überschreiben. Dies ist nützlich, um das Verhalten pro Lauf zu ändern. |
| [TopP](../../aspose.pdf.ai/runthreadcreaterequest/topp/) { get; set; } | Ruft einen Wert ab oder legt ihn fest, der eine Alternative zur Abtastung mit Temperatur darstellt, genannt Nucleus Sampling, bei dem das Modell die Ergebnisse der Token mit der top_p-Wahrscheinlichkeitsmasse berücksichtigt. Ein Wert von 0.1 bedeutet, dass nur die Token, die die obersten 10% der Wahrscheinlichkeitsmasse ausmachen, berücksichtigt werden. Wir empfehlen im Allgemeinen, dies oder die Temperatur zu ändern, aber nicht beides. |
| [TruncationStrategy](../../aspose.pdf.ai/runthreadcreaterequest/truncationstrategy/) { get; set; } | Ruft die Trunkierungsstrategie ab oder legt sie fest, die steuert, wie ein Thread vor dem Lauf gekürzt wird. Verwenden Sie dies, um das anfängliche Kontextfenster des Laufs zu steuern. |

### Siehe auch

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)