---
title: IOpenAIClient.DeleteThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод IOpenAIClient. Удаляет сообщение в потоке асинхронно
type: docs
weight: 160
url: /ru/net/aspose.pdf.ai/iopenaiclient/deletethreadmessageasync/
---
## Метод IOpenAIClient.DeleteThreadMessageAsync

Удаляет сообщение в потоке асинхронно.

```csharp
public Task<DeleteStatusResponse> DeleteThreadMessageAsync(string threadId, string threadMessageId, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| threadId | String | Идентификатор потока, содержащего сообщение для удаления. |
| threadMessageId | String | Идентификатор сообщения для удаления. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит статус операции удаления.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор потока равен null или пуст. |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор сообщения потока равен null или пуст. |

### См. также

* класс [DeleteStatusResponse](../../deletestatusresponse/)
* интерфейс [IOpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)