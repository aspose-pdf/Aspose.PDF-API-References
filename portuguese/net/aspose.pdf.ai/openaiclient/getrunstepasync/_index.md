---
title: OpenAIClient.GetRunStepAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Recupera detalhes de um passo específico dentro de uma execução de forma assíncrona
type: docs
weight: 270
url: /pt/net/aspose.pdf.ai/openaiclient/getrunstepasync/
---
## Método OpenAIClient.GetRunStepAsync

Recupera detalhes de um passo específico dentro de uma execução de forma assíncrona.

```csharp
public Task<RunStepResponse> GetRunStepAsync(string threadId, string runId, string runStepId, 
    CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| threadId | String | O ID do thread contendo a execução. |
| runId | String | O ID da execução contendo o passo. |
| runStepId | String | O ID do passo da execução a ser recuperado. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém os detalhes do passo da execução.

### Exceções

| exceção | condição |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lançada quando o Id do thread é nulo ou vazio. |
| [AIClientException](../../aiclientexception/) | Lançada quando o Id da execução é nulo ou vazio. |
| [AIClientException](../../aiclientexception/) | Lançada quando o Id do passo da execução é nulo ou vazio. |

### Veja Também

* classe [RunStepResponse](../../runstepresponse/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)