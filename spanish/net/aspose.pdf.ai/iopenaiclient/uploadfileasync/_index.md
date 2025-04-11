---
title: IOpenAIClient.UploadFileAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Sube un archivo de manera asíncrona al servidor de OpenAI
type: docs
weight: 420
url: /es/net/aspose.pdf.ai/iopenaiclient/uploadfileasync/
---
## Método IOpenAIClient.UploadFileAsync

Sube un archivo de manera asíncrona al servidor de OpenAI.

```csharp
public Task<FileResponse> UploadFileAsync(string purpose, string fileName, byte[] fileBytes, 
    CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| purpose | String | El propósito de la carga del archivo, que típicamente describe cómo se utilizará el archivo. |
| fileName | String | El nombre del archivo a subir. |
| fileBytes | Byte[] | El arreglo de bytes que contiene los datos del archivo. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene la respuesta de la carga del archivo.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el propósito del archivo es nulo o está vacío. |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el nombre del archivo es nulo o está vacío. |

### Véase También

* clase [FileResponse](../../fileresponse/)
* interfaz [IOpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)