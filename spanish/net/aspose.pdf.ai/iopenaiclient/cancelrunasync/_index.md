---
title: IOpenAIClient.CancelRunAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Cancela una ejecución existente dentro de un hilo de manera asíncrona
type: docs
weight: 10
url: /es/net/aspose.pdf.ai/iopenaiclient/cancelrunasync/
---
## Método IOpenAIClient.CancelRunAsync

Cancela una ejecución existente dentro de un hilo de manera asíncrona.

```csharp
public Task<RunResponse> CancelRunAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threadId | String | El ID del hilo que contiene la ejecución a cancelar. |
| runId | String | El ID de la ejecución a cancelar. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene la respuesta de la cancelación de la ejecución.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el Id del hilo es nulo o está vacío. |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el Id de la ejecución es nulo o está vacío. |

### Véase También

* clase [RunResponse](../../runresponse/)
* interfaz [IOpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)