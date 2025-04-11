---
title: OpenAIClient.RunAndGetAssistantResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод OpenAIClient. Запускает помощника с указанным threadId и runCreateRequest и асинхронно получает ответ помощника
type: docs
weight: 440
url: /ru/net/aspose.pdf.ai/openaiclient/runandgetassistantresponseasync/
---
## Метод OpenAIClient.RunAndGetAssistantResponseAsync

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
* класс [OpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)