---
title: OpenAIClient.WaitForVectorStoreToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод OpenAIClient. Ожидает, пока конкретное хранилище векторов завершится асинхронно
type: docs
weight: 500
url: /ru/net/aspose.pdf.ai/openaiclient/waitforvectorstoretocompleteasync/
---
## Метод OpenAIClient.WaitForVectorStoreToCompleteAsync

Ожидает, пока конкретное хранилище векторов завершится асинхронно.

```csharp
public Task<VectorStoreResponse> WaitForVectorStoreToCompleteAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| vectorStoreId | String | Идентификатор хранилища векторов, который нужно отслеживать до завершения. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит окончательный статус хранилища векторов.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор хранилища векторов равен null или пуст. |

### См. также

* класс [VectorStoreResponse](../../vectorstoreresponse/)
* класс [OpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)