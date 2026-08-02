---
title: "OpenAIClient.GetRunAsync"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод OpenAIClient. Асинхронно получает детали конкретного выполнения в потоке."
type: docs
weight: 260
url: /ru/net/aspose.pdf.ai/openaiclient/getrunasync/
---
## OpenAIClient.GetRunAsync method

Получает детали конкретного запуска в потоке асинхронно.

```csharp
public Task<RunResponse> GetRunAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| threadId | String | Идентификатор потока, содержащего запуск. |
| runId | String | Идентификатор выполнения для получения. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит детали выполнения.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор потока равен null или пустой строке. |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор запуска равен null или пуст. |

### См. также

* class [RunResponse](../../runresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


