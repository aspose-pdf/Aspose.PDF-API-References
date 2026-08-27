---
title: "Classe VectorStoreFileResponse"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.AI.VectorStoreFileResponse classe. Una risposta di file di vector store"
type: docs
weight: 1440
url: /it/net/aspose.pdf.ai/vectorstorefileresponse/
---
## VectorStoreFileResponse class

Una risposta di file dell'archivio vettoriale.

```csharp
public class VectorStoreFileResponse : BaseResponse, IStatus
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [VectorStoreFileResponse](vectorstorefileresponse/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/vectorstorefileresponse/createdat/) { get; set; } | Ottiene o imposta il timestamp Unix (in secondi) per quando il file di vector store è stato creato. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Ottiene o imposta il dettaglio della risposta. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Ottiene o imposta l'errore della risposta HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Ottiene o imposta le informazioni sull'errore. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Ottiene o imposta le intestazioni della risposta HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Ottiene o imposta il codice di stato HTTP. |
| [Id](../../aspose.pdf.ai/vectorstorefileresponse/id/) { get; set; } | Ottiene o imposta l'identificatore, che può essere referenziato negli endpoint API. /// |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indica se la risposta ha avuto successo. |
| [LastError](../../aspose.pdf.ai/vectorstorefileresponse/lasterror/) { get; set; } | Ottiene o imposta l'ultimo errore associato a questo file di vector store. Sarà null se non ci sono errori. |
| [Object](../../aspose.pdf.ai/vectorstorefileresponse/object/) { get; set; } | Ottiene o imposta il tipo di oggetto, che è sempre vector_store.file. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Ottiene la frase di motivo dell'errore. |
| [Status](../../aspose.pdf.ai/vectorstorefileresponse/status/) { get; set; } | Ottiene o imposta lo stato del file di vector store, che può essere in_progress, completed, cancelled o failed. Lo stato completed indica che il file di vector store è pronto per l'uso. |
| [UsageBytes](../../aspose.pdf.ai/vectorstorefileresponse/usagebytes/) { get; set; } | Ottiene o imposta l'utilizzo totale del vector store in byte. Nota che questo può differire dalla dimensione originale del file. |
| [VectorStoreId](../../aspose.pdf.ai/vectorstorefileresponse/vectorstoreid/) { get; set; } | Ottiene o imposta l'ID del vector store a cui è allegato il File. |

### Vedi anche

* class [BaseResponse](../baseresponse/)
* interface [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


