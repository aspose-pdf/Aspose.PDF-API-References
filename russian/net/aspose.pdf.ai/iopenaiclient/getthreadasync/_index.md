---
title: IOpenAIClient.GetThreadAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод IOpenAIClient. Асинхронно извлекает детали конкретного потока
type: docs
weight: 270
url: /ru/net/aspose.pdf.ai/iopenaiclient/getthreadasync/
---
## Метод IOpenAIClient.GetThreadAsync

Асинхронно извлекает детали конкретного потока.

```csharp
public Task<ThreadResponse> GetThreadAsync(string threadId, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| threadId | String | Идентификатор потока для извлечения. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит детали потока.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор потока равен null или пуст. |

### См. также

* класс [ThreadResponse](../../threadresponse/)
* интерфейс [IOpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)