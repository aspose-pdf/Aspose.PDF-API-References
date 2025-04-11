---
title: IOpenAIClient.CreateVectorStoreAndWaitToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод IOpenAIClient. Создает новый векторный магазин и ждет его завершения асинхронно
type: docs
weight: 90
url: /ru/net/aspose.pdf.ai/iopenaiclient/createvectorstoreandwaittocompleteasync/
---
## Метод IOpenAIClient.CreateVectorStoreAndWaitToCompleteAsync

Создает новый векторный магазин и ждет его завершения асинхронно.

```csharp
public Task<VectorStoreResponse> CreateVectorStoreAndWaitToCompleteAsync(
    VectorStoreCreateRequest vectorStoreCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| vectorStoreCreateRequest | VectorStoreCreateRequest | Объект запроса, содержащий детали для создания векторного магазина. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит ответ от создания векторного магазина после завершения.

### См. также

* класс [VectorStoreResponse](../../vectorstoreresponse/)
* класс [VectorStoreCreateRequest](../../vectorstorecreaterequest/)
* интерфейс [IOpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)