---
title: OpenAIClient.GetRunsAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод OpenAIClient. Асинхронно извлекает список запусков для указанного потока
type: docs
weight: 260
url: /ru/net/aspose.pdf.ai/openaiclient/getrunsasync/
---
## Метод OpenAIClient.GetRunsAsync

Асинхронно извлекает список запусков для указанного потока.

```csharp
public Task<RunListResponse> GetRunsAsync(string threadId, 
    RunListQueryParameters queryParameters = null, CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| threadId | String | Идентификатор потока, из которого нужно извлечь запуски. |
| queryParameters | RunListQueryParameters | Необязательные параметры запроса для фильтрации списка запусков. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит список запусков.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор потока равен null или пустой. |

### См. также

* класс [RunListResponse](../../runlistresponse/)
* класс [RunListQueryParameters](../../runlistqueryparameters/)
* класс [OpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)