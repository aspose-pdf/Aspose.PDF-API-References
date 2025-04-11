---
title: Class ThreadMessageCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.ThreadMessageCreateRequest klass. Representerar en begäran om att skapa ett meddelande inom en tråd
type: docs
weight: 1120
url: /sv/net/aspose.pdf.ai/threadmessagecreaterequest/
---
## ThreadMessageCreateRequest klass

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
| [Attachments](../../aspose.pdf.ai/threadmessagecreaterequest/attachments/) { get; set; } | Hämtar eller sätter en lista över filer som är bifogade till meddelandet. |
| [Content](../../aspose.pdf.ai/threadmessagecreaterequest/content/) { get; set; } | Hämtar eller sätter innehållet i meddelandet. Kan vara en sträng eller en array av innehållsdela. |
| [Metadata](../../aspose.pdf.ai/threadmessagecreaterequest/metadata/) { get; set; } | Hämtar eller sätter en uppsättning av 16 nyckel-värde-par som kan bifogas till ett objekt. Detta kan vara användbart för att lagra ytterligare information om objektet i ett strukturerat format. Nycklar kan vara maximalt 64 tecken långa och värden kan vara maximalt 512 tecken långa. |
| [Role](../../aspose.pdf.ai/threadmessagecreaterequest/role/) { get; set; } | Hämtar eller sätter rollen för entiteten som skapar meddelandet. Tillåtna värden inkluderar: "user", "assistant". |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [FromAssistant](../../aspose.pdf.ai/threadmessagecreaterequest/fromassistant/)() | Skapar en ny `ThreadMessageCreateRequest` med rollen inställd på Assistant. |
| static [FromUser](../../aspose.pdf.ai/threadmessagecreaterequest/fromuser/)() | Skapar en ny `ThreadMessageCreateRequest` med rollen inställd på User. |
| [WithAttachments](../../aspose.pdf.ai/threadmessagecreaterequest/withattachments/)(List&lt;Attachment&gt;) | Sätter bilagorna för trådmeddelandebegäran. |
| [WithContent](../../aspose.pdf.ai/threadmessagecreaterequest/withcontent/)(MessageContentRequest) | Lägger till ett meddelandeinnehåll till trådmeddelandebegäran. |
| [WithContents](../../aspose.pdf.ai/threadmessagecreaterequest/withcontents/)(List&lt;MessageContentRequest&gt;) | Sätter meddelandeinnehållet för trådmeddelandebegäran. |
| [WithMetadata](../../aspose.pdf.ai/threadmessagecreaterequest/withmetadata/)(Dictionary&lt;string, string&gt;) | Sätter metadata för trådmeddelandebegäran. |

### Se Även

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)