---
title: IOpenAIClient.GetVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Recupera detalles de un almacén de vectores específico de manera asincrónica
type: docs
weight: 300
url: /es/net/aspose.pdf.ai/iopenaiclient/getvectorstoreasync/
---
## Método IOpenAIClient.GetVectorStoreAsync

Recupera detalles de un almacén de vectores específico de manera asincrónica.

```csharp
public Task<VectorStoreResponse> GetVectorStoreAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vectorStoreId | String | El ID del almacén de vectores a recuperar. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asincrónica. El resultado de la tarea contiene los detalles del almacén de vectores.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el Id del almacén de vectores es nulo o está vacío. |

### Véase También

* clase [VectorStoreResponse](../../vectorstoreresponse/)
* interfaz [IOpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)