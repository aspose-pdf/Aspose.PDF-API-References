---
title: IOpenAIClient.ModifyVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Modifica un almacén de vectores existente de forma asincrónica
type: docs
weight: 400
url: /es/net/aspose.pdf.ai/iopenaiclient/modifyvectorstoreasync/
---
## Método IOpenAIClient.ModifyVectorStoreAsync

Modifica un almacén de vectores existente de forma asincrónica.

```csharp
public Task<VectorStoreResponse> ModifyVectorStoreAsync(string vectorStoreId, 
    VectorStoreModifyRequest vectorStoreModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vectorStoreId | String | El ID del almacén de vectores a modificar. |
| vectorStoreModifyRequest | VectorStoreModifyRequest | El objeto de solicitud que contiene los detalles de la modificación. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asincrónica. El resultado de la tarea contiene la respuesta de la modificación del almacén de vectores.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el ID del almacén de vectores es nulo o está vacío. |

### Véase También

* clase [VectorStoreResponse](../../vectorstoreresponse/)
* clase [VectorStoreModifyRequest](../../vectorstoremodifyrequest/)
* interfaz [IOpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)