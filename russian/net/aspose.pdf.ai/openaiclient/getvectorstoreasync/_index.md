---
title: OpenAIClient.GetVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод OpenAIClient. Асинхронно извлекает детали конкретного векторного хранилища
type: docs
weight: 330
url: /ru/net/aspose.pdf.ai/openaiclient/getvectorstoreasync/
---
## Метод OpenAIClient.GetVectorStoreAsync

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
* класс [OpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)