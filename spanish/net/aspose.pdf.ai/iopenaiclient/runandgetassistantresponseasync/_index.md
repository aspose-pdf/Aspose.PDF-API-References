---
title: IOpenAIClient.RunAndGetAssistantResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Ejecuta el asistente con el threadId especificado y runCreateRequest y obtiene de manera asíncrona la respuesta del asistente
type: docs
weight: 410
url: /es/net/aspose.pdf.ai/iopenaiclient/runandgetassistantresponseasync/
---
## Método IOpenAIClient.RunAndGetAssistantResponseAsync

Ejecuta el asistente con el threadId especificado y runCreateRequest, y obtiene de manera asíncrona la respuesta del asistente.

```csharp
public Task<string> RunAndGetAssistantResponseAsync(string threadId, 
    RunCreateRequest runCreateRequest, CancellationToken? cancellationToken)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threadId | String | El ID del hilo. |
| runCreateRequest | RunCreateRequest | La solicitud de creación de ejecución. |
| cancellationToken | Nullable`1 | El token de cancelación (opcional). |

### Valor de Retorno

Una tarea que representa la operación asíncrona con la cadena de respuesta del asistente.

### Véase También

* clase [RunCreateRequest](../../runcreaterequest/)
* interfaz [IOpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblaje [Aspose.PDF](../../../)