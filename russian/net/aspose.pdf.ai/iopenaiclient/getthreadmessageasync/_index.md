---
title: "IOpenAIClient.GetThreadMessageAsync"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод IOpenAIClient. Получает детали конкретного сообщения в потоке асинхронно"
type: docs
weight: 280
url: /ru/net/aspose.pdf.ai/iopenaiclient/getthreadmessageasync/
---
## IOpenAIClient.GetThreadMessageAsync method

Получает детали конкретного сообщения в потоке асинхронно.

```csharp
public Task<ThreadMessageResponse> GetThreadMessageAsync(string threadId, string threadMessageId, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| threadId | String | Идентификатор потока, содержащего сообщение. |
| threadMessageId | String | Идентификатор сообщения для получения. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит детали сообщения потока.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор потока равен null или пустой строке. |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор сообщения потока равен null или пуст. |

### См. также

* class [ThreadMessageResponse](../../threadmessageresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


