---
title: IOpenAIClient.GetVectorStoreFileBatchFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Recupera una lista de archivos dentro de un lote de archivos de tienda vectorial específico de manera asincrónica
type: docs
weight: 330
url: /es/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchfilesasync/
---
## Método IOpenAIClient.GetVectorStoreFileBatchFilesAsync

Recupera una lista de archivos dentro de un lote de archivos de tienda vectorial específico de manera asincrónica.

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

Una tarea que representa la operación asincrónica. El resultado de la tarea contiene una lista de archivos dentro del lote de archivos.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el Id de la tienda vectorial es nulo o está vacío. |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el Id del lote de archivos de la tienda vectorial es nulo o está vacío. |

### Véase También

* clase [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* clase [VectorStoreFileBatchFileListQueryParameters](../../vectorstorefilebatchfilelistqueryparameters/)
* interfaz [IOpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)