---
title: OpenAIClient.GetAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Recupera detalles de un asistente específico de manera asíncrona
type: docs
weight: 190
url: /es/net/aspose.pdf.ai/openaiclient/getassistantasync/
---
## Método OpenAIClient.GetAssistantAsync

Recupera detalles de un asistente específico de manera asíncrona.

```csharp
public Task<AssistantResponse> GetAssistantAsync(string assistantId, 
    CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| assistantId | String | El ID del asistente a recuperar. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene los detalles del asistente.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el ID del asistente es nulo o está vacío. |

### Véase También

* clase [AssistantResponse](../../assistantresponse/)
* clase [OpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)