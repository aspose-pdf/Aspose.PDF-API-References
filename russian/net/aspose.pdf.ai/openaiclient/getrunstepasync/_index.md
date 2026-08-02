---
title: "OpenAIClient.GetRunStepAsync"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод OpenAIClient. Асинхронно получает детали конкретного шага в запуске."
type: docs
weight: 280
url: /ru/net/aspose.pdf.ai/openaiclient/getrunstepasync/
---
## OpenAIClient.GetRunStepAsync method

Получает детали конкретного шага в запуске асинхронно.

```csharp
public Task<RunStepResponse> GetRunStepAsync(string threadId, string runId, string runStepId, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| threadId | String | Идентификатор потока, содержащего запуск. |
| runId | String | Идентификатор запуска, содержащего шаг. |
| runStepId | String | Идентификатор шага запуска, который нужно получить. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит детали шага запуска.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор потока равен null или пустой строке. |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор запуска равен null или пуст. |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор шага запуска равен null или пуст. |

### См. также

* class [RunStepResponse](../../runstepresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


