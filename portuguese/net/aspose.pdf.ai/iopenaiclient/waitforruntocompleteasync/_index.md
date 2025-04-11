---
title: IOpenAIClient.WaitForRunToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Aguarda a conclusão de uma execução dentro de uma thread de forma assíncrona
type: docs
weight: 440
url: /pt/net/aspose.pdf.ai/iopenaiclient/waitforruntocompleteasync/
---
## Método IOpenAIClient.WaitForRunToCompleteAsync

Aguarda a conclusão de uma execução dentro de uma thread de forma assíncrona.

```csharp
public Task<RunResponse> WaitForRunToCompleteAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| threadId | String | O ID da thread contendo a execução. |
| runId | String | O ID da execução a ser monitorada até a conclusão. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém o status final da execução.

### Exceções

| exceção | condição |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID da thread é nulo ou vazio. |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID da execução é nulo ou vazio. |

### Veja Também

* classe [RunResponse](../../runresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)