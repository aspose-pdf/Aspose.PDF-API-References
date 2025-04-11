---
title: IOpenAIClient.WaitForThreadMessageToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Aguarda a conclusão de uma mensagem de thread específica de forma assíncrona
type: docs
weight: 450
url: /pt/net/aspose.pdf.ai/iopenaiclient/waitforthreadmessagetocompleteasync/
---
## Método IOpenAIClient.WaitForThreadMessageToCompleteAsync

Aguarda a conclusão de uma mensagem de thread específica de forma assíncrona.

```csharp
public Task<ThreadMessageResponse> WaitForThreadMessageToCompleteAsync(string threadId, 
    string threadMessageId, CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| threadId | String | O ID da thread que contém a mensagem. |
| threadMessageId | String | O ID da mensagem a ser monitorada até a conclusão. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém o status final da mensagem.

### Exceções

| exceção | condição |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID da thread é nulo ou vazio. |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID da mensagem da thread é nulo ou vazio. |

### Veja Também

* classe [ThreadMessageResponse](../../threadmessageresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)