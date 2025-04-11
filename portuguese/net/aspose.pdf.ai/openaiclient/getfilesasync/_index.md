---
title: OpenAIClient.GetFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Recupera uma lista de arquivos de forma assíncrona com base no propósito especificado
type: docs
weight: 230
url: /pt/net/aspose.pdf.ai/openaiclient/getfilesasync/
---
## Método OpenAIClient.GetFilesAsync

Recupera uma lista de arquivos de forma assíncrona com base no propósito especificado.

```csharp
public Task<FileListResponse> GetFilesAsync(string purpose = null, 
    CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| purpose | String | Opcional. O propósito dos arquivos a serem recuperados. Se nulo, arquivos para todos os propósitos são recuperados. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém uma lista de arquivos.

### Veja Também

* classe [FileListResponse](../../filelistresponse/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)