---
title: IOpenAIClient.ModifyVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Modifica um repositório de vetores existente de forma assíncrona
type: docs
weight: 400
url: /pt/net/aspose.pdf.ai/iopenaiclient/modifyvectorstoreasync/
---
## Método IOpenAIClient.ModifyVectorStoreAsync

Modifica um repositório de vetores existente de forma assíncrona.

```csharp
public Task<VectorStoreResponse> ModifyVectorStoreAsync(string vectorStoreId, 
    VectorStoreModifyRequest vectorStoreModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| vectorStoreId | String | O ID do repositório de vetores a ser modificado. |
| vectorStoreModifyRequest | VectorStoreModifyRequest | O objeto de solicitação contendo os detalhes da modificação. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém a resposta da modificação do repositório de vetores.

### Exceções

| exceção | condição |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID do repositório de vetores é nulo ou vazio. |

### Veja Também

* classe [VectorStoreResponse](../../vectorstoreresponse/)
* classe [VectorStoreModifyRequest](../../vectorstoremodifyrequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)