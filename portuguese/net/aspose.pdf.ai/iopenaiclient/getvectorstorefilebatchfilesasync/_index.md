---
title: IOpenAIClient.GetVectorStoreFileBatchFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Recupera uma lista de arquivos dentro de um lote de arquivos de armazenamento vetorial específico de forma assíncrona
type: docs
weight: 330
url: /pt/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchfilesasync/
---
## Método IOpenAIClient.GetVectorStoreFileBatchFilesAsync

Recupera uma lista de arquivos dentro de um lote de arquivos de armazenamento vetorial específico de forma assíncrona.

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFileBatchFilesAsync(string vectorStoreId, 
    string fileBatchId, VectorStoreFileBatchFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| vectorStoreId | String | O ID do armazenamento vetorial contendo o lote de arquivos. |
| fileBatchId | String | O ID do lote de arquivos do qual recuperar os arquivos. |
| queryParameters | VectorStoreFileBatchFileListQueryParameters | Parâmetros de consulta opcionais para filtrar a lista de arquivos. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém uma lista de arquivos dentro do lote de arquivos.

### Exceções

| exceção | condição |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID do armazenamento vetorial é nulo ou vazio. |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID do lote de arquivos de armazenamento vetorial é nulo ou vazio. |

### Veja Também

* classe [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* classe [VectorStoreFileBatchFileListQueryParameters](../../vectorstorefilebatchfilelistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)