---
title: IOpenAIClient.GetVectorStoresAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Recupera uma lista de lojas de vetores de forma assíncrona
type: docs
weight: 350
url: /pt/net/aspose.pdf.ai/iopenaiclient/getvectorstoresasync/
---
## Método IOpenAIClient.GetVectorStoresAsync

Recupera uma lista de lojas de vetores de forma assíncrona.

```csharp
public Task<VectorStoreListResponse> GetVectorStoresAsync(
    VectorStoreListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| queryParameters | VectorStoreListQueryParameters | Parâmetros de consulta opcionais para filtrar a lista de lojas de vetores. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém uma lista de lojas de vetores.

### Veja Também

* classe [VectorStoreListResponse](../../vectorstorelistresponse/)
* classe [VectorStoreListQueryParameters](../../vectorstorelistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)