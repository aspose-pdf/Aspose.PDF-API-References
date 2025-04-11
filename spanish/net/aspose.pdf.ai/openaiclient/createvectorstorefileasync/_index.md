---
title: OpenAIClient.CreateVectorStoreFileAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Crea un nuevo archivo de almacenamiento de vectores de forma asíncrona
type: docs
weight: 110
url: /es/net/aspose.pdf.ai/openaiclient/createvectorstorefileasync/
---
## Método OpenAIClient.CreateVectorStoreFileAsync

Crea un nuevo archivo de almacenamiento de vectores de forma asíncrona.

```csharp
public Task<VectorStoreFileResponse> CreateVectorStoreFileAsync(string vectorStoreId, 
    VectorStoreFileCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vectorStoreId | String | El ID del almacenamiento de vectores donde se creará el archivo. |
| vectorStoreFileCreateRequest | VectorStoreFileCreateRequest | El objeto de solicitud que contiene detalles para crear el archivo. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene la respuesta de la creación del archivo.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el ID del almacenamiento de vectores es nulo o está vacío. |

### Ver También

* clase [VectorStoreFileResponse](../../vectorstorefileresponse/)
* clase [VectorStoreFileCreateRequest](../../vectorstorefilecreaterequest/)
* clase [OpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)