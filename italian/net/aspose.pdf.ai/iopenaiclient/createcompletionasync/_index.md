---
title: IOpenAIClient.CreateCompletionAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo IOpenAIClient. Crea una nuova completamento in modo asincrono
type: docs
weight: 40
url: /it/net/aspose.pdf.ai/iopenaiclient/createcompletionasync/
---
## Metodo IOpenAIClient.CreateCompletionAsync

Crea una nuova completamento in modo asincrono.

```csharp
public Task<CompletionResponse> CreateCompletionAsync(
    CompletionCreateRequest completionCreateRequest, CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| completionCreateRequest | CompletionCreateRequest | L'oggetto di richiesta contenente i dettagli per creare la completamento. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di Ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene la risposta dalla creazione della completamento.

### Vedi Anche

* classe [CompletionResponse](../../completionresponse/)
* classe [CompletionCreateRequest](../../completioncreaterequest/)
* interfaccia [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)