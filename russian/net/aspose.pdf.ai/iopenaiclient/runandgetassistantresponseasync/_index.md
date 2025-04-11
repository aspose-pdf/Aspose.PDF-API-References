---
title: IOpenAIClient.RunAndGetAssistantResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод IOpenAIClient. Запускает помощника с указанным threadId и runCreateRequest и асинхронно получает ответ помощника
type: docs
weight: 410
url: /ru/net/aspose.pdf.ai/iopenaiclient/runandgetassistantresponseasync/
---
## Метод IOpenAIClient.RunAndGetAssistantResponseAsync

Запускает помощника с указанным threadId и runCreateRequest и асинхронно получает ответ помощника.

```csharp
public Task<string> RunAndGetAssistantResponseAsync(string threadId, 
    RunCreateRequest runCreateRequest, CancellationToken? cancellationToken)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| threadId | String | Идентификатор потока. |
| runCreateRequest | RunCreateRequest | Запрос на создание запуска. |
| cancellationToken | Nullable`1 | Токен отмены (необязательно). |

### Возвращаемое значение

Задача, представляющая асинхронную операцию с строкой ответа помощника.

### См. также

* класс [RunCreateRequest](../../runcreaterequest/)
* интерфейс [IOpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)