---
title: IOpenAIClient.CreateVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Crea un nuevo almacén de vectores de manera asíncrona
type: docs
weight: 100
url: /es/net/aspose.pdf.ai/iopenaiclient/createvectorstoreasync/
---
## Método IOpenAIClient.CreateVectorStoreAsync

Crea un nuevo almacén de vectores de manera asíncrona.

```csharp
public Task<VectorStoreResponse> CreateVectorStoreAsync(
    VectorStoreCreateRequest vectorStoreCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vectorStoreCreateRequest | VectorStoreCreateRequest | El objeto de solicitud que contiene detalles para crear el almacén de vectores. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene la respuesta de la creación del almacén de vectores.

### Véase También

* clase [VectorStoreResponse](../../vectorstoreresponse/)
* clase [VectorStoreCreateRequest](../../vectorstorecreaterequest/)
* interfaz [IOpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)