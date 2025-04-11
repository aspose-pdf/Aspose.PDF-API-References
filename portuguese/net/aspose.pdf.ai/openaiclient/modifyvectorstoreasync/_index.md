---
title: OpenAIClient.ModifyVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Modifica um armazenamento de vetor existente de forma assíncrona
type: docs
weight: 430
url: /pt/net/aspose.pdf.ai/openaiclient/modifyvectorstoreasync/
---
## Método OpenAIClient.ModifyVectorStoreAsync

Modifica um armazenamento de vetor existente de forma assíncrona.

```csharp
public Task<VectorStoreResponse> ModifyVectorStoreAsync(string vectorStoreId, 
    VectorStoreModifyRequest vectorStoreModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| vectorStoreId | String | O ID do armazenamento de vetor a ser modificado. |
| vectorStoreModifyRequest | VectorStoreModifyRequest | O objeto de solicitação contendo os detalhes da modificação. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém a resposta da modificação do armazenamento de vetor.

### Exceções

| exceção | condição |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID do armazenamento de vetor é nulo ou vazio. |

### Veja Também

* classe [VectorStoreResponse](../../vectorstoreresponse/)
* classe [VectorStoreModifyRequest](../../vectorstoremodifyrequest/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)