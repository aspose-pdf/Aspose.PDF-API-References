---
title: IOpenAIClient.CreateVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Cria um novo armazenamento de vetores de forma assíncrona
type: docs
weight: 100
url: /pt/net/aspose.pdf.ai/iopenaiclient/createvectorstoreasync/
---
## Método IOpenAIClient.CreateVectorStoreAsync

Cria um novo armazenamento de vetores de forma assíncrona.

```csharp
public Task<VectorStoreResponse> CreateVectorStoreAsync(
    VectorStoreCreateRequest vectorStoreCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| vectorStoreCreateRequest | VectorStoreCreateRequest | O objeto de solicitação contendo detalhes para criar o armazenamento de vetores. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém a resposta da criação do armazenamento de vetores.

### Veja Também

* classe [VectorStoreResponse](../../vectorstoreresponse/)
* classe [VectorStoreCreateRequest](../../vectorstorecreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)