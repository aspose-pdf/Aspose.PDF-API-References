---
title: "Klass ChatMessage"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.AI.ChatMessage‑klass. Ett chatt‑slutförandemeddelande som genererats av modellen"
type: docs
weight: 190
url: /sv/net/aspose.pdf.ai/chatmessage/
---
## ChatMessage class

Ett chattkompletteringsmeddelande genererat av modellen.

```csharp
public class ChatMessage
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ChatMessage](chatmessage/#constructor)() | Initierar en ny instans av klassen `ChatMessage`. |
| [ChatMessage](chatmessage/#constructor_1)(string, string) | Initierar en ny instans av klassen `ChatMessage`. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Content](../../aspose.pdf.ai/chatmessage/content/) { get; set; } | Hämtar eller anger innehållet i meddelandet. |
| [Name](../../aspose.pdf.ai/chatmessage/name/) { get; set; } | Hämtar eller anger ett valfritt namn för deltagaren. Tillhandahåller modellinformation för att särskilja mellan deltagare med samma roll. |
| [Role](../../aspose.pdf.ai/chatmessage/role/) { get; set; } | Hämtar eller anger författarens roll för meddelandet. |
| [ToolCallId](../../aspose.pdf.ai/chatmessage/toolcallid/) { get; set; } | Hämtar eller anger verktygsanropet som detta meddelande svarar på. |
| [ToolCalls](../../aspose.pdf.ai/chatmessage/toolcalls/) { get; set; } | Hämtar eller anger verktygsanropen som genererats av modellen, såsom funktionsanrop. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [FromAssistant](../../aspose.pdf.ai/chatmessage/fromassistant/)(string) | Skapar ett nytt ChatMessage-objekt som representerar ett assistentmeddelande. |
| static [FromSystem](../../aspose.pdf.ai/chatmessage/fromsystem/)(string) | Skapar ett nytt ChatMessage-objekt som representerar ett systemmeddelande. |
| static [FromUser](../../aspose.pdf.ai/chatmessage/fromuser/)(string) | Skapar ett nytt ChatMessage-objekt som representerar ett användarmeddelande. |

### Se även

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


