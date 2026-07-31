---
title: "IOpenAIClient.CreateCompletionAsync"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo IOpenAIClient. Crea un nuovo completamento in modo asincrono"
type: docs
weight: 40
url: /it/net/aspose.pdf.ai/iopenaiclient/createcompletionasync/
---
## IOpenAIClient.CreateCompletionAsync method

Crea un nuovo completamento in modo asincrono.

```csharp
public Task<CompletionResponse> CreateCompletionAsync(
    CompletionCreateRequest completionCreateRequest, CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| completionCreateRequest | CompletionCreateRequest | L'oggetto di richiesta contenente i dettagli per creare il completamento. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene la risposta dalla creazione del completamento.

### Vedi anche

* class [CompletionResponse](../../completionresponse/)
* class [CompletionCreateRequest](../../completioncreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


