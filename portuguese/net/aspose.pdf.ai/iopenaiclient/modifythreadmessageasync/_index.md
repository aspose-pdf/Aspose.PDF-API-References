---
title: IOpenAIClient.ModifyThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Modifica uma mensagem existente dentro de um thread de forma assíncrona
type: docs
weight: 390
url: /pt/net/aspose.pdf.ai/iopenaiclient/modifythreadmessageasync/
---
## Método IOpenAIClient.ModifyThreadMessageAsync

Modifica uma mensagem existente dentro de um thread de forma assíncrona.

```csharp
public Task<ThreadMessageResponse> ModifyThreadMessageAsync(string threadId, 
    string threadMessageId, ThreadMessageModifyRequest threadMessageModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| threadId | String | O ID do thread contendo a mensagem a ser modificada. |
| threadMessageId | String | O ID da mensagem a ser modificada. |
| threadMessageModifyRequest | ThreadMessageModifyRequest | Os detalhes da solicitação para modificar a mensagem. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém a resposta da modificação da mensagem.

### Exceções

| exceção | condição |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lançada quando o thread Id é nulo ou vazio. |
| [AIClientException](../../aiclientexception/) | Lançada quando o thread message Id é nulo ou vazio. |

### Veja Também

* classe [ThreadMessageResponse](../../threadmessageresponse/)
* classe [ThreadMessageModifyRequest](../../threadmessagemodifyrequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)