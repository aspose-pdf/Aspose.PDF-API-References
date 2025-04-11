---
title: OpenAIClient.CreateRunAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Cria uma execução dentro de um thread especificado de forma assíncrona
type: docs
weight: 50
url: /pt/net/aspose.pdf.ai/openaiclient/createrunasync/
---
## Método OpenAIClient.CreateRunAsync

Cria uma execução dentro de um thread especificado de forma assíncrona.

```csharp
public Task<RunResponse> CreateRunAsync(string threadId, RunCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| threadId | String | O ID do thread onde a execução será criada. |
| runCreateRequest | RunCreateRequest | Os detalhes da solicitação para criar a execução. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém a resposta da criação da execução.

### Exceções

| exceção | condição |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID do thread é nulo ou vazio. |

### Veja Também

* classe [RunResponse](../../runresponse/)
* classe [RunCreateRequest](../../runcreaterequest/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)