---
title: "IOpenAIClient.GetVectorStoresAsync"
second_title: "Справочник API Aspose.PDF для .NET"
description: "IOpenAIClient метод. Асинхронно получает список векторных хранилищ."
type: docs
weight: 350
url: /ru/net/aspose.pdf.ai/iopenaiclient/getvectorstoresasync/
---
## IOpenAIClient.GetVectorStoresAsync method

Получает список векторных хранилищ асинхронно.

```csharp
public Task<VectorStoreListResponse> GetVectorStoresAsync(
    VectorStoreListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| queryParameters | VectorStoreListQueryParameters | Необязательные параметры запроса для фильтрации списка векторных хранилищ. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит список векторных хранилищ.

### См. также

* class [VectorStoreListResponse](../../vectorstorelistresponse/)
* class [VectorStoreListQueryParameters](../../vectorstorelistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


