---
title: OpenAIClient.GetAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Recupera detalhes de um assistente específico de forma assíncrona
type: docs
weight: 190
url: /pt/net/aspose.pdf.ai/openaiclient/getassistantasync/
---
## Método OpenAIClient.GetAssistantAsync

Recupera detalhes de um assistente específico de forma assíncrona.

```csharp
public Task<AssistantResponse> GetAssistantAsync(string assistantId, 
    CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| assistantId | String | O ID do assistente a ser recuperado. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém os detalhes do assistente.

### Exceções

| exceção | condição |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID do assistente é nulo ou vazio. |

### Veja Também

* classe [AssistantResponse](../../assistantresponse/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)