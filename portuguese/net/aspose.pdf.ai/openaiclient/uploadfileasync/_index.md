---
title: OpenAIClient.UploadFileAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Faz o upload de um arquivo de forma assíncrona para o servidor OpenAI
type: docs
weight: 450
url: /pt/net/aspose.pdf.ai/openaiclient/uploadfileasync/
---
## Método OpenAIClient.UploadFileAsync

Faz o upload de um arquivo de forma assíncrona para o servidor OpenAI.

```csharp
public Task<FileResponse> UploadFileAsync(string purpose, string fileName, byte[] fileBytes, 
    CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| purpose | String | O propósito do upload do arquivo, tipicamente descrevendo como o arquivo será utilizado. |
| fileName | String | O nome do arquivo a ser enviado. |
| fileBytes | Byte[] | O array de bytes contendo os dados do arquivo. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém a resposta do upload do arquivo.

### Exceções

| exceção | condição |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lançada quando o propósito do arquivo é nulo ou vazio. |
| [AIClientException](../../aiclientexception/) | Lançada quando o nome do arquivo é nulo ou vazio. |

### Veja Também

* classe [FileResponse](../../fileresponse/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)