---
title: Class ThreadMessageCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.ThreadMessageCreateRequest. Rappresenta una richiesta per creare un messaggio all'interno di un thread
type: docs
weight: 1120
url: /it/net/aspose.pdf.ai/threadmessagecreaterequest/
---
## Classe ThreadMessageCreateRequest

Rappresenta una richiesta per creare un messaggio all'interno di un thread.

```csharp
public class ThreadMessageCreateRequest
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ThreadMessageCreateRequest](threadmessagecreaterequest/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Attachments](../../aspose.pdf.ai/threadmessagecreaterequest/attachments/) { get; set; } | Ottiene o imposta un elenco di file allegati al messaggio. |
| [Content](../../aspose.pdf.ai/threadmessagecreaterequest/content/) { get; set; } | Ottiene o imposta il contenuto del messaggio. Può essere una stringa o un array di parti di contenuto. |
| [Metadata](../../aspose.pdf.ai/threadmessagecreaterequest/metadata/) { get; set; } | Ottiene o imposta un insieme di 16 coppie chiave-valore che possono essere collegate a un oggetto. Questo può essere utile per memorizzare informazioni aggiuntive sull'oggetto in un formato strutturato. Le chiavi possono avere una lunghezza massima di 64 caratteri e i valori possono avere una lunghezza massima di 512 caratteri. |
| [Role](../../aspose.pdf.ai/threadmessagecreaterequest/role/) { get; set; } | Ottiene o imposta il ruolo dell'entità che crea il messaggio. I valori consentiti includono: "user", "assistant". |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromAssistant](../../aspose.pdf.ai/threadmessagecreaterequest/fromassistant/)() | Crea una nuova `ThreadMessageCreateRequest` con il ruolo impostato su Assistant. |
| static [FromUser](../../aspose.pdf.ai/threadmessagecreaterequest/fromuser/)() | Crea una nuova `ThreadMessageCreateRequest` con il ruolo impostato su User. |
| [WithAttachments](../../aspose.pdf.ai/threadmessagecreaterequest/withattachments/)(List&lt;Attachment&gt;) | Imposta gli allegati per la richiesta di messaggio del thread. |
| [WithContent](../../aspose.pdf.ai/threadmessagecreaterequest/withcontent/)(MessageContentRequest) | Aggiunge un contenuto di messaggio alla richiesta di messaggio del thread. |
| [WithContents](../../aspose.pdf.ai/threadmessagecreaterequest/withcontents/)(List&lt;MessageContentRequest&gt;) | Imposta i contenuti del messaggio per la richiesta di messaggio del thread. |
| [WithMetadata](../../aspose.pdf.ai/threadmessagecreaterequest/withmetadata/)(Dictionary&lt;string, string&gt;) | Imposta i metadati per la richiesta di messaggio del thread. |

### Vedi Anche

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)