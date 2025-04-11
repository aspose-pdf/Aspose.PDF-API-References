---
title: OpenAIClient.DeleteThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Exclui uma mensagem dentro de um thread de forma assíncrona
type: docs
weight: 160
url: /pt/net/aspose.pdf.ai/openaiclient/deletethreadmessageasync/
---
## Método OpenAIClient.DeleteThreadMessageAsync

Exclui uma mensagem dentro de um thread de forma assíncrona.

```csharp
public Task<DeleteStatusResponse> DeleteThreadMessageAsync(string threadId, string threadMessageId, 
    CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| threadId | String | O ID do thread que contém a mensagem a ser excluída. |
| threadMessageId | String | O ID da mensagem a ser excluída. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém o status da operação de exclusão.

### Exceções

| exceção | condição |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID do thread é nulo ou vazio. |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID da mensagem do thread é nulo ou vazio. |

### Veja Também

* classe [DeleteStatusResponse](../../deletestatusresponse/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)