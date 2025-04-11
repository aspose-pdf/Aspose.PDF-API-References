---
title: OpenAIClient.WaitForThreadMessageToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Espera a que un mensaje de hilo específico se complete de manera asíncrona
type: docs
weight: 480
url: /es/net/aspose.pdf.ai/openaiclient/waitforthreadmessagetocompleteasync/
---
## Método OpenAIClient.WaitForThreadMessageToCompleteAsync

Espera a que un mensaje de hilo específico se complete de manera asíncrona.

```csharp
public Task<ThreadMessageResponse> WaitForThreadMessageToCompleteAsync(string threadId, 
    string threadMessageId, CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threadId | String | El ID del hilo que contiene el mensaje. |
| threadMessageId | String | El ID del mensaje a monitorear hasta su finalización. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene el estado final del mensaje.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el Id del hilo es nulo o está vacío. |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el Id del mensaje del hilo es nulo o está vacío. |

### Ver También

* clase [ThreadMessageResponse](../../threadmessageresponse/)
* clase [OpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)