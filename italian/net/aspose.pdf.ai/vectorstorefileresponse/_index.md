---
title: Class VectorStoreFileResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.VectorStoreFileResponse classe. Un archivio vettoriale file risposta.
type: docs
weight: 1350
url: /it/net/aspose.pdf.ai/vectorstorefileresponse/
---
## Classe VectorStoreFileResponse

Una risposta del file del negozio vettoriale.

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
| [CreatedAt](../../aspose.pdf.ai/vectorstorefileresponse/createdat/) { get; set; } | Ottiene o imposta il timestamp Unix (in secondi) per quando è stato creato il file del negozio vettoriale. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Ottiene o imposta i dettagli della risposta. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Ottiene o imposta l'errore della risposta HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Ottiene o imposta le informazioni sull'errore. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Ottiene o imposta le intestazioni della risposta HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Ottiene o imposta il codice di stato HTTP. |
| [Id](../../aspose.pdf.ai/vectorstorefileresponse/id/) { get; set; } | Ottiene o imposta l'identificatore, che può essere referenziato negli endpoint API. /// |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indica se la risposta è stata positiva. |
| [LastError](../../aspose.pdf.ai/vectorstorefileresponse/lasterror/) { get; set; } | Ottiene o imposta l'ultimo errore associato a questo file del negozio vettoriale. Sarà nullo se non ci sono errori. |
| [Object](../../aspose.pdf.ai/vectorstorefileresponse/object/) { get; set; } | Ottiene o imposta il tipo di oggetto, che è sempre vector_store.file. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Ottiene la frase di motivo dell'errore. |
| [Status](../../aspose.pdf.ai/vectorstorefileresponse/status/) { get; set; } | Ottiene o imposta lo stato del file del negozio vettoriale, che può essere in_progress, completed, cancelled o failed. Lo stato completed indica che il file del negozio vettoriale è pronto per l'uso. |
| [UsageBytes](../../aspose.pdf.ai/vectorstorefileresponse/usagebytes/) { get; set; } | Ottiene o imposta l'uso totale del negozio vettoriale in byte. Nota che questo potrebbe essere diverso dalla dimensione originale del file. |
| [VectorStoreId](../../aspose.pdf.ai/vectorstorefileresponse/vectorstoreid/) { get; set; } | Ottiene o imposta l'ID del negozio vettoriale a cui è allegato il file. |

### Vedi Anche

* classe [BaseResponse](../baseresponse/)
* interfaccia [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)