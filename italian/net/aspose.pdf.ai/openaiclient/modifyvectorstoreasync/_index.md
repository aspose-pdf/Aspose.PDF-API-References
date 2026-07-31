---
title: "OpenAIClient.ModifyVectorStoreAsync"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo OpenAIClient. Modifica un vector store esistente in modo asincrono."
type: docs
weight: 440
url: /it/net/aspose.pdf.ai/openaiclient/modifyvectorstoreasync/
---
## OpenAIClient.ModifyVectorStoreAsync method

Modifica un archivio vettoriale esistente in modo asincrono.

```csharp
public Task<VectorStoreResponse> ModifyVectorStoreAsync(string vectorStoreId, 
    VectorStoreModifyRequest vectorStoreModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vectorStoreId | String | L'ID del vector store da modificare. |
| vectorStoreModifyRequest | VectorStoreModifyRequest | L'oggetto richiesta contenente i dettagli della modifica. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene la risposta dalla modifica del vector store.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Generata quando l'ID del vector store è nullo o vuoto. |

### Vedi anche

* class [VectorStoreResponse](../../vectorstoreresponse/)
* class [VectorStoreModifyRequest](../../vectorstoremodifyrequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


