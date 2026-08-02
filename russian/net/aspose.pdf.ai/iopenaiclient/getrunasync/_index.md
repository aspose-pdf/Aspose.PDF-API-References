---
title: "IOpenAIClient.GetRunAsync"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод IOpenAIClient. Асинхронно получает детали конкретного запуска в потоке."
type: docs
weight: 230
url: /ru/net/aspose.pdf.ai/iopenaiclient/getrunasync/
---
## IOpenAIClient.GetRunAsync method

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
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


