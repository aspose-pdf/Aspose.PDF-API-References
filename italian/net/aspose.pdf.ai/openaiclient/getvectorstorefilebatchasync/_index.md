---
title: OpenAIClient.GetVectorStoreFileBatchAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo OpenAIClient. Recupera i dettagli di un batch di file di archiviazione vettoriale specifico in modo asincrono
type: docs
weight: 350
url: /it/net/aspose.pdf.ai/openaiclient/getvectorstorefilebatchasync/
---
## Metodo OpenAIClient.GetVectorStoreFileBatchAsync

Recupera i dettagli di un batch di file di archiviazione vettoriale specifico in modo asincrono.

```csharp
public Task<VectorStoreFileBatchResponse> GetVectorStoreFileBatchAsync(string vectorStoreId, 
    string fileBatchId, CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vectorStoreId | String | L'ID dell'archivio vettoriale contenente il batch di file. |
| fileBatchId | String | L'ID del batch di file da recuperare. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di Ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene i dettagli del batch di file.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID dell'archivio vettoriale è nullo o vuoto. |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID del batch di file dell'archivio vettoriale è nullo o vuoto. |

### Vedi Anche

* classe [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)