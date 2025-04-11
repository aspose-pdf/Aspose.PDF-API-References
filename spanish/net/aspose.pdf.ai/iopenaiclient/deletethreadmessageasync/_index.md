---
title: IOpenAIClient.DeleteThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Elimina un mensaje dentro de un hilo de manera asíncrona
type: docs
weight: 160
url: /es/net/aspose.pdf.ai/iopenaiclient/deletethreadmessageasync/
---
## Método IOpenAIClient.DeleteThreadMessageAsync

Elimina un mensaje dentro de un hilo de manera asíncrona.

```csharp
public Task<DeleteStatusResponse> DeleteThreadMessageAsync(string threadId, string threadMessageId, 
    CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threadId | String | El ID del hilo que contiene el mensaje a eliminar. |
| threadMessageId | String | El ID del mensaje a eliminar. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene el estado de la operación de eliminación.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el Id del hilo es nulo o está vacío. |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el Id del mensaje del hilo es nulo o está vacío. |

### Véase También

* clase [DeleteStatusResponse](../../deletestatusresponse/)
* interfaz [IOpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)