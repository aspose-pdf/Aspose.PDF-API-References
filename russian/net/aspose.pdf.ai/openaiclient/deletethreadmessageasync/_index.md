---
title: "OpenAIClient.DeleteThreadMessageAsync"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод OpenAIClient. Асинхронно удаляет сообщение в потоке."
type: docs
weight: 160
url: /ru/net/aspose.pdf.ai/openaiclient/deletethreadmessageasync/
---
## OpenAIClient.DeleteThreadMessageAsync method

Удаляет сообщение в потоке асинхронно.

```csharp
public Task<DeleteStatusResponse> DeleteThreadMessageAsync(string threadId, string threadMessageId, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| threadId | String | Идентификатор потока, содержащего сообщение для удаления. |
| threadMessageId | String | Идентификатор сообщения для удаления. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит статус операции удаления.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор потока равен null или пустой строке. |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор сообщения потока равен null или пуст. |

### См. также

* class [DeleteStatusResponse](../../deletestatusresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


