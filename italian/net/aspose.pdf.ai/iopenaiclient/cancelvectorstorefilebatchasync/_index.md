---
title: IOpenAIClient.CancelVectorStoreFileBatchAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo IOpenAIClient. Annulla un batch di file di archiviazione vettoriale specifico in modo asincrono
type: docs
weight: 20
url: /it/net/aspose.pdf.ai/iopenaiclient/cancelvectorstorefilebatchasync/
---
## Metodo IOpenAIClient.CancelVectorStoreFileBatchAsync

Annulla un batch di file di archiviazione vettoriale specifico in modo asincrono.

```csharp
public Task<VectorStoreFileBatchResponse> CancelVectorStoreFileBatchAsync(string vectorStoreId, 
    string fileBatchId, CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vectorStoreId | String | L'ID dell'archivio vettoriale contenente il batch di file da annullare. |
| fileBatchId | String | L'ID del batch di file da annullare. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene la risposta dall'annullamento del batch di file.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID dell'archivio vettoriale è nullo o vuoto. |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID del batch di file dell'archivio vettoriale è nullo o vuoto. |

### Vedi anche

* classe [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* interfaccia [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)