---
title: IOpenAIClient.GetThreadMessagesAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Recupera una lista de mensajes para un hilo específico de manera asíncrona
type: docs
weight: 290
url: /es/net/aspose.pdf.ai/iopenaiclient/getthreadmessagesasync/
---
## Método IOpenAIClient.GetThreadMessagesAsync

Recupera una lista de mensajes para un hilo específico de manera asíncrona.

```csharp
public Task<ThreadMessageListResponse> GetThreadMessagesAsync(string threadId, 
    ThreadMessageListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threadId | String | El ID del hilo del que recuperar mensajes. |
| queryParameters | ThreadMessageListQueryParameters | Parámetros de consulta opcionales para filtrar la lista de mensajes. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene una lista de mensajes del hilo.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el Id del hilo es nulo o está vacío. |

### Véase También

* clase [ThreadMessageListResponse](../../threadmessagelistresponse/)
* clase [ThreadMessageListQueryParameters](../../threadmessagelistqueryparameters/)
* interfaz [IOpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)