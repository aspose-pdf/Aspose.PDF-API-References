---
title: IOpenAIClient.ModifyAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Modifica un asistente existente de manera asíncrona
type: docs
weight: 360
url: /es/net/aspose.pdf.ai/iopenaiclient/modifyassistantasync/
---
## Método IOpenAIClient.ModifyAssistantAsync

Modifica un asistente existente de manera asíncrona.

```csharp
public Task<AssistantResponse> ModifyAssistantAsync(string assistantId, 
    AssistantModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| assistantId | String | El ID del asistente a modificar. |
| assistantModifyRequest | AssistantModifyRequest | El objeto de solicitud que contiene los detalles de la modificación. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene la respuesta de la modificación del asistente.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el ID del asistente es nulo o está vacío. |

### Véase También

* clase [AssistantResponse](../../assistantresponse/)
* clase [AssistantModifyRequest](../../assistantmodifyrequest/)
* interfaz [IOpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)