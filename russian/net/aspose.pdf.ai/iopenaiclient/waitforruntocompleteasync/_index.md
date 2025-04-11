---
title: IOpenAIClient.WaitForRunToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод IOpenAIClient. Ожидает завершения выполнения в потоке асинхронно
type: docs
weight: 440
url: /ru/net/aspose.pdf.ai/iopenaiclient/waitforruntocompleteasync/
---
## Метод IOpenAIClient.WaitForRunToCompleteAsync

Ожидает завершения выполнения в потоке асинхронно.

```csharp
public Task<RunResponse> WaitForRunToCompleteAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| threadId | String | Идентификатор потока, содержащего выполнение. |
| runId | String | Идентификатор выполнения, который нужно отслеживать до завершения. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит окончательный статус выполнения.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор потока равен null или пуст. |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор выполнения равен null или пуст. |

### См. также

* класс [RunResponse](../../runresponse/)
* интерфейс [IOpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)