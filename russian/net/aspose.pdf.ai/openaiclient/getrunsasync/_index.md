---
title: "OpenAIClient.GetRunsAsync"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод OpenAIClient. Получает список запусков для указанного потока асинхронно"
type: docs
weight: 270
url: /ru/net/aspose.pdf.ai/openaiclient/getrunsasync/
---
## OpenAIClient.GetRunsAsync method

Получает список запусков для указанного потока асинхронно.

```csharp
public Task<RunListResponse> GetRunsAsync(string threadId, 
    RunListQueryParameters queryParameters = null, CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| threadId | String | Идентификатор потока, из которого нужно получить запуски. |
| queryParameters | RunListQueryParameters | Необязательные параметры запроса для фильтрации списка запусков. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит список запусков.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор потока равен null или пустой строке. |

### См. также

* class [RunListResponse](../../runlistresponse/)
* class [RunListQueryParameters](../../runlistqueryparameters/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


