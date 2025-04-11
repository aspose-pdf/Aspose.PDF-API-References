---
title: OpenAIClient.DeleteFileAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo OpenAIClient. Elimina un file specifico in modo asincrono
type: docs
weight: 140
url: /it/net/aspose.pdf.ai/openaiclient/deletefileasync/
---
## Metodo OpenAIClient.DeleteFileAsync

Elimina un file specifico in modo asincrono.

```csharp
public Task<DeleteStatusResponse> DeleteFileAsync(string fileId, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileId | String | L'ID del file da eliminare. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di Ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene lo stato dell'operazione di eliminazione.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID del file è nullo o vuoto. |

### Vedi Anche

* classe [DeleteStatusResponse](../../deletestatusresponse/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)