---
title: OpenAIClient.GetVectorStoreFileBatchAsync
second_title: Aspose.PDF for .NET API Reference
description: Método de OpenAIClient. Recupera detalles de un lote de archivos de tienda de vectores de manera asíncrona
type: docs
weight: 350
url: /es/net/aspose.pdf.ai/openaiclient/getvectorstorefilebatchasync/
---
## Método OpenAIClient.GetVectorStoreFileBatchAsync

Recupera detalles de un lote específico de archivos de tienda de vectores de manera asíncrona.

```csharp
public Task<VectorStoreFileBatchResponse> GetVectorStoreFileBatchAsync(string vectorStoreId, 
    string fileBatchId, CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vectorStoreId | String | El ID de la tienda de vectores que contiene el lote de archivos. |
| fileBatchId | String | El ID del lote de archivos a recuperar. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene los detalles del lote de archivos.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el ID de la tienda de vectores es nulo o está vacío. |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el ID del lote de archivos de la tienda de vectores es nulo o está vacío. |

### Véase También

* clase [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* clase [OpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)