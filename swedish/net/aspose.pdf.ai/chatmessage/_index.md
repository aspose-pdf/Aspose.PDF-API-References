---
title: Class ChatMessage
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.ChatMessage klass. Ett chattkompletteringsmeddelande som genererats av modellen
type: docs
weight: 190
url: /sv/net/aspose.pdf.ai/chatmessage/
---
## ChatMessage klass

Ett chattkompletteringsmeddelande som genererats av modellen.

```csharp
public class ChatMessage
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ChatMessage](chatmessage/#constructor)() | Initierar en ny instans av `ChatMessage` klassen. |
| [ChatMessage](chatmessage/#constructor_1)(string, string) | Initierar en ny instans av `ChatMessage` klassen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Content](../../aspose.pdf.ai/chatmessage/content/) { get; set; } | Hämtar eller ställer in innehållet i meddelandet. |
| [Name](../../aspose.pdf.ai/chatmessage/name/) { get; set; } | Hämtar eller ställer in ett valfritt namn för deltagaren. Ger modellen information för att särskilja mellan deltagare med samma roll. |
| [Role](../../aspose.pdf.ai/chatmessage/role/) { get; set; } | Hämtar eller ställer in rollen för meddelandets författare. |
| [ToolCallId](../../aspose.pdf.ai/chatmessage/toolcallid/) { get; set; } | Hämtar eller ställer in verktygskall som detta meddelande svarar på. |
| [ToolCalls](../../aspose.pdf.ai/chatmessage/toolcalls/) { get; set; } | Hämtar eller ställer in verktygskall som genererats av modellen, såsom funktionsanrop. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [FromAssistant](../../aspose.pdf.ai/chatmessage/fromassistant/)(string) | Skapar ett nytt ChatMessage-objekt som representerar ett assistentmeddelande. |
| static [FromSystem](../../aspose.pdf.ai/chatmessage/fromsystem/)(string) | Skapar ett nytt ChatMessage-objekt som representerar ett systemmeddelande. |
| static [FromUser](../../aspose.pdf.ai/chatmessage/fromuser/)(string) | Skapar ett nytt ChatMessage-objekt som representerar ett användarmedelande. |

### Se Även

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)