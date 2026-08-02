---
title: "OpenAIClient.GetThreadMessagesAsync"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод OpenAIClient. Асинхронно получает список сообщений для конкретного потока."
type: docs
weight: 330
url: /ru/net/aspose.pdf.ai/openaiclient/getthreadmessagesasync/
---
## OpenAIClient.GetThreadMessagesAsync method

Получает список сообщений для конкретного потока асинхронно.

```csharp
public Task<ThreadMessageListResponse> GetThreadMessagesAsync(string threadId, 
    ThreadMessageListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| threadId | String | Идентификатор потока, из которого нужно получить сообщения. |
| queryParameters | ThreadMessageListQueryParameters | Необязательные параметры запроса для фильтрации списка сообщений. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит список сообщений потока.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор потока равен null или пустой строке. |

### См. также

* class [ThreadMessageListResponse](../../threadmessagelistresponse/)
* class [ThreadMessageListQueryParameters](../../threadmessagelistqueryparameters/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


