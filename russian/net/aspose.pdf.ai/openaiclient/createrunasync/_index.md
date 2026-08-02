---
title: "OpenAIClient.CreateRunAsync"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод OpenAIClient. Создаёт запуск в указанном потоке асинхронно"
type: docs
weight: 50
url: /ru/net/aspose.pdf.ai/openaiclient/createrunasync/
---
## OpenAIClient.CreateRunAsync method

Создает запуск в указанном потоке асинхронно.

```csharp
public Task<RunResponse> CreateRunAsync(string threadId, RunCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| threadId | String | Идентификатор потока, в котором будет создан запуск. |
| runCreateRequest | RunCreateRequest | Подробности запроса для создания запуска. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит ответ от создания запуска.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор потока равен null или пустой строке. |

### См. также

* class [RunResponse](../../runresponse/)
* class [RunCreateRequest](../../runcreaterequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


