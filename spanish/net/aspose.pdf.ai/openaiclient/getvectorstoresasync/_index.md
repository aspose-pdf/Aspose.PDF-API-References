---
title: OpenAIClient.GetVectorStoresAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Recupera una lista de almacenes de vectores de manera asíncrona
type: docs
weight: 380
url: /es/net/aspose.pdf.ai/openaiclient/getvectorstoresasync/
---
## Método OpenAIClient.GetVectorStoresAsync

Recupera una lista de almacenes de vectores de manera asíncrona.

```csharp
public Task<VectorStoreListResponse> GetVectorStoresAsync(
    VectorStoreListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| queryParameters | VectorStoreListQueryParameters | Parámetros de consulta opcionales para filtrar la lista de almacenes de vectores. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene una lista de almacenes de vectores.

### Véase También

* clase [VectorStoreListResponse](../../vectorstorelistresponse/)
* clase [VectorStoreListQueryParameters](../../vectorstorelistqueryparameters/)
* clase [OpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)