---
title: "OpenAIClient.GetAssistantAsync"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo OpenAIClient. Recupera i dettagli di un assistente specifico in modo asincrono"
type: docs
weight: 190
url: /it/net/aspose.pdf.ai/openaiclient/getassistantasync/
---
## OpenAIClient.GetAssistantAsync method

Recupera i dettagli di un assistente specifico in modo asincrono.

```csharp
public Task<AssistantResponse> GetAssistantAsync(string assistantId, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| assistantId | String | L'ID dell'assistente da recuperare. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene i dettagli dell'assistente.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Generato quando l'ID dell'assistente è null o vuoto. |

### Vedi anche

* class [AssistantResponse](../../assistantresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


