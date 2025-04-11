---
title: OpenAIClient.GetThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Recupera detalhes de uma mensagem específica dentro de um thread de forma assíncrona
type: docs
weight: 310
url: /pt/net/aspose.pdf.ai/openaiclient/getthreadmessageasync/
---
## Método OpenAIClient.GetThreadMessageAsync

Recupera detalhes de uma mensagem específica dentro de um thread de forma assíncrona.

```csharp
public Task<ThreadMessageResponse> GetThreadMessageAsync(string threadId, string threadMessageId, 
    CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| threadId | String | O ID do thread contendo a mensagem. |
| threadMessageId | String | O ID da mensagem a ser recuperada. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém os detalhes da mensagem do thread.

### Exceções

| exceção | condição |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID do thread é nulo ou vazio. |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID da mensagem do thread é nulo ou vazio. |

### Veja Também

* classe [ThreadMessageResponse](../../threadmessageresponse/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)