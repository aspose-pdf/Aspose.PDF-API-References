---
title: "OpenAIClient.GetThreadMessageAsync"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод OpenAIClient. Асинхронно получает детали конкретного сообщения в потоке"
type: docs
weight: 320
url: /ru/net/aspose.pdf.ai/openaiclient/getthreadmessageasync/
---
## OpenAIClient.GetThreadMessageAsync method

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
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


