---
title: IOpenAIClient.DeleteVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Exclui um armazenamento de vetores de forma assíncrona
type: docs
weight: 170
url: /pt/net/aspose.pdf.ai/iopenaiclient/deletevectorstoreasync/
---
## Método IOpenAIClient.DeleteVectorStoreAsync

Exclui um armazenamento de vetores de forma assíncrona.

```csharp
public Task<DeleteStatusResponse> DeleteVectorStoreAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| vectorStoreId | String | O ID do armazenamento de vetores a ser excluído. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém o status da operação de exclusão.

### Exceções

| exceção | condição |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID do armazenamento de vetores é nulo ou vazio. |

### Veja Também

* classe [DeleteStatusResponse](../../deletestatusresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)