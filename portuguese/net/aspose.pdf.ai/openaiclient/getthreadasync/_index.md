---
title: OpenAIClient.GetThreadAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Recupera detalhes de um thread específico de forma assíncrona
type: docs
weight: 300
url: /pt/net/aspose.pdf.ai/openaiclient/getthreadasync/
---
## Método OpenAIClient.GetThreadAsync

Recupera detalhes de um thread específico de forma assíncrona.

```csharp
public Task<ThreadResponse> GetThreadAsync(string threadId, 
    CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| threadId | String | O ID do thread a ser recuperado. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém os detalhes do thread.

### Exceções

| exceção | condição |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID do thread é nulo ou vazio. |

### Veja Também

* classe [ThreadResponse](../../threadresponse/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)