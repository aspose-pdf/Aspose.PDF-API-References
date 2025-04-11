---
title: IOpenAIClient.GetAssistantsAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Recupera una lista de asistentes de manera asíncrona
type: docs
weight: 200
url: /es/net/aspose.pdf.ai/iopenaiclient/getassistantsasync/
---
## Método IOpenAIClient.GetAssistantsAsync

Recupera una lista de asistentes de manera asíncrona.

```csharp
public Task<AssistantListResponse> GetAssistantsAsync(
    AssistantListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| queryParameters | AssistantListQueryParameters | Parámetros de consulta opcionales para filtrar la lista de asistentes. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene la lista de asistentes.

### Véase También

* clase [AssistantListResponse](../../assistantlistresponse/)
* clase [AssistantListQueryParameters](../../assistantlistqueryparameters/)
* interfaz [IOpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)