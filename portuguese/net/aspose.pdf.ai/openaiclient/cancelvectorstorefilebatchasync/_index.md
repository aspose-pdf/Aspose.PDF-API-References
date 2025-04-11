---
title: OpenAIClient.CancelVectorStoreFileBatchAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Cancela um lote de arquivos de armazenamento vetorial específico de forma assíncrona
type: docs
weight: 20
url: /pt/net/aspose.pdf.ai/openaiclient/cancelvectorstorefilebatchasync/
---
## Método OpenAIClient.CancelVectorStoreFileBatchAsync

Cancela um lote de arquivos de armazenamento vetorial específico de forma assíncrona.

```csharp
public Task<VectorStoreFileBatchResponse> CancelVectorStoreFileBatchAsync(string vectorStoreId, 
    string fileBatchId, CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| vectorStoreId | String | O ID do armazenamento vetorial contendo o lote de arquivos a ser cancelado. |
| fileBatchId | String | O ID do lote de arquivos a ser cancelado. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém a resposta do cancelamento do lote de arquivos.

### Exceções

| exceção | condição |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID do armazenamento vetorial é nulo ou vazio. |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID do lote de arquivos do armazenamento vetorial é nulo ou vazio. |

### Veja Também

* classe [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)