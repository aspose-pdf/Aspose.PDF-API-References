---
title: OpenAIClient.ModifyVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Modifica un almacén de vectores existente de forma asíncrona
type: docs
weight: 430
url: /es/net/aspose.pdf.ai/openaiclient/modifyvectorstoreasync/
---
## Método OpenAIClient.ModifyVectorStoreAsync

Modifica un almacén de vectores existente de forma asíncrona.

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

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene la respuesta de la modificación del almacén de vectores.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el ID del almacén de vectores es nulo o está vacío. |

### Véase También

* clase [VectorStoreResponse](../../vectorstoreresponse/)
* clase [VectorStoreModifyRequest](../../vectorstoremodifyrequest/)
* clase [OpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)