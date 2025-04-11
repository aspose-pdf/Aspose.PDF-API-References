---
title: IOpenAIClient.GetThreadMessagesAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод IOpenAIClient. Асинхронно извлекает список сообщений для конкретной темы
type: docs
weight: 290
url: /ru/net/aspose.pdf.ai/iopenaiclient/getthreadmessagesasync/
---
## Метод IOpenAIClient.GetThreadMessagesAsync

Асинхронно извлекает список сообщений для конкретной темы.

```csharp
public Task<ThreadMessageListResponse> GetThreadMessagesAsync(string threadId, 
    ThreadMessageListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| threadId | String | Идентификатор темы, из которой нужно извлечь сообщения. |
| queryParameters | ThreadMessageListQueryParameters | Необязательные параметры запроса для фильтрации списка сообщений. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит список сообщений темы.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор темы равен null или пуст. |

### См. также

* класс [ThreadMessageListResponse](../../threadmessagelistresponse/)
* класс [ThreadMessageListQueryParameters](../../threadmessagelistqueryparameters/)
* интерфейс [IOpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)