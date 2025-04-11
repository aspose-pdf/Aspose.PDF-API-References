---
title: OpenAIClient.GetRunStepsAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод OpenAIClient. Асинхронно извлекает список шагов для определённого выполнения в рамках потока
type: docs
weight: 280
url: /ru/net/aspose.pdf.ai/openaiclient/getrunstepsasync/
---
## Метод OpenAIClient.GetRunStepsAsync

Асинхронно извлекает список шагов для определённого выполнения в рамках потока.

```csharp
public Task<RunStepListResponse> GetRunStepsAsync(string threadId, string runId, 
    RunStepListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Параметр          | Тип                                 | Описание                                                                           |
| ----------------- | ----------------------------------- | ---------------------------------------------------------------------------------- |
| threadId          | String                              | Идентификатор потока, содержащего выполнение.                                      |
| runId             | String                              | Идентификатор выполнения, из которого извлекаются шаги.                            |
| queryParameters   | RunStepListQueryParameters          | Необязательные параметры запроса для фильтрации списка шагов выполнения.            |
| cancellationToken | Nullable`1                         | Токен для отмены операции.                                                         |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит список шагов выполнения.

### Исключения

| исключение                              | условие                                                      |
| --------------------------------------- | ------------------------------------------------------------ |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор потока равен null или пустой. |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор выполнения равен null или пустой. |

### См. также

* класс [RunStepListResponse](../../runsteplistresponse/)
* класс [RunStepListQueryParameters](../../runsteplistqueryparameters/)
* класс [OpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)