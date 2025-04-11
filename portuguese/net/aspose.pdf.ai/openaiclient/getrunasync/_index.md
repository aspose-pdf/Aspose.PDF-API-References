---
title: OpenAIClient.GetRunAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Recupera detalhes de uma execução específica dentro de um thread de forma assíncrona
type: docs
weight: 250
url: /pt/net/aspose.pdf.ai/openaiclient/getrunasync/
---
## Método OpenAIClient.GetRunAsync

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
| [AIClientException](../../aiclientexception/) | Lançada quando o thread Id é nulo ou vazio. |
| [AIClientException](../../aiclientexception/) | Lançada quando o run Id é nulo ou vazio. |

### Veja Também

* classe [RunResponse](../../runresponse/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)