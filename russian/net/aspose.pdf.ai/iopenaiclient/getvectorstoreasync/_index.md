---
title: IOpenAIClient.GetVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод IOpenAIClient. Асинхронно извлекает детали конкретного векторного хранилища
type: docs
weight: 300
url: /ru/net/aspose.pdf.ai/iopenaiclient/getvectorstoreasync/
---
## Метод IOpenAIClient.GetVectorStoreAsync

Асинхронно извлекает детали конкретного векторного хранилища.

```csharp
public Task<VectorStoreResponse> GetVectorStoreAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| vectorStoreId | String | Идентификатор векторного хранилища для извлечения. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит детали векторного хранилища.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор векторного хранилища равен null или пуст. |

### См. также

* класс [VectorStoreResponse](../../vectorstoreresponse/)
* интерфейс [IOpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)