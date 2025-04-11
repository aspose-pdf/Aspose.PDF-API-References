---
title: OpenAIClient.CreateVectorStoreFileBatchAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Cria um novo lote de arquivos de armazenamento vetorial de forma assíncrona
type: docs
weight: 120
url: /pt/net/aspose.pdf.ai/openaiclient/createvectorstorefilebatchasync/
---
## Método OpenAIClient.CreateVectorStoreFileBatchAsync

Cria um novo lote de arquivos de armazenamento vetorial de forma assíncrona.

```csharp
public Task<VectorStoreFileBatchResponse> CreateVectorStoreFileBatchAsync(string vectorStoreId, 
    VectorStoreFileBatchCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| vectorStoreId | String | O ID do armazenamento vetorial onde o lote de arquivos será criado. |
| vectorStoreFileCreateRequest | VectorStoreFileBatchCreateRequest | O objeto de solicitação contendo detalhes para criar o lote de arquivos. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém a resposta da criação do lote de arquivos.

### Exceções

| exceção | condição |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID do armazenamento vetorial é nulo ou vazio. |

### Veja Também

* classe [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* classe [VectorStoreFileBatchCreateRequest](../../vectorstorefilebatchcreaterequest/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)