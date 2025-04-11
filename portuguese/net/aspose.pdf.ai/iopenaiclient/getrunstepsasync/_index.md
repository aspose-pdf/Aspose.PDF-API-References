---
title: IOpenAIClient.GetRunStepsAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Recupera uma lista de etapas para uma execução específica dentro de um thread de forma assíncrona
type: docs
weight: 260
url: /pt/net/aspose.pdf.ai/iopenaiclient/getrunstepsasync/
---
## Método IOpenAIClient.GetRunStepsAsync

Recupera uma lista de etapas para uma execução específica dentro de um thread de forma assíncrona.

```csharp
public Task<RunStepListResponse> GetRunStepsAsync(string threadId, string runId, 
    RunStepListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| threadId | String | O ID do thread que contém a execução. |
| runId | String | O ID da execução para recuperar etapas. |
| queryParameters | RunStepListQueryParameters | Parâmetros de consulta opcionais para filtrar a lista de etapas da execução. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém a lista de etapas da execução.

### Exceções

| exceção | condição |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID do thread é nulo ou vazio. |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID da execução é nulo ou vazio. |

### Veja Também

* classe [RunStepListResponse](../../runsteplistresponse/)
* classe [RunStepListQueryParameters](../../runsteplistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)