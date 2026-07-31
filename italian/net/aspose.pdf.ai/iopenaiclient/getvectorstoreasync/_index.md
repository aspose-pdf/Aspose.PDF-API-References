---
title: "IOpenAIClient.GetVectorStoreAsync"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo IOpenAIClient. Recupera i dettagli di un archivio vettoriale specifico in modo asincrono"
type: docs
weight: 300
url: /it/net/aspose.pdf.ai/iopenaiclient/getvectorstoreasync/
---
## IOpenAIClient.GetVectorStoreAsync method

Recupera i dettagli di un archivio vettoriale specifico in modo asincrono.

```csharp
public Task<VectorStoreResponse> GetVectorStoreAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vectorStoreId | String | L'ID del vector store da recuperare. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene i dettagli del vector store.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Generata quando l'ID del vector store è nullo o vuoto. |

### Vedi anche

* class [VectorStoreResponse](../../vectorstoreresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


