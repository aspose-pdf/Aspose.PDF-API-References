---
title: OpenAIClient.WaitForVectorStoreFileToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Espera a que un archivo específico de la tienda de vectores se complete de manera asíncrona
type: docs
weight: 490
url: /es/net/aspose.pdf.ai/openaiclient/waitforvectorstorefiletocompleteasync/
---
## Método OpenAIClient.WaitForVectorStoreFileToCompleteAsync

Espera a que un archivo específico de la tienda de vectores se complete de manera asíncrona.

```csharp
public Task<VectorStoreFileResponse> WaitForVectorStoreFileToCompleteAsync(string vectorStoreId, 
    string fileId, CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vectorStoreId | String | El ID de la tienda de vectores que contiene el archivo. |
| fileId | String | El ID del archivo a monitorear hasta su finalización. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene el estado final del archivo.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el Id de la tienda de vectores es nulo o está vacío. |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el Id del archivo es nulo o está vacío. |

### Véase También

* clase [VectorStoreFileResponse](../../vectorstorefileresponse/)
* clase [OpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)