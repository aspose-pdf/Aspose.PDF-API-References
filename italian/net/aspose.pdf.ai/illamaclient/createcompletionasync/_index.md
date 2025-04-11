---
title: ILlamaClient.CreateCompletionAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo ILlamaClient. Crea una richiesta di completamento chat nel servizio Llama
type: docs
weight: 10
url: /it/net/aspose.pdf.ai/illamaclient/createcompletionasync/
---
## Metodo ILlamaClient.CreateCompletionAsync

Crea una richiesta di completamento chat nel servizio Llama.

```csharp
public Task<LlamaChatCompletionResponse> CreateCompletionAsync(
    LlamaChatCompletionRequest chatCompletionRequest, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chatCompletionRequest | LlamaChatCompletionRequest | La richiesta di completamento chat. |
| cancellationToken | Nullable`1 | Il token di cancellazione. |

### Valore di ritorno

La risposta di completamento chat.

### Vedi anche

* classe [LlamaChatCompletionResponse](../../llamachatcompletionresponse/)
* classe [LlamaChatCompletionRequest](../../llamachatcompletionrequest/)
* interfaccia [ILlamaClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)