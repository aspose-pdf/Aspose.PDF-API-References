---
title: IOpenAIClient.ModifyThreadAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Modifica um thread existente de forma assíncrona
type: docs
weight: 380
url: /pt/net/aspose.pdf.ai/iopenaiclient/modifythreadasync/
---
## Método IOpenAIClient.ModifyThreadAsync

Modifica um thread existente de forma assíncrona.

```csharp
public Task<ThreadResponse> ModifyThreadAsync(string threadId, 
    ThreadModifyRequest threadModifyRequest, CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| threadId | String | O ID do thread a ser modificado. |
| threadModifyRequest | ThreadModifyRequest | O objeto de solicitação contendo os detalhes da modificação. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém a resposta da modificação do thread.

### Exceções

| exceção | condição |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID do thread é nulo ou vazio. |

### Veja Também

* classe [ThreadResponse](../../threadresponse/)
* classe [ThreadModifyRequest](../../threadmodifyrequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)