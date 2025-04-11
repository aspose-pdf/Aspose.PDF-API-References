---
title: OpenAIClient.DeleteAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Elimina un asistente existente de manera asíncrona
type: docs
weight: 130
url: /es/net/aspose.pdf.ai/openaiclient/deleteassistantasync/
---
## Método OpenAIClient.DeleteAssistantAsync

Elimina un asistente existente de manera asíncrona.

```csharp
public Task<DeleteStatusResponse> DeleteAssistantAsync(string assistantId, 
    CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| assistantId | String | El ID del asistente a eliminar. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene el estado de la operación de eliminación.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el ID del asistente es nulo o está vacío. |

### Véase También

* clase [DeleteStatusResponse](../../deletestatusresponse/)
* clase [OpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)