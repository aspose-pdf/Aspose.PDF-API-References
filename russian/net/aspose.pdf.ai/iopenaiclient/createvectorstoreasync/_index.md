---
title: IOpenAIClient.CreateVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод IOpenAIClient. Создает новый векторный магазин асинхронно
type: docs
weight: 100
url: /ru/net/aspose.pdf.ai/iopenaiclient/createvectorstoreasync/
---
## Метод IOpenAIClient.CreateVectorStoreAsync

Создает новый векторный магазин асинхронно.

```csharp
public Task<VectorStoreResponse> CreateVectorStoreAsync(
    VectorStoreCreateRequest vectorStoreCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| vectorStoreCreateRequest | VectorStoreCreateRequest | Объект запроса, содержащий детали для создания векторного магазина. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит ответ на создание векторного магазина.

### См. также

* класс [VectorStoreResponse](../../vectorstoreresponse/)
* класс [VectorStoreCreateRequest](../../vectorstorecreaterequest/)
* интерфейс [IOpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)