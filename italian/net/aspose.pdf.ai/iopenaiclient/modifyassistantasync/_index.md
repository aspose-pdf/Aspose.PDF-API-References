---
title: IOpenAIClient.ModifyAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo IOpenAIClient. Modifica un assistente esistente in modo asincrono
type: docs
weight: 360
url: /it/net/aspose.pdf.ai/iopenaiclient/modifyassistantasync/
---
## Metodo IOpenAIClient.ModifyAssistantAsync

Modifica un assistente esistente in modo asincrono.

```csharp
public Task<AssistantResponse> ModifyAssistantAsync(string assistantId, 
    AssistantModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| assistantId | String | L'ID dell'assistente da modificare. |
| assistantModifyRequest | AssistantModifyRequest | L'oggetto di richiesta contenente i dettagli della modifica. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di Ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene la risposta dalla modifica dell'assistente.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Sollevata quando l'ID dell'assistente è nullo o vuoto. |

### Vedi Anche

* classe [AssistantResponse](../../assistantresponse/)
* classe [AssistantModifyRequest](../../assistantmodifyrequest/)
* interfaccia [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)