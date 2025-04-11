---
title: OpenAIClient.ModifyAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод OpenAIClient. Асинхронно изменяет существующего помощника
type: docs
weight: 390
url: /ru/net/aspose.pdf.ai/openaiclient/modifyassistantasync/
---
## Метод OpenAIClient.ModifyAssistantAsync

Асинхронно изменяет существующего помощника.

```csharp
public Task<AssistantResponse> ModifyAssistantAsync(string assistantId, 
    AssistantModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| assistantId | String | Идентификатор помощника для изменения. |
| assistantModifyRequest | AssistantModifyRequest | Объект запроса, содержащий детали изменения. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит ответ на изменение помощника.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор помощника равен null или пуст. |

### См. также

* класс [AssistantResponse](../../assistantresponse/)
* класс [AssistantModifyRequest](../../assistantmodifyrequest/)
* класс [OpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)