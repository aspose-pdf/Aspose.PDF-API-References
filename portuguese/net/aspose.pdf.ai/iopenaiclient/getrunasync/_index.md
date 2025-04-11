---
title: IOpenAIClient.GetRunAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Recupera detalhes de uma execução específica dentro de um thread de forma assíncrona
type: docs
weight: 230
url: /pt/net/aspose.pdf.ai/iopenaiclient/getrunasync/
---
## Método IOpenAIClient.GetRunAsync

Recupera detalhes de uma execução específica dentro de um thread de forma assíncrona.

```csharp
public Task<RunResponse> GetRunAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| threadId | String | O ID do thread contendo a execução. |
| runId | String | O ID da execução a ser recuperada. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém os detalhes da execução.

### Exceções

| exceção | condição |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lançada quando o Id do thread é nulo ou vazio. |
| [AIClientException](../../aiclientexception/) | Lançada quando o Id da execução é nulo ou vazio. |

### Veja Também

* classe [RunResponse](../../runresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)