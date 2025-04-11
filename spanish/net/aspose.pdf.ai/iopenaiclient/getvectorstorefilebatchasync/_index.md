---
title: IOpenAIClient.GetVectorStoreFileBatchAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Recupera detalles de un lote de archivos de tienda de vectores específico de manera asíncrona
type: docs
weight: 320
url: /es/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchasync/
---
## Método IOpenAIClient.GetVectorStoreFileBatchAsync

Recupera detalles de un lote de archivos de tienda de vectores específico de manera asíncrona.

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
* interfaz [IOpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)