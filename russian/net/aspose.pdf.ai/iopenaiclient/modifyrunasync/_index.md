---
title: "IOpenAIClient.ModifyRunAsync"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод IOpenAIClient. Изменяет существующий запуск в потоке асинхронно"
type: docs
weight: 370
url: /ru/net/aspose.pdf.ai/iopenaiclient/modifyrunasync/
---
## IOpenAIClient.ModifyRunAsync method

Изменяет существующий запуск в потоке асинхронно.

```csharp
public Task<RunResponse> ModifyRunAsync(string threadId, string runId, 
    RunModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| threadId | String | Идентификатор потока, содержащего запуск. |
| runId | String | Идентификатор запуска, который нужно изменить. |
| assistantModifyRequest | RunModifyRequest | Подробности запроса для изменения запуска. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит ответ от изменения запуска.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор потока равен null или пустой строке. |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор запуска равен null или пуст. |

### См. также

* class [RunResponse](../../runresponse/)
* class [RunModifyRequest](../../runmodifyrequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


