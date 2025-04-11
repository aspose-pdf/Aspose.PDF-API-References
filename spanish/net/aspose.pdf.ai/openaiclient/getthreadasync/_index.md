---
title: OpenAIClient.GetThreadAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Recupera detalles de un hilo específico de manera asíncrona
type: docs
weight: 300
url: /es/net/aspose.pdf.ai/openaiclient/getthreadasync/
---
## Método OpenAIClient.GetThreadAsync

Recupera detalles de un hilo específico de manera asíncrona.

```csharp
public Task<ThreadResponse> GetThreadAsync(string threadId, 
    CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threadId | String | El ID del hilo a recuperar. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene los detalles del hilo.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el Id del hilo es nulo o está vacío. |

### Véase También

* clase [ThreadResponse](../../threadresponse/)
* clase [OpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)