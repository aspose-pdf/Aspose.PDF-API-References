---
title: Class CompletionCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.CompletionCreateRequest-Klasse. Stellt eine Anfrage für den Endpunkt Create Chat Completion dar
type: docs
weight: 220
url: /de/net/aspose.pdf.ai/completioncreaterequest/
---
## CompletionCreateRequest-Klasse

Stellt eine Anfrage für den Endpunkt Create Chat Completion dar.

```csharp
public class CompletionCreateRequest
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [CompletionCreateRequest](completioncreaterequest/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [FrequencyPenalty](../../aspose.pdf.ai/completioncreaterequest/frequencypenalty/) { get; set; } | Ruft eine Zahl zwischen -2.0 und 2.0 ab oder legt sie fest. Positive Werte bestrafen neue Tokens basierend auf ihrer bisherigen Häufigkeit im Text, wodurch die Wahrscheinlichkeit des Modells verringert wird, dieselbe Zeile wörtlich zu wiederholen. |
| [LogitBias](../../aspose.pdf.ai/completioncreaterequest/logitbias/) { get; set; } | Ruft die Wahrscheinlichkeit ab oder legt sie fest, dass bestimmte Tokens in der Vervollständigung erscheinen. Akzeptiert ein JSON-Objekt, das Tokens (angegeben durch ihre Token-ID im Tokenizer) einem zugehörigen Bias-Wert von -100 bis 100 zuordnet. |
| [Logprobs](../../aspose.pdf.ai/completioncreaterequest/logprobs/) { get; set; } | Ruft ab oder legt fest, ob die Log-Wahrscheinlichkeiten der Ausgabetokens zurückgegeben werden sollen oder nicht. Wenn wahr, werden die Log-Wahrscheinlichkeiten jedes Ausgabetokens, das im Inhalt der Nachricht zurückgegeben wird, zurückgegeben. |
| [MaxTokens](../../aspose.pdf.ai/completioncreaterequest/maxtokens/) { get; set; } | Ruft die maximale Anzahl von Tokens ab oder legt sie fest, die in der Vervollständigung generiert werden sollen. |
| [Messages](../../aspose.pdf.ai/completioncreaterequest/messages/) { get; set; } | Ruft eine Liste von Nachrichten ab oder legt sie fest, die das Gespräch bisher umfassen. |
| [Model](../../aspose.pdf.ai/completioncreaterequest/model/) { get; set; } | Ruft die ID des zu verwendenden Modells ab oder legt sie fest. |
| [NumberOfChoices](../../aspose.pdf.ai/completioncreaterequest/numberofchoices/) { get; set; } | Ruft ab oder legt fest, wie viele Chat-Vervollständigungsoptionen für jede Eingabemeldung generiert werden sollen. Beachten Sie, dass Sie basierend auf der Anzahl der generierten Tokens über alle Optionen hinweg belastet werden. Halten Sie n auf 1, um die Kosten zu minimieren. |
| [PresencePenalty](../../aspose.pdf.ai/completioncreaterequest/presencepenalty/) { get; set; } | Ruft eine Zahl zwischen -2.0 und 2.0 ab oder legt sie fest. Positive Werte bestrafen neue Tokens basierend darauf, ob sie im bisherigen Text erscheinen, wodurch die Wahrscheinlichkeit des Modells erhöht wird, über neue Themen zu sprechen. |
| [ResponseFormat](../../aspose.pdf.ai/completioncreaterequest/responseformat/) { get; set; } | Ruft ein Objekt ab oder legt es fest, das das Format angibt, das das Modell ausgeben muss. Kompatibel mit GPT-4 Turbo und allen GPT-3.5 Turbo-Modellen, die neuer sind als gpt-3.5-turbo-1106. Das Setzen auf { "type": "json_object" } aktiviert den JSON-Modus, der garantiert, dass die vom Modell generierte Nachricht gültiges JSON ist. |
| [Seed](../../aspose.pdf.ai/completioncreaterequest/seed/) { get; set; } | Ruft den Seed-Wert ab oder legt ihn fest. Diese Funktion befindet sich in der Beta-Phase. Wenn angegeben, wird unser System versuchen, deterministisch zu sampeln, sodass wiederholte Anfragen mit demselben Seed und denselben Parametern dasselbe Ergebnis zurückgeben sollten. Determinismus ist nicht garantiert, und Sie sollten den Parameter system_fingerprint in der Antwort verwenden, um Änderungen im Backend zu überwachen. |
| [Stop](../../aspose.pdf.ai/completioncreaterequest/stop/) { get; set; } | Ruft bis zu 4 Sequenzen ab oder legt sie fest, bei denen die API das Generieren weiterer Tokens stoppt. |
| [Stream](../../aspose.pdf.ai/completioncreaterequest/stream/) { get; set; } | Ruft ab oder legt fest, ob Streaming verwendet werden soll. Wenn festgelegt, werden partielle Nachrichten-Deltas gesendet, wie in ChatGPT. Tokens werden als datenbasierte servergesendete Ereignisse gesendet, sobald sie verfügbar sind, wobei der Stream durch eine data: [DONE]-Nachricht beendet wird. |
| [Temperature](../../aspose.pdf.ai/completioncreaterequest/temperature/) { get; set; } | Ruft die zu verwendende Sampling-Temperatur ab oder legt sie fest, zwischen 0 und 2. Höhere Werte wie 0.8 machen die Ausgabe zufälliger, während niedrigere Werte wie 0.2 sie fokussierter und deterministisch machen. |
| [ToolChoice](../../aspose.pdf.ai/completioncreaterequest/toolchoice/) { get; set; } | Ruft ein Objekt ab oder legt es fest, das steuert, welches (falls vorhanden) Tool vom Modell aufgerufen wird. none bedeutet, dass das Modell kein Tool aufruft und stattdessen eine Nachricht generiert. auto bedeutet, dass das Modell zwischen der Generierung einer Nachricht oder dem Aufruf eines oder mehrerer Tools wählen kann. required bedeutet, dass das Modell ein oder mehrere Tools aufrufen muss. Das Festlegen eines bestimmten Tools über {"type": "function", "function": {"name": "my_function"}} zwingt das Modell, dieses Tool aufzurufen. none ist der Standard, wenn keine Tools vorhanden sind. auto ist der Standard, wenn Tools vorhanden sind. |
| [Tools](../../aspose.pdf.ai/completioncreaterequest/tools/) { get; set; } | Ruft eine Liste von Tools ab oder legt sie fest, die das Modell aufrufen kann. Derzeit werden nur Funktionen als Tool unterstützt. Verwenden Sie dies, um eine Liste von Funktionen bereitzustellen, für die das Modell JSON-Eingaben generieren kann. Maximal 128 Funktionen werden unterstützt. |
| [TopP](../../aspose.pdf.ai/completioncreaterequest/topp/) { get; set; } | Ruft eine Alternative zum Sampling mit Temperatur ab oder legt sie fest, die als Nucleus-Sampling bezeichnet wird, bei dem das Modell die Ergebnisse der Tokens mit der top_p-Wahrscheinlichkeitsmasse berücksichtigt. 0.1 bedeutet, dass nur die Tokens berücksichtigt werden, die die obersten 10% der Wahrscheinlichkeitsmasse ausmachen. |
| [User](../../aspose.pdf.ai/completioncreaterequest/user/) { get; set; } | Ruft eine eindeutige Kennung ab oder legt sie fest, die Ihren Endbenutzer darstellt, was OpenAI helfen kann, Missbrauch zu überwachen und zu erkennen. |

### Siehe auch

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)