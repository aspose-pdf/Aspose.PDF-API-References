---
title: "IOpenAIClient.DeleteVectorStoreFileAsync"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "IOpenAIClient metodo. Elimina un file all'interno di un archivio vettoriale in modo asincrono"
type: docs
weight: 180
url: /it/net/aspose.pdf.ai/iopenaiclient/deletevectorstorefileasync/
---
## IOpenAIClient.DeleteVectorStoreFileAsync method

Elimina un file all'interno di un archivio vettoriale in modo asincrono.

```csharp
public Task<DeleteStatusResponse> DeleteVectorStoreFileAsync(string vectorStoreId, string fileId, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vectorStoreId | String | L'ID dell'archivio vettoriale che contiene il file da eliminare. |
| fileId | String | L'ID del file da eliminare. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene lo stato dell'operazione di eliminazione.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Generata quando l'ID del vector store è nullo o vuoto. |
| [AIClientException](../../aiclientexception/) | Generato quando l'ID del file è nullo o vuoto. |

### Vedi anche

* class [DeleteStatusResponse](../../deletestatusresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


