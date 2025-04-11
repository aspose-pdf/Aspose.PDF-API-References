---
title: OpenAIClient.WaitForVectorStoreToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Espera a que una tienda de vectores específica complete de manera asíncrona
type: docs
weight: 500
url: /es/net/aspose.pdf.ai/openaiclient/waitforvectorstoretocompleteasync/
---
## Método OpenAIClient.WaitForVectorStoreToCompleteAsync

Espera a que una tienda de vectores específica complete de manera asíncrona.

```csharp
public Task<VectorStoreResponse> WaitForVectorStoreToCompleteAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vectorStoreId | String | El ID de la tienda de vectores a monitorear hasta su finalización. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene el estado final de la tienda de vectores.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el Id de la tienda de vectores es nulo o está vacío. |

### Véase También

* clase [VectorStoreResponse](../../vectorstoreresponse/)
* clase [OpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)