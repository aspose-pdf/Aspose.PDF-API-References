---
title: "OpenAIClient.GetVectorStoreAsync"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo OpenAIClient. Recupera i dettagli di un vector store specifico in modo asincrono"
type: docs
weight: 340
url: /it/net/aspose.pdf.ai/openaiclient/getvectorstoreasync/
---
## OpenAIClient.GetVectorStoreAsync method

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
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


