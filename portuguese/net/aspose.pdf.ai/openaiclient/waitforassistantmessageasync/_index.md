---
title: OpenAIClient.WaitForAssistantMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Aguarda a primeira mensagem do assistente dentro de um thread de forma assíncrona
type: docs
weight: 460
url: /pt/net/aspose.pdf.ai/openaiclient/waitforassistantmessageasync/
---
## Método OpenAIClient.WaitForAssistantMessageAsync

Aguarda a primeira mensagem do assistente dentro de um thread de forma assíncrona.

```csharp
public Task<ThreadMessageResponse> WaitForAssistantMessageAsync(string threadId, 
    ThreadMessageListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| threadId | String | O ID do thread a ser monitorado para a primeira mensagem do assistente. |
| queryParameters | ThreadMessageListQueryParameters | Parâmetros de consulta opcionais para filtrar a lista de mensagens. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém a primeira mensagem do assistente no thread.

### Exceções

| exceção | condição |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID do thread é nulo ou vazio. |

### Veja Também

* classe [ThreadMessageResponse](../../threadmessageresponse/)
* classe [ThreadMessageListQueryParameters](../../threadmessagelistqueryparameters/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)