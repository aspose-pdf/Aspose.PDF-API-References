---
title: IOpenAIClient.GetVectorStoreFileBatchAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo IOpenAIClient. Recupera i dettagli di un batch di file di store vettoriale specifico in modo asincrono
type: docs
weight: 320
url: /it/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchasync/
---
## Metodo IOpenAIClient.GetVectorStoreFileBatchAsync

Recupera i dettagli di un batch di file di store vettoriale specifico in modo asincrono.

```csharp
public Task<VectorStoreFileBatchResponse> GetVectorStoreFileBatchAsync(string vectorStoreId, 
    string fileBatchId, CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vectorStoreId | String | L'ID dello store vettoriale contenente il batch di file. |
| fileBatchId | String | L'ID del batch di file da recuperare. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene i dettagli del batch di file.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID dello store vettoriale è nullo o vuoto. |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID del batch di file dello store vettoriale è nullo o vuoto. |

### Vedi anche

* classe [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* interfaccia [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)