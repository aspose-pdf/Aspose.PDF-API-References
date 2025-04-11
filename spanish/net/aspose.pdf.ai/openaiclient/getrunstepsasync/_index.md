---
title: OpenAIClient.GetRunStepsAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Recupera una lista de pasos para una ejecución específica dentro de un hilo de manera asíncrona
type: docs
weight: 280
url: /es/net/aspose.pdf.ai/openaiclient/getrunstepsasync/
---
## Método OpenAIClient.GetRunStepsAsync

Recupera una lista de pasos para una ejecución específica dentro de un hilo de manera asíncrona.

```csharp
public Task<RunStepListResponse> GetRunStepsAsync(string threadId, string runId, 
    RunStepListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threadId | String | El ID del hilo que contiene la ejecución. |
| runId | String | El ID de la ejecución de la que recuperar pasos. |
| queryParameters | RunStepListQueryParameters | Parámetros de consulta opcionales para filtrar la lista de pasos de ejecución. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene la lista de pasos de ejecución.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el Id del hilo es nulo o está vacío. |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el Id de la ejecución es nulo o está vacío. |

### Véase También

* clase [RunStepListResponse](../../runsteplistresponse/)
* clase [RunStepListQueryParameters](../../runsteplistqueryparameters/)
* clase [OpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)