---
title: OpenAIClient.CancelVectorStoreFileBatchAsync
second_title: Aspose.PDF for .NET API Reference
description: Método de OpenAIClient. Cancela un lote de archivos de la tienda de vectores de forma asíncrona
type: docs
weight: 20
url: /es/net/aspose.pdf.ai/openaiclient/cancelvectorstorefilebatchasync/
---
## Método OpenAIClient.CancelVectorStoreFileBatchAsync

Cancela un lote específico de archivos de la tienda de vectores de forma asíncrona.

```csharp
public Task<VectorStoreFileBatchResponse> CancelVectorStoreFileBatchAsync(string vectorStoreId, 
    string fileBatchId, CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vectorStoreId | String | El ID de la tienda de vectores que contiene el lote de archivos a cancelar. |
| fileBatchId | String | El ID del lote de archivos a cancelar. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene la respuesta de la cancelación del lote de archivos.

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