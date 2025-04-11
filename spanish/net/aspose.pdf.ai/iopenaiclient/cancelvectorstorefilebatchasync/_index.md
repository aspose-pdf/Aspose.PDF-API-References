---
title: IOpenAIClient.CancelVectorStoreFileBatchAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Cancela un lote de archivos de almacenamiento vectorial específico de manera asíncrona
type: docs
weight: 20
url: /es/net/aspose.pdf.ai/iopenaiclient/cancelvectorstorefilebatchasync/
---
## Método IOpenAIClient.CancelVectorStoreFileBatchAsync

Cancela un lote de archivos de almacenamiento vectorial específico de manera asíncrona.

```csharp
public Task<VectorStoreFileBatchResponse> CancelVectorStoreFileBatchAsync(string vectorStoreId, 
    string fileBatchId, CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vectorStoreId | String | El ID del almacenamiento vectorial que contiene el lote de archivos a cancelar. |
| fileBatchId | String | El ID del lote de archivos a cancelar. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene la respuesta de la cancelación del lote de archivos.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el ID del almacenamiento vectorial es nulo o está vacío. |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el ID del lote de archivos de almacenamiento vectorial es nulo o está vacío. |

### Véase También

* clase [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* interfaz [IOpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblaje [Aspose.PDF](../../../)