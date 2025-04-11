---
title: Class RunCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.RunCreateRequest-Klasse. Stellt eine Anfrage zum Erstellen eines Runs dar
type: docs
weight: 980
url: /de/net/aspose.pdf.ai/runcreaterequest/
---
## RunCreateRequest-Klasse

Stellt eine Anfrage zum Erstellen eines Runs dar.

```csharp
public class RunCreateRequest
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [RunCreateRequest](runcreaterequest/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AdditionalInstructions](../../aspose.pdf.ai/runcreaterequest/additionalinstructions/) { get; set; } | Ruft die zusätzlichen Anweisungen ab oder legt sie fest. Fügt zusätzliche Anweisungen am Ende der Anweisungen für den Run hinzu. Dies ist nützlich, um das Verhalten pro Run zu ändern, ohne andere Anweisungen zu überschreiben. |
| [AdditionalMessages](../../aspose.pdf.ai/runcreaterequest/additionalmessages/) { get; set; } | Ruft die zusätzlichen Nachrichten an den Thread vor der Erstellung des Runs ab oder legt sie fest. |
| [AssistantId](../../aspose.pdf.ai/runcreaterequest/assistantid/) { get; set; } | Ruft die ID des Assistenten ab oder legt sie fest, die zur Ausführung dieses Runs verwendet werden soll. |
| [Instructions](../../aspose.pdf.ai/runcreaterequest/instructions/) { get; set; } | Ruft die Anweisungen ab oder legt sie fest, die die Anweisungen des Assistenten überschreiben. Dies ist nützlich, um das Verhalten pro Run zu ändern. |
| [MaxCompletionTokens](../../aspose.pdf.ai/runcreaterequest/maxcompletiontokens/) { get; set; } | Ruft die maximale Anzahl von Abschluss-Token ab oder legt sie fest, die im Verlauf des Runs verwendet werden dürfen. Der Run wird sich bemühen, nur die angegebene Anzahl von Abschluss-Token über mehrere Runden des Runs zu verwenden. Wenn der Run die angegebene Anzahl von Abschluss-Token überschreitet, endet der Run mit dem Status unvollständig. Siehe incomplete_details für weitere Informationen. |
| [MaxPromptTokens](../../aspose.pdf.ai/runcreaterequest/maxprompttokens/) { get; set; } | Ruft die maximale Anzahl von Eingabe-Token ab oder legt sie fest, die im Verlauf des Runs verwendet werden dürfen. Der Run wird sich bemühen, nur die angegebene Anzahl von Eingabe-Token über mehrere Runden des Runs zu verwenden. Wenn der Run die angegebene Anzahl von Eingabe-Token überschreitet, endet der Run mit dem Status unvollständig. Siehe incomplete_details für weitere Informationen. |
| [Metadata](../../aspose.pdf.ai/runcreaterequest/metadata/) { get; set; } | Ruft ein Set von 16 Schlüssel-Wert-Paaren ab oder legt es fest, die an ein Objekt angehängt werden können. Dies kann nützlich sein, um zusätzliche Informationen über das Objekt in einem strukturierten Format zu speichern. Schlüssel können maximal 64 Zeichen lang sein und Werte maximal 512 Zeichen lang. |
| [Model](../../aspose.pdf.ai/runcreaterequest/model/) { get; set; } | Ruft die ID des Modells ab oder legt sie fest, die zur Ausführung dieses Runs verwendet werden soll. Wenn hier ein Wert angegeben wird, überschreibt er das mit dem Assistenten verbundene Modell. Andernfalls wird das mit dem Assistenten verbundene Modell verwendet. |
| [ResponseFormat](../../aspose.pdf.ai/runcreaterequest/responseformat/) { get; set; } | Ruft das Antwortformat ab oder legt es fest. Gibt das Format an, das das Modell ausgeben muss. Kompatibel mit GPT-4o, GPT-4 Turbo und allen GPT-3.5 Turbo-Modellen seit gpt-3.5-turbo-1106. Das Setzen auf { "type": "json_object" } aktiviert den JSON-Modus, der garantiert, dass die vom Modell generierte Nachricht gültiges JSON ist. Wichtig: Wenn Sie den JSON-Modus verwenden, müssen Sie das Modell auch anweisen, selbst über eine System- oder Benutzernachricht JSON zu erzeugen. Andernfalls kann das Modell einen unendlichen Strom von Leerzeichen erzeugen, bis die Generierung das Token-Limit erreicht, was zu einer langwierigen und scheinbar "festgefahrenen" Anfrage führt. Beachten Sie auch, dass der Nachrichteninhalt teilweise abgeschnitten werden kann, wenn finish_reason="length" angegeben ist, was darauf hinweist, dass die Generierung die max_tokens überschritt oder die Konversation die maximale Kontextlänge überschritt. |
| [Stream](../../aspose.pdf.ai/runcreaterequest/stream/) { get; set; } | Ruft ab oder legt fest, ob Streaming verwendet werden soll. Wenn true, gibt es einen Stream von Ereignissen zurück, die während des Runs als servergesendete Ereignisse auftreten, und endet, wenn der Run einen terminalen Zustand mit einer data: [DONE]-Nachricht erreicht. |
| [Temperature](../../aspose.pdf.ai/runcreaterequest/temperature/) { get; set; } | Ruft die zu verwendende Abtasttemperatur ab oder legt sie fest, zwischen 0 und 2. Höhere Werte wie 0.8 machen die Ausgabe zufälliger, während niedrigere Werte wie 0.2 sie fokussierter und deterministisch machen. |
| [ToolChoice](../../aspose.pdf.ai/runcreaterequest/toolchoice/) { get; set; } | Ruft ab oder legt fest, welches (falls vorhanden) Werkzeug vom Modell aufgerufen wird. none bedeutet, dass das Modell keine Werkzeuge aufruft und stattdessen eine Nachricht generiert. auto ist der Standardwert und bedeutet, dass das Modell zwischen der Generierung einer Nachricht oder dem Aufruf eines oder mehrerer Werkzeuge wählen kann. required bedeutet, dass das Modell ein oder mehrere Werkzeuge aufrufen muss, bevor es auf den Benutzer antwortet. Das Angeben eines bestimmten Werkzeugs wie {"type": "file_search"} oder {"type": "function", "function": {"name": "my_function"}} zwingt das Modell, dieses Werkzeug aufzurufen. |
| [Tools](../../aspose.pdf.ai/runcreaterequest/tools/) { get; set; } | Ruft die Werkzeuge ab oder legt sie fest, die die Werkzeuge überschreiben, die der Assistent für diesen Run verwenden kann. Dies ist nützlich, um das Verhalten pro Run zu ändern. |
| [TopP](../../aspose.pdf.ai/runcreaterequest/topp/) { get; set; } | Ruft eine Alternative zum Sampling mit Temperatur ab oder legt sie fest, die als Nucleus-Sampling bezeichnet wird, bei dem das Modell die Ergebnisse der Token mit der top_p-Wahrscheinlichkeitsmasse berücksichtigt. 0.1 bedeutet also, dass nur die Token, die die obersten 10% der Wahrscheinlichkeitsmasse ausmachen, berücksichtigt werden. Wir empfehlen im Allgemeinen, dies oder die Temperatur zu ändern, aber nicht beides. |
| [TruncationStrategy](../../aspose.pdf.ai/runcreaterequest/truncationstrategy/) { get; set; } | Ruft die Trunkierungsstrategie ab oder legt sie fest. Steuert, wie ein Thread vor dem Run gekürzt wird. Verwenden Sie dies, um das anfängliche Kontextfenster des Runs zu steuern. |

### Siehe auch

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)