---
title: OpenAIClient.GetFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Recupera una lista de archivos de manera asíncrona según el propósito especificado
type: docs
weight: 230
url: /es/net/aspose.pdf.ai/openaiclient/getfilesasync/
---
## Método OpenAIClient.GetFilesAsync

Recupera una lista de archivos de manera asíncrona según el propósito especificado.

```csharp
public Task<FileListResponse> GetFilesAsync(string purpose = null, 
    CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| purpose | String | Opcional. El propósito de los archivos a recuperar. Si es nulo, se recuperan archivos para todos los propósitos. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene una lista de archivos.

### Véase También

* clase [FileListResponse](../../filelistresponse/)
* clase [OpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)