---
title: OpenAIClient.WaitForAssistantMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод OpenAIClient. Ожидает первое сообщение от помощника в потоке асинхронно
type: docs
weight: 460
url: /ru/net/aspose.pdf.ai/openaiclient/waitforassistantmessageasync/
---
## Метод OpenAIClient.WaitForAssistantMessageAsync

Ожидает первое сообщение от помощника в потоке асинхронно.

```csharp
public Task<ThreadMessageResponse> WaitForAssistantMessageAsync(string threadId, 
    ThreadMessageListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| threadId | String | Идентификатор потока, который нужно отслеживать для первого сообщения помощника. |
| queryParameters | ThreadMessageListQueryParameters | Необязательные параметры запроса для фильтрации списка сообщений. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит первое сообщение помощника в потоке.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор потока равен null или пустой. |

### См. также

* класс [ThreadMessageResponse](../../threadmessageresponse/)
* класс [ThreadMessageListQueryParameters](../../threadmessagelistqueryparameters/)
* класс [OpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)