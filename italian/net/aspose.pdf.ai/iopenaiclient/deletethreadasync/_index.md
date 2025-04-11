---
title: IOpenAIClient.DeleteThreadAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo IOpenAIClient. Elimina un thread esistente in modo asincrono
type: docs
weight: 150
url: /it/net/aspose.pdf.ai/iopenaiclient/deletethreadasync/
---
## Metodo IOpenAIClient.DeleteThreadAsync

Elimina un thread esistente in modo asincrono.

```csharp
public Task<DeleteStatusResponse> DeleteThreadAsync(string threadId, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threadId | String | L'ID del thread da eliminare. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di Ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene lo stato dell'operazione di eliminazione.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID del thread è nullo o vuoto. |

### Vedi Anche

* classe [DeleteStatusResponse](../../deletestatusresponse/)
* interfaccia [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)