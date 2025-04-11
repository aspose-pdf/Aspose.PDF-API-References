---
title: IOpenAIClient.DeleteAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo IOpenAIClient. Elimina un assistente esistente in modo asincrono
type: docs
weight: 130
url: /it/net/aspose.pdf.ai/iopenaiclient/deleteassistantasync/
---
## Metodo IOpenAIClient.DeleteAssistantAsync

Elimina un assistente esistente in modo asincrono.

```csharp
public Task<DeleteStatusResponse> DeleteAssistantAsync(string assistantId, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| assistantId | String | L'ID dell'assistente da eliminare. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di Ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene lo stato dell'operazione di eliminazione.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID dell'assistente è nullo o vuoto. |

### Vedi Anche

* classe [DeleteStatusResponse](../../deletestatusresponse/)
* interfaccia [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)