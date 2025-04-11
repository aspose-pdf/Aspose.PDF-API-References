---
title: IOpenAIClient.GetVectorStoreFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Recupera uma lista de arquivos dentro de um armazenamento vetorial específico de forma assíncrona
type: docs
weight: 340
url: /pt/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilesasync/
---
## Método IOpenAIClient.GetVectorStoreFilesAsync

Recupera uma lista de arquivos dentro de um armazenamento vetorial específico de forma assíncrona.

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFilesAsync(string vectorStoreId, 
    VectorStoreFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| vectorStoreId | String | O ID do armazenamento vetorial contendo os arquivos. |
| queryParameters | VectorStoreFileListQueryParameters | Parâmetros de consulta opcionais para filtrar a lista de arquivos. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém uma lista de arquivos dentro do armazenamento vetorial.

### Exceções

| exceção | condição |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID do armazenamento vetorial é nulo ou vazio. |

### Veja Também

* classe [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* classe [VectorStoreFileListQueryParameters](../../vectorstorefilelistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)