---
title: IOpenAIClient.CreateVectorStoreFileBatchAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Crea un nuevo lote de archivos de almacenamiento vectorial de forma asíncrona
type: docs
weight: 120
url: /es/net/aspose.pdf.ai/iopenaiclient/createvectorstorefilebatchasync/
---
## Método IOpenAIClient.CreateVectorStoreFileBatchAsync

Crea un nuevo lote de archivos de almacenamiento vectorial de forma asíncrona.

```csharp
public Task<VectorStoreFileBatchResponse> CreateVectorStoreFileBatchAsync(string vectorStoreId, 
    VectorStoreFileBatchCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vectorStoreId | String | El ID del almacenamiento vectorial donde se creará el lote de archivos. |
| vectorStoreFileCreateRequest | VectorStoreFileBatchCreateRequest | El objeto de solicitud que contiene detalles para crear el lote de archivos. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene la respuesta de la creación del lote de archivos.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el ID del almacenamiento vectorial es nulo o está vacío. |

### Véase También

* clase [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* clase [VectorStoreFileBatchCreateRequest](../../vectorstorefilebatchcreaterequest/)
* interfaz [IOpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)