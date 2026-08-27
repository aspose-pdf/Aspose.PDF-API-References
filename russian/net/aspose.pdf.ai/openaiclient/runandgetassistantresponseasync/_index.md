---
title: "OpenAIClient.RunAndGetAssistantResponseAsync"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод OpenAIClient. Запускает помощника с указанным threadId и runCreateRequest и асинхронно получает ответ помощника"
type: docs
weight: 450
url: /ru/net/aspose.pdf.ai/openaiclient/runandgetassistantresponseasync/
---
## OpenAIClient.RunAndGetAssistantResponseAsync method

Запускает помощника с указанным threadId и runCreateRequest и асинхронно получает ответ помощника.

```csharp
public Task<string> RunAndGetAssistantResponseAsync(string threadId, 
    RunCreateRequest runCreateRequest, CancellationToken? cancellationToken)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| threadId | String | Идентификатор потока. |
| runCreateRequest | RunCreateRequest | Запрос создания выполнения. |
| cancellationToken | Nullable`1 | Токен отмены (необязательно). |

### Возвращаемое значение

Задача, представляющая асинхронную операцию со строкой ответа помощника.

### См. также

* class [RunCreateRequest](../../runcreaterequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


