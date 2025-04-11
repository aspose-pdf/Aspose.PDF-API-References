---
title: OpenAIClient.GetRunsAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Recupera uma lista de execuções para um thread especificado de forma assíncrona
type: docs
weight: 260
url: /pt/net/aspose.pdf.ai/openaiclient/getrunsasync/
---
## Método OpenAIClient.GetRunsAsync

Recupera uma lista de execuções para um thread especificado de forma assíncrona.

```csharp
public Task<RunListResponse> GetRunsAsync(string threadId, 
    RunListQueryParameters queryParameters = null, CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| threadId | String | O ID do thread para recuperar execuções. |
| queryParameters | RunListQueryParameters | Parâmetros de consulta opcionais para filtrar a lista de execuções. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém uma lista de execuções.

### Exceções

| exceção | condição |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID do thread é nulo ou vazio. |

### Veja Também

* classe [RunListResponse](../../runlistresponse/)
* classe [RunListQueryParameters](../../runlistqueryparameters/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)