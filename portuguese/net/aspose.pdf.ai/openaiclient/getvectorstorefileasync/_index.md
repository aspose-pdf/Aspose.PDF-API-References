---
title: OpenAIClient.GetVectorStoreFileAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Recupera detalhes de um arquivo específico dentro de um armazenamento vetorial de forma assíncrona
type: docs
weight: 340
url: /pt/net/aspose.pdf.ai/openaiclient/getvectorstorefileasync/
---
## Método OpenAIClient.GetVectorStoreFileAsync

Recupera detalhes de um arquivo específico dentro de um armazenamento vetorial de forma assíncrona.

```csharp
public Task<VectorStoreFileResponse> GetVectorStoreFileAsync(string vectorStoreId, string fileId, 
    CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| vectorStoreId | String | O ID do armazenamento vetorial que contém o arquivo. |
| fileId | String | O ID do arquivo a ser recuperado. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém os detalhes do arquivo.

### Exceções

| exceção | condição |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID do armazenamento vetorial é nulo ou vazio. |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID do arquivo é nulo ou vazio. |

### Veja Também

* classe [VectorStoreFileResponse](../../vectorstorefileresponse/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)