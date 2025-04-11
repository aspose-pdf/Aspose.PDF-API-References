---
title: OpenAIClient.GetThreadMessagesAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Recupera uma lista de mensagens para um thread específico de forma assíncrona
type: docs
weight: 320
url: /pt/net/aspose.pdf.ai/openaiclient/getthreadmessagesasync/
---
## Método OpenAIClient.GetThreadMessagesAsync

Recupera uma lista de mensagens para um thread específico de forma assíncrona.

```csharp
public Task<ThreadMessageListResponse> GetThreadMessagesAsync(string threadId, 
    ThreadMessageListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| threadId | String | O ID do thread para recuperar mensagens. |
| queryParameters | ThreadMessageListQueryParameters | Parâmetros de consulta opcionais para filtrar a lista de mensagens. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém uma lista de mensagens do thread.

### Exceções

| exceção | condição |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID do thread é nulo ou vazio. |

### Veja Também

* classe [ThreadMessageListResponse](../../threadmessagelistresponse/)
* classe [ThreadMessageListQueryParameters](../../threadmessagelistqueryparameters/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)