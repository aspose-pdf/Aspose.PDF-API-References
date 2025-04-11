---
title: OpenAIClient.GetThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Recupera detalles de un mensaje específico dentro de un hilo de manera asíncrona
type: docs
weight: 310
url: /es/net/aspose.pdf.ai/openaiclient/getthreadmessageasync/
---
## Método OpenAIClient.GetThreadMessageAsync

Recupera detalles de un mensaje específico dentro de un hilo de manera asíncrona.

```csharp
public Task<ThreadMessageResponse> GetThreadMessageAsync(string threadId, string threadMessageId, 
    CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threadId | String | El ID del hilo que contiene el mensaje. |
| threadMessageId | String | El ID del mensaje a recuperar. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene los detalles del mensaje del hilo.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el Id del hilo es nulo o está vacío. |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el Id del mensaje del hilo es nulo o está vacío. |

### Véase También

* clase [ThreadMessageResponse](../../threadmessageresponse/)
* clase [OpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)