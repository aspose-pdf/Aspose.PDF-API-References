---
title: IOpenAIClient.GetVectorStoreFileAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Recupera detalles de un archivo específico dentro de un almacén de vectores de manera asincrónica
type: docs
weight: 310
url: /es/net/aspose.pdf.ai/iopenaiclient/getvectorstorefileasync/
---
## Método IOpenAIClient.GetVectorStoreFileAsync

Recupera detalles de un archivo específico dentro de un almacén de vectores de manera asincrónica.

```csharp
public Task<VectorStoreFileResponse> GetVectorStoreFileAsync(string vectorStoreId, string fileId, 
    CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vectorStoreId | String | El ID del almacén de vectores que contiene el archivo. |
| fileId | String | El ID del archivo a recuperar. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asincrónica. El resultado de la tarea contiene los detalles del archivo.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el ID del almacén de vectores es nulo o está vacío. |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el ID del archivo es nulo o está vacío. |

### Véase También

* clase [VectorStoreFileResponse](../../vectorstorefileresponse/)
* interfaz [IOpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)