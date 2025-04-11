---
title: IOpenAIClient.CreateRunAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод IOpenAIClient. Создает выполнение в указанном потоке асинхронно
type: docs
weight: 50
url: /ru/net/aspose.pdf.ai/iopenaiclient/createrunasync/
---
## Метод IOpenAIClient.CreateRunAsync

Создает выполнение в указанном потоке асинхронно.

```csharp
public Task<RunResponse> CreateRunAsync(string threadId, RunCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| threadId | String | Идентификатор потока, в котором будет создано выполнение. |
| runCreateRequest | RunCreateRequest | Подробности запроса для создания выполнения. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит ответ на создание выполнения.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор потока равен null или пуст. |

### См. также

* класс [RunResponse](../../runresponse/)
* класс [RunCreateRequest](../../runcreaterequest/)
* интерфейс [IOpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)