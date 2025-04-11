---
title: OpenAIClient.CreateVectorStoreAndWaitToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Cria um novo armazenamento de vetores e aguarda sua conclusão de forma assíncrona
type: docs
weight: 90
url: /pt/net/aspose.pdf.ai/openaiclient/createvectorstoreandwaittocompleteasync/
---
## Método OpenAIClient.CreateVectorStoreAndWaitToCompleteAsync

Cria um novo armazenamento de vetores e aguarda sua conclusão de forma assíncrona.

```csharp
public Task<VectorStoreResponse> CreateVectorStoreAndWaitToCompleteAsync(
    VectorStoreCreateRequest vectorStoreCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| vectorStoreCreateRequest | VectorStoreCreateRequest | O objeto de solicitação contendo detalhes para criar o armazenamento de vetores. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém a resposta da criação do armazenamento de vetores após a conclusão.

### Veja Também

* classe [VectorStoreResponse](../../vectorstoreresponse/)
* classe [VectorStoreCreateRequest](../../vectorstorecreaterequest/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)