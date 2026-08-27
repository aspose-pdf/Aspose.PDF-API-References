---
title: "Klass ThreadMessageCreateRequest"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.AI.ThreadMessageCreateRequest-klass. Representerar en begäran om att skapa ett meddelande inom en tråd"
type: docs
weight: 1210
url: /sv/net/aspose.pdf.ai/threadmessagecreaterequest/
---
## ThreadMessageCreateRequest class

Representerar en begäran om att skapa ett meddelande inom en tråd.

```csharp
public class ThreadMessageCreateRequest
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ThreadMessageCreateRequest](threadmessagecreaterequest/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Attachments](../../aspose.pdf.ai/threadmessagecreaterequest/attachments/) { get; set; } | Hämtar eller anger en lista med filer som är bifogade till meddelandet. |
| [Content](../../aspose.pdf.ai/threadmessagecreaterequest/content/) { get; set; } | Hämtar eller anger innehållet i meddelandet. Kan vara en sträng eller en array av innehållsdelar. |
| [Metadata](../../aspose.pdf.ai/threadmessagecreaterequest/metadata/) { get; set; } | Hämtar eller anger en uppsättning av 16 nyckel‑värdepar som kan bifogas ett objekt. Detta kan vara användbart för att lagra ytterligare information om objektet i ett strukturerat format. Nycklar kan vara högst 64 tecken långa och värden kan vara högst 512 tecken långa. |
| [Role](../../aspose.pdf.ai/threadmessagecreaterequest/role/) { get; set; } | Hämtar eller anger rollen för enheten som skapar meddelandet. Tillåtna värden inkluderar: "user", "assistant". |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [FromAssistant](../../aspose.pdf.ai/threadmessagecreaterequest/fromassistant/)() | Skapar en ny `ThreadMessageCreateRequest` med rollen satt till Assistant. |
| static [FromUser](../../aspose.pdf.ai/threadmessagecreaterequest/fromuser/)() | Skapar en ny `ThreadMessageCreateRequest` med rollen satt till User. |
| [WithAttachments](../../aspose.pdf.ai/threadmessagecreaterequest/withattachments/)(List&lt;Attachment&gt;) | Anger bilagorna för trådmeldande förfrågan. |
| [WithContent](../../aspose.pdf.ai/threadmessagecreaterequest/withcontent/)(MessageContentRequest) | Lägger till ett meddelandeinnehåll till trådmeldande förfrågan. |
| [WithContents](../../aspose.pdf.ai/threadmessagecreaterequest/withcontents/)(List&lt;MessageContentRequest&gt;) | Anger meddelandeinnehållet för trådmeldande förfrågan. |
| [WithMetadata](../../aspose.pdf.ai/threadmessagecreaterequest/withmetadata/)(Dictionary&lt;string, string&gt;) | Anger metadata för trådmeldande förfrågan. |

### Se även

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


