---
title: OpenAIClient.DeleteThreadAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод OpenAIClient. Удаляет существующий поток асинхронно
type: docs
weight: 150
url: /ru/net/aspose.pdf.ai/openaiclient/deletethreadasync/
---
## Метод OpenAIClient.DeleteThreadAsync

Удаляет существующий поток асинхронно.

```csharp
public Task<DeleteStatusResponse> DeleteThreadAsync(string threadId, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| threadId | String | Идентификатор потока для удаления. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит статус операции удаления.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор потока равен null или пуст. |

### См. также

* класс [DeleteStatusResponse](../../deletestatusresponse/)
* класс [OpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)