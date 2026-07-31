---
title: "Classe ChatMessage"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.AI.ChatMessage. Un messaggio di completamento chat generato dal modello"
type: docs
weight: 190
url: /it/net/aspose.pdf.ai/chatmessage/
---
## ChatMessage class

Un messaggio di completamento della chat generato dal modello.

```csharp
public class ChatMessage
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ChatMessage](chatmessage/#constructor)() | Inizializza una nuova istanza della classe `ChatMessage`. |
| [ChatMessage](chatmessage/#constructor_1)(string, string) | Inizializza una nuova istanza della classe `ChatMessage`. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Content](../../aspose.pdf.ai/chatmessage/content/) { get; set; } | Ottiene o imposta il contenuto del messaggio. |
| [Name](../../aspose.pdf.ai/chatmessage/name/) { get; set; } | Ottiene o imposta un nome opzionale per il partecipante. Fornisce al modello informazioni per differenziare i partecipanti con lo stesso ruolo. |
| [Role](../../aspose.pdf.ai/chatmessage/role/) { get; set; } | Ottiene o imposta il ruolo dell'autore del messaggio. |
| [ToolCallId](../../aspose.pdf.ai/chatmessage/toolcallid/) { get; set; } | Ottiene o imposta la chiamata allo strumento a cui questo messaggio risponde. |
| [ToolCalls](../../aspose.pdf.ai/chatmessage/toolcalls/) { get; set; } | Ottiene o imposta le chiamate allo strumento generate dal modello, come le chiamate di funzione. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromAssistant](../../aspose.pdf.ai/chatmessage/fromassistant/)(string) | Crea un nuovo oggetto ChatMessage che rappresenta un messaggio dell'assistente. |
| static [FromSystem](../../aspose.pdf.ai/chatmessage/fromsystem/)(string) | Crea un nuovo oggetto ChatMessage che rappresenta un messaggio di sistema. |
| static [FromUser](../../aspose.pdf.ai/chatmessage/fromuser/)(string) | Crea un nuovo oggetto ChatMessage che rappresenta un messaggio dell'utente. |

### Vedi anche

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


