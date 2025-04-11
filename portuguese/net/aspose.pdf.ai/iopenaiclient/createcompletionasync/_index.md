---
title: IOpenAIClient.CreateCompletionAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Cria uma nova conclusão de forma assíncrona
type: docs
weight: 40
url: /pt/net/aspose.pdf.ai/iopenaiclient/createcompletionasync/
---
## Método IOpenAIClient.CreateCompletionAsync

Cria uma nova conclusão de forma assíncrona.

```csharp
public Task<CompletionResponse> CreateCompletionAsync(
    CompletionCreateRequest completionCreateRequest, CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| completionCreateRequest | CompletionCreateRequest | O objeto de solicitação contendo detalhes para criar a conclusão. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém a resposta da criação da conclusão.

### Veja Também

* classe [CompletionResponse](../../completionresponse/)
* classe [CompletionCreateRequest](../../completioncreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)