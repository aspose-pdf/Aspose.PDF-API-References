---
title: IOpenAIClient.ModifyRunAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Modifica uma execução existente dentro de um thread de forma assíncrona
type: docs
weight: 370
url: /pt/net/aspose.pdf.ai/iopenaiclient/modifyrunasync/
---
## Método IOpenAIClient.ModifyRunAsync

Modifica uma execução existente dentro de um thread de forma assíncrona.

```csharp
public Task<RunResponse> ModifyRunAsync(string threadId, string runId, 
    RunModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| threadId | String | O ID do thread contendo a execução. |
| runId | String | O ID da execução a ser modificada. |
| assistantModifyRequest | RunModifyRequest | Os detalhes da solicitação para modificar a execução. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém a resposta da modificação da execução.

### Exceções

| exceção | condição |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID do thread é nulo ou vazio. |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID da execução é nulo ou vazio. |

### Veja Também

* classe [RunResponse](../../runresponse/)
* classe [RunModifyRequest](../../runmodifyrequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)