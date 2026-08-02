---
title: "OpenAIClient.GetRunStepsAsync"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод OpenAIClient. Асинхронно получает список шагов для конкретного выполнения в потоке"
type: docs
weight: 290
url: /ru/net/aspose.pdf.ai/openaiclient/getrunstepsasync/
---
## OpenAIClient.GetRunStepsAsync method

Получает список шагов для конкретного запуска в потоке асинхронно.

```csharp
public Task<RunStepListResponse> GetRunStepsAsync(string threadId, string runId, 
    RunStepListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| threadId | String | Идентификатор потока, содержащего запуск. |
| runId | String | Идентификатор выполнения, из которого получать шаги. |
| queryParameters | RunStepListQueryParameters | Необязательные параметры запроса для фильтрации списка шагов выполнения. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит список шагов выполнения.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор потока равен null или пустой строке. |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор запуска равен null или пуст. |

### См. также

* class [RunStepListResponse](../../runsteplistresponse/)
* class [RunStepListQueryParameters](../../runsteplistqueryparameters/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


