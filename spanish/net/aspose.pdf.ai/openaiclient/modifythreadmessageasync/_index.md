---
title: OpenAIClient.ModifyThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Modifica un mensaje existente dentro de un hilo de manera asíncrona
type: docs
weight: 420
url: /es/net/aspose.pdf.ai/openaiclient/modifythreadmessageasync/
---
## Método OpenAIClient.ModifyThreadMessageAsync

Modifica un mensaje existente dentro de un hilo de manera asíncrona.

```csharp
public Task<ThreadMessageResponse> ModifyThreadMessageAsync(string threadId, 
    string threadMessageId, ThreadMessageModifyRequest threadMessageModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threadId | String | El ID del hilo que contiene el mensaje a modificar. |
| threadMessageId | String | El ID del mensaje a modificar. |
| threadMessageModifyRequest | ThreadMessageModifyRequest | Los detalles de la solicitud para modificar el mensaje. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene la respuesta de la modificación del mensaje.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el ID del hilo es nulo o está vacío. |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el ID del mensaje del hilo es nulo o está vacío. |

### Véase También

* clase [ThreadMessageResponse](../../threadmessageresponse/)
* clase [ThreadMessageModifyRequest](../../threadmessagemodifyrequest/)
* clase [OpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)