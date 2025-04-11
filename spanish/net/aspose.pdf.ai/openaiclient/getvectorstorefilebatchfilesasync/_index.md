---
title: OpenAIClient.GetVectorStoreFileBatchFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Recupera una lista de archivos dentro de un lote de archivos de tienda vectorial específico de manera asíncrona
type: docs
weight: 360
url: /es/net/aspose.pdf.ai/openaiclient/getvectorstorefilebatchfilesasync/
---
## Método OpenAIClient.GetVectorStoreFileBatchFilesAsync

Recupera una lista de archivos dentro de un lote de archivos de tienda vectorial específico de manera asíncrona.

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFileBatchFilesAsync(string vectorStoreId, 
    string fileBatchId, VectorStoreFileBatchFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vectorStoreId | String | El ID de la tienda vectorial que contiene el lote de archivos. |
| fileBatchId | String | El ID del lote de archivos del cual recuperar archivos. |
| queryParameters | VectorStoreFileBatchFileListQueryParameters | Parámetros de consulta opcionales para filtrar la lista de archivos. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene una lista de archivos dentro del lote de archivos.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el ID de la tienda vectorial es nulo o está vacío. |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el ID del lote de archivos de la tienda vectorial es nulo o está vacío. |

### Véase También

* clase [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* clase [VectorStoreFileBatchFileListQueryParameters](../../vectorstorefilebatchfilelistqueryparameters/)
* clase [OpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)