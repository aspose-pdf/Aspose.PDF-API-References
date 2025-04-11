---
title: IOpenAIClient.CreateThreadAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo IOpenAIClient. Crea un nuovo thread in modo asincrono
type: docs
weight: 70
url: /it/net/aspose.pdf.ai/iopenaiclient/createthreadasync/
---
## Metodo IOpenAIClient.CreateThreadAsync

Crea un nuovo thread in modo asincrono.

```csharp
public Task<ThreadResponse> CreateThreadAsync(ThreadCreateRequest threadCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threadCreateRequest | ThreadCreateRequest | L'oggetto di richiesta contenente i dettagli per la creazione del thread. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene la risposta dalla creazione del thread.

### Vedi anche

* classe [ThreadResponse](../../threadresponse/)
* classe [ThreadCreateRequest](../../threadcreaterequest/)
* interfaccia [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)