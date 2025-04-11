---
title: IOpenAIClient.GetRunStepsAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод IOpenAIClient. Асинхронно извлекает список шагов для конкретного выполнения в потоке
type: docs
weight: 260
url: /ru/net/aspose.pdf.ai/iopenaiclient/getrunstepsasync/
---
## Метод IOpenAIClient.GetRunStepsAsync

Асинхронно извлекает список шагов для конкретного выполнения в потоке.

```csharp
public Task<RunStepListResponse> GetRunStepsAsync(string threadId, string runId, 
    RunStepListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| threadId | String | Идентификатор потока, содержащего выполнение. |
| runId | String | Идентификатор выполнения, из которого нужно извлечь шаги. |
| queryParameters | RunStepListQueryParameters | Необязательные параметры запроса для фильтрации списка шагов выполнения. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит список шагов выполнения.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор потока равен null или пуст. |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор выполнения равен null или пуст. |

### См. также

* класс [RunStepListResponse](../../runsteplistresponse/)
* класс [RunStepListQueryParameters](../../runsteplistqueryparameters/)
* интерфейс [IOpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)