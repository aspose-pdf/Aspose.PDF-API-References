---
title: IOpenAIClient.ModifyThreadAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод IOpenAIClient. Асинхронно изменяет существующий поток
type: docs
weight: 380
url: /ru/net/aspose.pdf.ai/iopenaiclient/modifythreadasync/
---
## Метод IOpenAIClient.ModifyThreadAsync

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
* интерфейс [IOpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)