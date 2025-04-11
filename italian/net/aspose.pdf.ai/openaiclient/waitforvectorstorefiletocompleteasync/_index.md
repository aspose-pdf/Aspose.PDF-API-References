---
title: OpenAIClient.WaitForVectorStoreFileToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo OpenAIClient. Attende che un file specifico del vector store venga completato in modo asincrono
type: docs
weight: 490
url: /it/net/aspose.pdf.ai/openaiclient/waitforvectorstorefiletocompleteasync/
---
## Metodo OpenAIClient.WaitForVectorStoreFileToCompleteAsync

Attende che un file specifico del vector store venga completato in modo asincrono.

```csharp
public Task<VectorStoreFileResponse> WaitForVectorStoreFileToCompleteAsync(string vectorStoreId, 
    string fileId, CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vectorStoreId | String | L'ID del vector store contenente il file. |
| fileId | String | L'ID del file da monitorare fino al completamento. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di Ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene lo stato finale del file.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID del vector store è nullo o vuoto. |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID del file è nullo o vuoto. |

### Vedi Anche

* classe [VectorStoreFileResponse](../../vectorstorefileresponse/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)