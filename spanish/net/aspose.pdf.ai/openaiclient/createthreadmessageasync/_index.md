---
title: OpenAIClient.CreateThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Crea un nuevo mensaje dentro de un hilo de manera asíncrona
type: docs
weight: 80
url: /es/net/aspose.pdf.ai/openaiclient/createthreadmessageasync/
---
## Método OpenAIClient.CreateThreadMessageAsync

Crea un nuevo mensaje dentro de un hilo de manera asíncrona.

```csharp
public Task<ThreadMessageResponse> CreateThreadMessageAsync(string threadId, 
    ThreadMessageCreateRequest threadMessageRequest, CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threadId | String | El ID del hilo donde se creará el mensaje. |
| threadMessageRequest | ThreadMessageCreateRequest | Los detalles de la solicitud para crear el mensaje. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene la respuesta de la creación del mensaje.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el ID del hilo es nulo o está vacío. |

### Véase También

* clase [ThreadMessageResponse](../../threadmessageresponse/)
* clase [ThreadMessageCreateRequest](../../threadmessagecreaterequest/)
* clase [OpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)