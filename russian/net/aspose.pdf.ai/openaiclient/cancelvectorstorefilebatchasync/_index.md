---
title: OpenAIClient.CancelVectorStoreFileBatchAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод OpenAIClient. Асинхронно отменяет конкретную партию файлов в векторном хранилище
type: docs
weight: 20
url: /ru/net/aspose.pdf.ai/openaiclient/cancelvectorstorefilebatchasync/
---
## Метод OpenAIClient.CancelVectorStoreFileBatchAsync

Асинхронно отменяет конкретную партию файлов в векторном хранилище.

```csharp
public Task<VectorStoreFileBatchResponse> CancelVectorStoreFileBatchAsync(string vectorStoreId, 
    string fileBatchId, CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| vectorStoreId | String | Идентификатор векторного хранилища, содержащего партию файлов для отмены. |
| fileBatchId | String | Идентификатор партии файлов для отмены. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит ответ на отмену партии файлов.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор векторного хранилища равен null или пуст. |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор партии файлов в векторном хранилище равен null или пуст. |

### См. также

* класс [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* класс [OpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)