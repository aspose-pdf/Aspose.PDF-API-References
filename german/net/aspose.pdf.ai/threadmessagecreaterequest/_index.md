---
title: Class ThreadMessageCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.ThreadMessageCreateRequest-Klasse. Stellt eine Anfrage zum Erstellen einer Nachricht innerhalb eines Threads dar
type: docs
weight: 1120
url: /de/net/aspose.pdf.ai/threadmessagecreaterequest/
---
## Klasse ThreadMessageCreateRequest

Stellt eine Anfrage zum Erstellen einer Nachricht innerhalb eines Threads dar.

```csharp
public class ThreadMessageCreateRequest
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ThreadMessageCreateRequest](threadmessagecreaterequest/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Attachments](../../aspose.pdf.ai/threadmessagecreaterequest/attachments/) { get; set; } | Ruft eine Liste von Dateien ab oder legt sie fest, die an die Nachricht angehängt sind. |
| [Content](../../aspose.pdf.ai/threadmessagecreaterequest/content/) { get; set; } | Ruft den Inhalt der Nachricht ab oder legt ihn fest. Kann ein String oder ein Array von Inhaltsbestandteilen sein. |
| [Metadata](../../aspose.pdf.ai/threadmessagecreaterequest/metadata/) { get; set; } | Ruft ein Set von 16 Schlüssel-Wert-Paaren ab oder legt es fest, die an ein Objekt angehängt werden können. Dies kann nützlich sein, um zusätzliche Informationen über das Objekt in einem strukturierten Format zu speichern. Schlüssel können maximal 64 Zeichen lang sein und Werte maximal 512 Zeichen lang. |
| [Role](../../aspose.pdf.ai/threadmessagecreaterequest/role/) { get; set; } | Ruft die Rolle der Entität ab oder legt sie fest, die die Nachricht erstellt. Erlaubte Werte sind: "user", "assistant". |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromAssistant](../../aspose.pdf.ai/threadmessagecreaterequest/fromassistant/)() | Erstellt eine neue `ThreadMessageCreateRequest` mit der Rolle, die auf Assistant gesetzt ist. |
| static [FromUser](../../aspose.pdf.ai/threadmessagecreaterequest/fromuser/)() | Erstellt eine neue `ThreadMessageCreateRequest` mit der Rolle, die auf User gesetzt ist. |
| [WithAttachments](../../aspose.pdf.ai/threadmessagecreaterequest/withattachments/)(List&lt;Attachment&gt;) | Legt die Anhänge für die Thread-Nachrichtenanfrage fest. |
| [WithContent](../../aspose.pdf.ai/threadmessagecreaterequest/withcontent/)(MessageContentRequest) | Fügt einen Nachrichteninhalt zur Thread-Nachrichtenanfrage hinzu. |
| [WithContents](../../aspose.pdf.ai/threadmessagecreaterequest/withcontents/)(List&lt;MessageContentRequest&gt;) | Legt die Nachrichteninhalte für die Thread-Nachrichtenanfrage fest. |
| [WithMetadata](../../aspose.pdf.ai/threadmessagecreaterequest/withmetadata/)(Dictionary&lt;string, string&gt;) | Legt die Metadaten für die Thread-Nachrichtenanfrage fest. |

### Siehe auch

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)