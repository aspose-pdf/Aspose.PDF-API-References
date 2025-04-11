---
title: OpenAIClient.DeleteFileAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Elimina un archivo específico de forma asíncrona
type: docs
weight: 140
url: /es/net/aspose.pdf.ai/openaiclient/deletefileasync/
---
## Método OpenAIClient.DeleteFileAsync

Elimina un archivo específico de forma asíncrona.

```csharp
public Task<DeleteStatusResponse> DeleteFileAsync(string fileId, 
    CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileId | String | El ID del archivo a eliminar. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene el estado de la operación de eliminación.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el ID del archivo es nulo o está vacío. |

### Véase También

* clase [DeleteStatusResponse](../../deletestatusresponse/)
* clase [OpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)