---
title: IOpenAIClient.GetThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Recupera detalles de un mensaje específico dentro de un hilo de manera asincrónica
type: docs
weight: 280
url: /es/net/aspose.pdf.ai/iopenaiclient/getthreadmessageasync/
---
## Método IOpenAIClient.GetThreadMessageAsync

Recupera detalles de un mensaje específico dentro de un hilo de manera asincrónica.

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

Una tarea que representa la operación asincrónica. El resultado de la tarea contiene los detalles del mensaje del hilo.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el Id del hilo es nulo o está vacío. |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el Id del mensaje del hilo es nulo o está vacío. |

### Véase También

* clase [ThreadMessageResponse](../../threadmessageresponse/)
* interfaz [IOpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)