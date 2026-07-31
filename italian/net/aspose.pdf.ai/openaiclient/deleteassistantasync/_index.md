---
title: "OpenAIClient.DeleteAssistantAsync"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo OpenAIClient. Elimina un assistente esistente in modo asincrono."
type: docs
weight: 130
url: /it/net/aspose.pdf.ai/openaiclient/deleteassistantasync/
---
## OpenAIClient.DeleteAssistantAsync method

Elimina un assistente esistente in modo asincrono.

```csharp
public Task<DeleteStatusResponse> DeleteAssistantAsync(string assistantId, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| assistantId | String | L'ID dell'assistente da eliminare. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene lo stato dell'operazione di eliminazione.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Generato quando l'ID dell'assistente è null o vuoto. |

### Vedi anche

* class [DeleteStatusResponse](../../deletestatusresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


