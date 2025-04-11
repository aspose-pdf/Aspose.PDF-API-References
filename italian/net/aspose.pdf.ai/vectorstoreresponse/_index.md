---
title: Class VectorStoreResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.VectorStoreResponse classe. L'archivio vettoriale oggetto.
type: docs
weight: 1390
url: /it/net/aspose.pdf.ai/vectorstoreresponse/
---
## Classe VectorStoreResponse

L'oggetto del negozio vettoriale.

```csharp
public class VectorStoreResponse : BaseResponse, IEntityId, IStatus
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [VectorStoreResponse](vectorstoreresponse/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/vectorstoreresponse/createdat/) { get; set; } | Ottiene o imposta il timestamp Unix (in secondi) per quando è stato creato il negozio vettoriale. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Ottiene o imposta i dettagli della risposta. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Ottiene o imposta l'errore della risposta HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Ottiene o imposta le informazioni sull'errore. |
| [ExpiresAfter](../../aspose.pdf.ai/vectorstoreresponse/expiresafter/) { get; set; } | Ottiene o imposta la politica di scadenza per un negozio vettoriale. |
| [ExpiresAt](../../aspose.pdf.ai/vectorstoreresponse/expiresat/) { get; set; } | Ottiene o imposta il timestamp Unix (in secondi) per quando il negozio vettoriale scadrà. |
| [FileCounts](../../aspose.pdf.ai/vectorstoreresponse/filecounts/) { get; set; } | Ottiene o imposta il numero di file che sono stati elaborati. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Ottiene o imposta le intestazioni della risposta HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Ottiene o imposta il codice di stato HTTP. |
| [Id](../../aspose.pdf.ai/vectorstoreresponse/id/) { get; set; } | Ottiene o imposta l'identificatore, che può essere referenziato negli endpoint API. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indica se la risposta è stata positiva. |
| [LastActiveAt](../../aspose.pdf.ai/vectorstoreresponse/lastactiveat/) { get; set; } | Ottiene o imposta il timestamp Unix (in secondi) per quando il negozio vettoriale è stato attivo per l'ultima volta. |
| [Metadata](../../aspose.pdf.ai/vectorstoreresponse/metadata/) { get; set; } | Ottiene o imposta un insieme di 16 coppie chiave-valore che possono essere collegate a un oggetto. Questo può essere utile per memorizzare informazioni aggiuntive sull'oggetto in un formato strutturato. Le chiavi possono avere un massimo di 64 caratteri e i valori possono avere un massimo di 512 caratteri. |
| [Name](../../aspose.pdf.ai/vectorstoreresponse/name/) { get; set; } | Ottiene o imposta il nome del negozio vettoriale. |
| [Object](../../aspose.pdf.ai/vectorstoreresponse/object/) { get; set; } | Ottiene o imposta il tipo di oggetto, che è sempre vector_store. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Ottiene la frase di motivo dell'errore. |
| [Status](../../aspose.pdf.ai/vectorstoreresponse/status/) { get; set; } | Ottiene o imposta lo stato del negozio vettoriale, che può essere scaduto, in_corso o completato. Uno stato di completato indica che il negozio vettoriale è pronto per l'uso. |
| [UsageBytes](../../aspose.pdf.ai/vectorstoreresponse/usagebytes/) { get; set; } | Ottiene o imposta il numero totale di byte utilizzati dai file nel negozio vettoriale. |

### Vedi Anche

* classe [BaseResponse](../baseresponse/)
* interfaccia [IEntityId](../ientityid/)
* interfaccia [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)