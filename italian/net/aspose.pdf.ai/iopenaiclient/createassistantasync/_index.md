---
title: IOpenAIClient.CreateAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo IOpenAIClient. Crea un nuovo assistente in modo asincrono
type: docs
weight: 30
url: /it/net/aspose.pdf.ai/iopenaiclient/createassistantasync/
---
## Metodo IOpenAIClient.CreateAssistantAsync

Crea un nuovo assistente in modo asincrono.

```csharp
public Task<AssistantResponse> CreateAssistantAsync(AssistantCreateRequest assistantCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| assistantCreateRequest | AssistantCreateRequest | L'oggetto di richiesta contenente i dettagli per creare l'assistente. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di Ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene la risposta dalla creazione dell'assistente.

### Vedi Anche

* classe [AssistantResponse](../../assistantresponse/)
* classe [AssistantCreateRequest](../../assistantcreaterequest/)
* interfaccia [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)