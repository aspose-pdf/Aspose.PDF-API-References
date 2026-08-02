---
title: "IOpenAIClient.CreateThreadMessageAsync"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод IOpenAIClient. Создаёт новое сообщение в потоке асинхронно"
type: docs
weight: 80
url: /ru/net/aspose.pdf.ai/iopenaiclient/createthreadmessageasync/
---
## IOpenAIClient.CreateThreadMessageAsync method

Создает новое сообщение в потоке асинхронно.

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

Задача, представляющая асинхронную операцию. Результат задачи содержит ответ от создания сообщения.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор потока равен null или пустой строке. |

### См. также

* class [ThreadMessageResponse](../../threadmessageresponse/)
* class [ThreadMessageCreateRequest](../../threadmessagecreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


