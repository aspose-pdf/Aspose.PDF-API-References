---
title: OpenAIClient.WaitForAssistantMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Espera el primer mensaje del asistente dentro de un hilo de manera asíncrona
type: docs
weight: 460
url: /es/net/aspose.pdf.ai/openaiclient/waitforassistantmessageasync/
---
## Método OpenAIClient.WaitForAssistantMessageAsync

Espera el primer mensaje del asistente dentro de un hilo de manera asíncrona.

```csharp
public Task<ThreadMessageResponse> WaitForAssistantMessageAsync(string threadId, 
    ThreadMessageListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threadId | String | El ID del hilo a monitorear para el primer mensaje del asistente. |
| queryParameters | ThreadMessageListQueryParameters | Parámetros de consulta opcionales para filtrar la lista de mensajes. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene el primer mensaje del asistente en el hilo.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el ID del hilo es nulo o está vacío. |

### Ver También

* clase [ThreadMessageResponse](../../threadmessageresponse/)
* clase [ThreadMessageListQueryParameters](../../threadmessagelistqueryparameters/)
* clase [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)