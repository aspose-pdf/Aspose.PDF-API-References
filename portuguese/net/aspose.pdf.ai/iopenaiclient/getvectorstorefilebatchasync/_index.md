---
title: IOpenAIClient.GetVectorStoreFileBatchAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Recupera detalhes de um lote de arquivos de armazenamento vetorial específico de forma assíncrona
type: docs
weight: 320
url: /pt/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchasync/
---
## Método IOpenAIClient.GetVectorStoreFileBatchAsync

Recupera detalhes de um lote de arquivos de armazenamento vetorial específico de forma assíncrona.

```csharp
public Task<VectorStoreFileBatchResponse> GetVectorStoreFileBatchAsync(string vectorStoreId, 
    string fileBatchId, CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| vectorStoreId | String | O ID do armazenamento vetorial contendo o lote de arquivos. |
| fileBatchId | String | O ID do lote de arquivos a ser recuperado. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém os detalhes do lote de arquivos.

### Exceções

| exceção | condição |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID do armazenamento vetorial é nulo ou vazio. |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID do lote de arquivos do armazenamento vetorial é nulo ou vazio. |

### Veja Também

* classe [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)