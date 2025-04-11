---
title: OpenAIClient.DeleteVectorStoreFileAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Elimina un archivo dentro de un almacén de vectores de manera asíncrona
type: docs
weight: 180
url: /es/net/aspose.pdf.ai/openaiclient/deletevectorstorefileasync/
---
## Método OpenAIClient.DeleteVectorStoreFileAsync

Elimina un archivo dentro de un almacén de vectores de manera asíncrona.

```csharp
public Task<DeleteStatusResponse> DeleteVectorStoreFileAsync(string vectorStoreId, string fileId, 
    CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vectorStoreId | String | El ID del almacén de vectores que contiene el archivo a eliminar. |
| fileId | String | El ID del archivo a eliminar. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene el estado de la operación de eliminación.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el ID del almacén de vectores es nulo o está vacío. |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el ID del archivo es nulo o está vacío. |

### Véase También

* clase [DeleteStatusResponse](../../deletestatusresponse/)
* clase [OpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)