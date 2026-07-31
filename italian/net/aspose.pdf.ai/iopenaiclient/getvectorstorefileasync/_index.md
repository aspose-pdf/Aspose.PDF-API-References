---
title: "IOpenAIClient.GetVectorStoreFileAsync"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo IOpenAIClient. Recupera i dettagli di un file specifico all'interno di un vector store in modo asincrono"
type: docs
weight: 310
url: /it/net/aspose.pdf.ai/iopenaiclient/getvectorstorefileasync/
---
## IOpenAIClient.GetVectorStoreFileAsync method

Recupera i dettagli di un file specifico all'interno di un archivio vettoriale in modo asincrono.

```csharp
public Task<VectorStoreFileResponse> GetVectorStoreFileAsync(string vectorStoreId, string fileId, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vectorStoreId | String | L'ID del vector store che contiene il file. |
| fileId | String | L'ID del file da recuperare. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene i dettagli del file.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Generata quando l'ID del vector store è nullo o vuoto. |
| [AIClientException](../../aiclientexception/) | Generato quando l'ID del file è nullo o vuoto. |

### Vedi anche

* class [VectorStoreFileResponse](../../vectorstorefileresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


