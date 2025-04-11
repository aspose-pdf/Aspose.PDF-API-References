---
title: ILlamaClient.CreateCompletionAsync
second_title: Aspose.PDF for .NET API Reference
description: Método ILlamaClient. Cria uma solicitação de conclusão de chat no serviço Llama
type: docs
weight: 10
url: /pt/net/aspose.pdf.ai/illamaclient/createcompletionasync/
---
## Método ILlamaClient.CreateCompletionAsync

Cria uma solicitação de conclusão de chat no serviço Llama.

```csharp
public Task<LlamaChatCompletionResponse> CreateCompletionAsync(
    LlamaChatCompletionRequest chatCompletionRequest, 
    CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chatCompletionRequest | LlamaChatCompletionRequest | A solicitação de conclusão de chat. |
| cancellationToken | Nullable`1 | O token de cancelamento. |

### Valor de Retorno

A resposta de conclusão de chat.

### Veja Também

* classe [LlamaChatCompletionResponse](../../llamachatcompletionresponse/)
* classe [LlamaChatCompletionRequest](../../llamachatcompletionrequest/)
* interface [ILlamaClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)