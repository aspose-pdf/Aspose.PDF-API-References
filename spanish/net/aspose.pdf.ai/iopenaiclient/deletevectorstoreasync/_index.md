---
title: IOpenAIClient.DeleteVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Elimina un almacén de vectores de forma asíncrona
type: docs
weight: 170
url: /es/net/aspose.pdf.ai/iopenaiclient/deletevectorstoreasync/
---
## Método IOpenAIClient.DeleteVectorStoreAsync

Elimina un almacén de vectores de forma asíncrona.

```csharp
public Task<DeleteStatusResponse> DeleteVectorStoreAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vectorStoreId | String | El ID del almacén de vectores a eliminar. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene el estado de la operación de eliminación.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el ID del almacén de vectores es nulo o está vacío. |

### Véase También

* clase [DeleteStatusResponse](../../deletestatusresponse/)
* interfaz [IOpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)