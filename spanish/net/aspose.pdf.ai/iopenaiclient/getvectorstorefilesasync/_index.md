---
title: IOpenAIClient.GetVectorStoreFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Recupera una lista de archivos dentro de un almacén de vectores específico de manera asíncrona
type: docs
weight: 340
url: /es/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilesasync/
---
## Método IOpenAIClient.GetVectorStoreFilesAsync

Recupera una lista de archivos dentro de un almacén de vectores específico de manera asíncrona.

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFilesAsync(string vectorStoreId, 
    VectorStoreFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vectorStoreId | String | El ID del almacén de vectores que contiene los archivos. |
| queryParameters | VectorStoreFileListQueryParameters | Parámetros de consulta opcionales para filtrar la lista de archivos. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene una lista de archivos dentro del almacén de vectores.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el ID del almacén de vectores es nulo o está vacío. |

### Véase También

* clase [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* clase [VectorStoreFileListQueryParameters](../../vectorstorefilelistqueryparameters/)
* interfaz [IOpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)