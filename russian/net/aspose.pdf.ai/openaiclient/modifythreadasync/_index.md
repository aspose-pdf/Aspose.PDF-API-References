---
title: OpenAIClient.ModifyThreadAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод OpenAIClient. Асинхронно изменяет существующий поток
type: docs
weight: 410
url: /ru/net/aspose.pdf.ai/openaiclient/modifythreadasync/
---
## Метод OpenAIClient.ModifyThreadAsync

Асинхронно изменяет существующий поток.

```csharp
public Task<ThreadResponse> ModifyThreadAsync(string threadId, 
    ThreadModifyRequest threadModifyRequest, CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| threadId | String | Идентификатор потока для изменения. |
| threadModifyRequest | ThreadModifyRequest | Объект запроса, содержащий детали изменения. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит ответ на изменение потока.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор потока равен null или пуст. |

### См. также

* класс [ThreadResponse](../../threadresponse/)
* класс [ThreadModifyRequest](../../threadmodifyrequest/)
* класс [OpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)