---
title: OpenAIClient.DeleteVectorStoreFileAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Exclui um arquivo dentro de um armazenamento vetorial de forma assíncrona
type: docs
weight: 180
url: /pt/net/aspose.pdf.ai/openaiclient/deletevectorstorefileasync/
---
## Método OpenAIClient.DeleteVectorStoreFileAsync

Exclui um arquivo dentro de um armazenamento vetorial de forma assíncrona.

```csharp
public Task<DeleteStatusResponse> DeleteVectorStoreFileAsync(string vectorStoreId, string fileId, 
    CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| vectorStoreId | String | O ID do armazenamento vetorial que contém o arquivo a ser excluído. |
| fileId | String | O ID do arquivo a ser excluído. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém o status da operação de exclusão.

### Exceções

| exceção | condição |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID do armazenamento vetorial é nulo ou vazio. |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID do arquivo é nulo ou vazio. |

### Veja Também

* classe [DeleteStatusResponse](../../deletestatusresponse/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)