---
title: OpenAIClient.WaitForRunToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Espera a que una ejecución se complete dentro de un hilo de manera asíncrona
type: docs
weight: 470
url: /es/net/aspose.pdf.ai/openaiclient/waitforruntocompleteasync/
---
## Método OpenAIClient.WaitForRunToCompleteAsync

Espera a que una ejecución se complete dentro de un hilo de manera asíncrona.

```csharp
public Task<RunResponse> WaitForRunToCompleteAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threadId | String | El ID del hilo que contiene la ejecución. |
| runId | String | El ID de la ejecución a monitorear hasta su finalización. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene el estado final de la ejecución.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el ID del hilo es nulo o está vacío. |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el ID de la ejecución es nulo o está vacío. |

### Véase También

* clase [RunResponse](../../runresponse/)
* clase [OpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)