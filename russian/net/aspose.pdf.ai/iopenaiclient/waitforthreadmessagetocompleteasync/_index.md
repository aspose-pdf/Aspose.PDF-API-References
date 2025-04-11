---
title: IOpenAIClient.WaitForThreadMessageToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод IOpenAIClient. Ожидает завершения конкретного сообщения потока асинхронно
type: docs
weight: 450
url: /ru/net/aspose.pdf.ai/iopenaiclient/waitforthreadmessagetocompleteasync/
---
## Метод IOpenAIClient.WaitForThreadMessageToCompleteAsync

Ожидает завершения конкретного сообщения потока асинхронно.

```csharp
public Task<ThreadMessageResponse> WaitForThreadMessageToCompleteAsync(string threadId, 
    string threadMessageId, CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| threadId | String | Идентификатор потока, содержащего сообщение. |
| threadMessageId | String | Идентификатор сообщения, которое необходимо отслеживать до завершения. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит окончательный статус сообщения.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор потока равен null или пуст. |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор сообщения потока равен null или пуст. |

### См. также

* класс [ThreadMessageResponse](../../threadmessageresponse/)
* интерфейс [IOpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)