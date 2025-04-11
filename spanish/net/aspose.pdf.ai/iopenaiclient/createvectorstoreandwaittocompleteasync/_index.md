---
title: IOpenAIClient.CreateVectorStoreAndWaitToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Crea un nuevo almacén de vectores y espera a que se complete de manera asíncrona
type: docs
weight: 90
url: /es/net/aspose.pdf.ai/iopenaiclient/createvectorstoreandwaittocompleteasync/
---
## Método IOpenAIClient.CreateVectorStoreAndWaitToCompleteAsync

Crea un nuevo almacén de vectores y espera a que se complete de manera asíncrona.

```csharp
public Task<VectorStoreResponse> CreateVectorStoreAndWaitToCompleteAsync(
    VectorStoreCreateRequest vectorStoreCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vectorStoreCreateRequest | VectorStoreCreateRequest | El objeto de solicitud que contiene detalles para crear el almacén de vectores. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene la respuesta de la creación del almacén de vectores después de la finalización.

### Véase También

* clase [VectorStoreResponse](../../vectorstoreresponse/)
* clase [VectorStoreCreateRequest](../../vectorstorecreaterequest/)
* interfaz [IOpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)