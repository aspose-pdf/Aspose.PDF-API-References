---
title: IOpenAIClient.ModifyVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод IOpenAIClient. Асинхронно изменяет существующий векторный магазин
type: docs
weight: 400
url: /ru/net/aspose.pdf.ai/iopenaiclient/modifyvectorstoreasync/
---
## Метод IOpenAIClient.ModifyVectorStoreAsync

Асинхронно изменяет существующий векторный магазин.

```csharp
public Task<VectorStoreResponse> ModifyVectorStoreAsync(string vectorStoreId, 
    VectorStoreModifyRequest vectorStoreModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| vectorStoreId | String | Идентификатор векторного магазина для изменения. |
| vectorStoreModifyRequest | VectorStoreModifyRequest | Объект запроса, содержащий детали изменения. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит ответ от изменения векторного магазина.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор векторного магазина равен null или пуст. |

### См. также

* класс [VectorStoreResponse](../../vectorstoreresponse/)
* класс [VectorStoreModifyRequest](../../vectorstoremodifyrequest/)
* интерфейс [IOpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)