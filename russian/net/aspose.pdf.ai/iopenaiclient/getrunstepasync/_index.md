---
title: IOpenAIClient.GetRunStepAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод IOpenAIClient. Асинхронно извлекает детали конкретного шага в рамках выполнения
type: docs
weight: 250
url: /ru/net/aspose.pdf.ai/iopenaiclient/getrunstepasync/
---
## Метод IOpenAIClient.GetRunStepAsync

Асинхронно извлекает детали конкретного шага в рамках выполнения.

```csharp
public Task<RunStepResponse> GetRunStepAsync(string threadId, string runId, string runStepId, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| threadId | String | Идентификатор потока, содержащего выполнение. |
| runId | String | Идентификатор выполнения, содержащего шаг. |
| runStepId | String | Идентификатор шага выполнения для извлечения. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит детали шага выполнения.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор потока равен null или пуст. |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор выполнения равен null или пуст. |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор шага выполнения равен null или пуст. |

### См. также

* класс [RunStepResponse](../../runstepresponse/)
* интерфейс [IOpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)