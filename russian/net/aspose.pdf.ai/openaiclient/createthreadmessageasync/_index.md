---
title: OpenAIClient.CreateThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод OpenAIClient. Асинхронно создает новое сообщение в потоке
type: docs
weight: 80
url: /ru/net/aspose.pdf.ai/openaiclient/createthreadmessageasync/
---
## Метод OpenAIClient.CreateThreadMessageAsync

Асинхронно создает новое сообщение в потоке.

```csharp
public Task<ThreadMessageResponse> CreateThreadMessageAsync(string threadId, 
    ThreadMessageCreateRequest threadMessageRequest, CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| threadId | String | Идентификатор потока, в котором будет создано сообщение. |
| threadMessageRequest | ThreadMessageCreateRequest | Подробности запроса для создания сообщения. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит ответ на создание сообщения.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор потока равен null или пуст. |

### См. также

* класс [ThreadMessageResponse](../../threadmessageresponse/)
* класс [ThreadMessageCreateRequest](../../threadmessagecreaterequest/)
* класс [OpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)