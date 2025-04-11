---
title: IOpenAIClient.ModifyRunAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод IOpenAIClient. Асинхронно изменяет существующий запуск в потоке
type: docs
weight: 370
url: /ru/net/aspose.pdf.ai/iopenaiclient/modifyrunasync/
---
## Метод IOpenAIClient.ModifyRunAsync

Асинхронно изменяет существующий запуск в потоке.

```csharp
public Task<RunResponse> ModifyRunAsync(string threadId, string runId, 
    RunModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| threadId | String | Идентификатор потока, содержащего запуск. |
| runId | String | Идентификатор запуска для изменения. |
| assistantModifyRequest | RunModifyRequest | Подробности запроса для изменения запуска. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит ответ на изменение запуска.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор потока равен null или пуст. |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор запуска равен null или пуст. |

### См. также

* класс [RunResponse](../../runresponse/)
* класс [RunModifyRequest](../../runmodifyrequest/)
* интерфейс [IOpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)