---
title: OpenAIClient.DeleteVectorStoreFileAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo OpenAIClient. Elimina un file all'interno di uno store vettoriale in modo asincrono
type: docs
weight: 180
url: /it/net/aspose.pdf.ai/openaiclient/deletevectorstorefileasync/
---
## Metodo OpenAIClient.DeleteVectorStoreFileAsync

Elimina un file all'interno di uno store vettoriale in modo asincrono.

```csharp
public Task<DeleteStatusResponse> DeleteVectorStoreFileAsync(string vectorStoreId, string fileId, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vectorStoreId | String | L'ID dello store vettoriale contenente il file da eliminare. |
| fileId | String | L'ID del file da eliminare. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene lo stato dell'operazione di eliminazione.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID dello store vettoriale è nullo o vuoto. |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID del file è nullo o vuoto. |

### Vedi anche

* classe [DeleteStatusResponse](../../deletestatusresponse/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)