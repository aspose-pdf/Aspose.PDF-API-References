---
title: OpenAIClient.GetVectorStoresAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод OpenAIClient. Асинхронно извлекает список векторных хранилищ
type: docs
weight: 380
url: /ru/net/aspose.pdf.ai/openaiclient/getvectorstoresasync/
---
## Метод OpenAIClient.GetVectorStoresAsync

Асинхронно извлекает список векторных хранилищ.

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

* класс [VectorStoreListResponse](../../vectorstorelistresponse/)
* класс [VectorStoreListQueryParameters](../../vectorstorelistqueryparameters/)
* класс [OpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)