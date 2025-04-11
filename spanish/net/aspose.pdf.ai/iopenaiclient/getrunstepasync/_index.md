---
title: IOpenAIClient.GetRunStepAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Recupera detalles de un paso específico dentro de una ejecución de manera asincrónica
type: docs
weight: 250
url: /es/net/aspose.pdf.ai/iopenaiclient/getrunstepasync/
---
## Método IOpenAIClient.GetRunStepAsync

Recupera detalles de un paso específico dentro de una ejecución de manera asincrónica.

```csharp
public Task<RunStepResponse> GetRunStepAsync(string threadId, string runId, string runStepId, 
    CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threadId | String | El ID del hilo que contiene la ejecución. |
| runId | String | El ID de la ejecución que contiene el paso. |
| runStepId | String | El ID del paso de la ejecución a recuperar. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asincrónica. El resultado de la tarea contiene los detalles del paso de la ejecución.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el Id del hilo es nulo o está vacío. |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el Id de la ejecución es nulo o está vacío. |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el Id del paso de la ejecución es nulo o está vacío. |

### Véase También

* clase [RunStepResponse](../../runstepresponse/)
* interfaz [IOpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblaje [Aspose.PDF](../../../)