---
title: "IOpenAIClient.WaitForAssistantMessageAsync"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод IOpenAIClient. Асинхронно ожидает первое сообщение от помощника в потоке"
type: docs
weight: 430
url: /ru/net/aspose.pdf.ai/iopenaiclient/waitforassistantmessageasync/
---
## IOpenAIClient.WaitForAssistantMessageAsync method

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
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


