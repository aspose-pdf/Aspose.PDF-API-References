---
title: IOpenAIClient.GetFileAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Recupera detalles de un archivo específico de manera asíncrona
type: docs
weight: 210
url: /es/net/aspose.pdf.ai/iopenaiclient/getfileasync/
---
## Método IOpenAIClient.GetFileAsync

Recupera detalles de un archivo específico de manera asíncrona.

```csharp
public Task<FileResponse> GetFileAsync(string fileId, 
    CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileId | String | El ID del archivo a recuperar. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene los detalles del archivo.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el ID del archivo es nulo o está vacío. |

### Véase También

* clase [FileResponse](../../fileresponse/)
* interfaz [IOpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)