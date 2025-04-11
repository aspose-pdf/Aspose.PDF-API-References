---
title: OpenAIClient.ModifyThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод OpenAIClient. Асинхронно изменяет существующее сообщение в потоке
type: docs
weight: 420
url: /ru/net/aspose.pdf.ai/openaiclient/modifythreadmessageasync/
---
## Метод OpenAIClient.ModifyThreadMessageAsync

Асинхронно изменяет существующее сообщение в потоке.

```csharp
public Task<ThreadMessageResponse> ModifyThreadMessageAsync(string threadId, 
    string threadMessageId, ThreadMessageModifyRequest threadMessageModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| threadId | String | Идентификатор потока, содержащего сообщение для изменения. |
| threadMessageId | String | Идентификатор сообщения для изменения. |
| threadMessageModifyRequest | ThreadMessageModifyRequest | Подробности запроса для изменения сообщения. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит ответ на изменение сообщения.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор потока равен null или пуст. |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор сообщения потока равен null или пуст. |

### См. также

* класс [ThreadMessageResponse](../../threadmessageresponse/)
* класс [ThreadMessageModifyRequest](../../threadmessagemodifyrequest/)
* класс [OpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)