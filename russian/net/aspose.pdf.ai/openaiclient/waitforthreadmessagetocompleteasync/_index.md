---
title: "OpenAIClient.WaitForThreadMessageToCompleteAsync"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод OpenAIClient. Асинхронно ожидает завершения конкретного сообщения потока."
type: docs
weight: 490
url: /ru/net/aspose.pdf.ai/openaiclient/waitforthreadmessagetocompleteasync/
---
## OpenAIClient.WaitForThreadMessageToCompleteAsync method

Ожидает завершения конкретного сообщения потока асинхронно.

```csharp
public Task<ThreadMessageResponse> WaitForThreadMessageToCompleteAsync(string threadId, 
    string threadMessageId, CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| threadId | String | Идентификатор потока, содержащего сообщение. |
| threadMessageId | String | Идентификатор сообщения, которое следует отслеживать до завершения. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит окончательный статус сообщения.

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


