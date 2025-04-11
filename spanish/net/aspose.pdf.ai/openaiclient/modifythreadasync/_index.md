---
title: OpenAIClient.ModifyThreadAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Modifica un hilo existente de manera asíncrona
type: docs
weight: 410
url: /es/net/aspose.pdf.ai/openaiclient/modifythreadasync/
---
## Método OpenAIClient.ModifyThreadAsync

Modifica un hilo existente de manera asíncrona.

```csharp
public Task<ThreadResponse> ModifyThreadAsync(string threadId, 
    ThreadModifyRequest threadModifyRequest, CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threadId | String | El ID del hilo a modificar. |
| threadModifyRequest | ThreadModifyRequest | El objeto de solicitud que contiene los detalles de la modificación. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene la respuesta de la modificación del hilo.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el ID del hilo es nulo o está vacío. |

### Véase También

* clase [ThreadResponse](../../threadresponse/)
* clase [ThreadModifyRequest](../../threadmodifyrequest/)
* clase [OpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)