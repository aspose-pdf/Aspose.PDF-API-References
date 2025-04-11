---
title: OpenAIClient.DeleteThreadAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Elimina un hilo existente de manera asíncrona
type: docs
weight: 150
url: /es/net/aspose.pdf.ai/openaiclient/deletethreadasync/
---
## Método OpenAIClient.DeleteThreadAsync

Elimina un hilo existente de manera asíncrona.

```csharp
public Task<DeleteStatusResponse> DeleteThreadAsync(string threadId, 
    CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threadId | String | El ID del hilo a eliminar. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene el estado de la operación de eliminación.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el ID del hilo es nulo o está vacío. |

### Véase También

* clase [DeleteStatusResponse](../../deletestatusresponse/)
* clase [OpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)