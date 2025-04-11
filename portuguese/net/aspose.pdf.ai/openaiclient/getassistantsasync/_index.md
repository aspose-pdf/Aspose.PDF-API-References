---
title: OpenAIClient.GetAssistantsAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Recupera uma lista de assistentes de forma assíncrona
type: docs
weight: 200
url: /pt/net/aspose.pdf.ai/openaiclient/getassistantsasync/
---
## Método OpenAIClient.GetAssistantsAsync

Recupera uma lista de assistentes de forma assíncrona.

```csharp
public Task<AssistantListResponse> GetAssistantsAsync(
    AssistantListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| queryParameters | AssistantListQueryParameters | Parâmetros de consulta opcionais para filtrar a lista de assistentes. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém a lista de assistentes.

### Veja Também

* classe [AssistantListResponse](../../assistantlistresponse/)
* classe [AssistantListQueryParameters](../../assistantlistqueryparameters/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)