---
title: Class ChatMessage
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.ChatMessage-Klasse. Eine vom Modell generierte Chat-Vervollständigungsnachricht
type: docs
weight: 190
url: /de/net/aspose.pdf.ai/chatmessage/
---
## ChatMessage-Klasse

Eine vom Modell generierte Chat-Vervollständigungsnachricht.

```csharp
public class ChatMessage
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ChatMessage](chatmessage/#constructor)() | Initialisiert eine neue Instanz der `ChatMessage`-Klasse. |
| [ChatMessage](chatmessage/#constructor_1)(string, string) | Initialisiert eine neue Instanz der `ChatMessage`-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Content](../../aspose.pdf.ai/chatmessage/content/) { get; set; } | Ruft den Inhalt der Nachricht ab oder legt ihn fest. |
| [Name](../../aspose.pdf.ai/chatmessage/name/) { get; set; } | Ruft einen optionalen Namen für den Teilnehmer ab oder legt ihn fest. Bietet dem Modell Informationen, um zwischen Teilnehmern derselben Rolle zu unterscheiden. |
| [Role](../../aspose.pdf.ai/chatmessage/role/) { get; set; } | Ruft die Rolle des Autors der Nachricht ab oder legt sie fest. |
| [ToolCallId](../../aspose.pdf.ai/chatmessage/toolcallid/) { get; set; } | Ruft den Tool-Call ab oder legt ihn fest, auf den diese Nachricht antwortet. |
| [ToolCalls](../../aspose.pdf.ai/chatmessage/toolcalls/) { get; set; } | Ruft die vom Modell generierten Tool-Calls ab oder legt sie fest, wie z.B. Funktionsaufrufe. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromAssistant](../../aspose.pdf.ai/chatmessage/fromassistant/)(string) | Erstellt ein neues ChatMessage-Objekt, das eine Assistentennachricht darstellt. |
| static [FromSystem](../../aspose.pdf.ai/chatmessage/fromsystem/)(string) | Erstellt ein neues ChatMessage-Objekt, das eine Systemnachricht darstellt. |
| static [FromUser](../../aspose.pdf.ai/chatmessage/fromuser/)(string) | Erstellt ein neues ChatMessage-Objekt, das eine Benutzernachricht darstellt. |

### Siehe auch

* Namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../)