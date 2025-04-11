---
title: IOpenAIClient.WaitForAssistantMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод IOpenAIClient. Ожидает первое сообщение от помощника в потоке асинхронно
type: docs
weight: 430
url: /ru/net/aspose.pdf.ai/iopenaiclient/waitforassistantmessageasync/
---
## Метод IOpenAIClient.WaitForAssistantMessageAsync

Ожидает первое сообщение от помощника в потоке асинхронно.

```csharp
public Task<ThreadMessageResponse> WaitForAssistantMessageAsync(string threadId, 
    ThreadMessageListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| threadId | String | Идентификатор потока для мониторинга первого сообщения помощника. |
| queryParameters | ThreadMessageListQueryParameters | Необязательные параметры запроса для фильтрации списка сообщений. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит первое сообщение помощника в потоке.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор потока равен null или пуст. |

### См. также

* класс [ThreadMessageResponse](../../threadmessageresponse/)
* класс [ThreadMessageListQueryParameters](../../threadmessagelistqueryparameters/)
* интерфейс [IOpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)