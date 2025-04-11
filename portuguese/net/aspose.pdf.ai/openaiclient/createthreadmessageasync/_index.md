---
title: OpenAIClient.CreateThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Cria uma nova mensagem dentro de um thread de forma assíncrona
type: docs
weight: 80
url: /pt/net/aspose.pdf.ai/openaiclient/createthreadmessageasync/
---
## Método OpenAIClient.CreateThreadMessageAsync

Cria uma nova mensagem dentro de um thread de forma assíncrona.

```csharp
public Task<ThreadMessageResponse> CreateThreadMessageAsync(string threadId, 
    ThreadMessageCreateRequest threadMessageRequest, CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| threadId | String | O ID do thread onde a mensagem será criada. |
| threadMessageRequest | ThreadMessageCreateRequest | Os detalhes da solicitação para criar a mensagem. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém a resposta da criação da mensagem.

### Exceções

| exceção | condição |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lançada quando o thread Id é nulo ou vazio. |

### Veja Também

* classe [ThreadMessageResponse](../../threadmessageresponse/)
* classe [ThreadMessageCreateRequest](../../threadmessagecreaterequest/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)