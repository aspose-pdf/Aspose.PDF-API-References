---
title: "OpenAIClient.WaitForAssistantMessageAsync"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод OpenAIClient. Ожидает первое сообщение от помощника в потоке асинхронно"
type: docs
weight: 470
url: /ru/net/aspose.pdf.ai/openaiclient/waitforassistantmessageasync/
---
## OpenAIClient.WaitForAssistantMessageAsync method

Ожидает первое сообщение от помощника в потоке асинхронно.

```csharp
public Task<ThreadMessageResponse> WaitForAssistantMessageAsync(string threadId, 
    ThreadMessageListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| threadId | String | Идентификатор потока, в котором следует отслеживать первое сообщение помощника. |
| queryParameters | ThreadMessageListQueryParameters | Необязательные параметры запроса для фильтрации списка сообщений. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит первое сообщение помощника в потоке.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор потока равен null или пустой строке. |

### См. также

* class [ThreadMessageResponse](../../threadmessageresponse/)
* class [ThreadMessageListQueryParameters](../../threadmessagelistqueryparameters/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


