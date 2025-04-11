---
title: IOpenAIClient.CreateAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод IOpenAIClient. Создает нового ассистента асинхронно
type: docs
weight: 30
url: /ru/net/aspose.pdf.ai/iopenaiclient/createassistantasync/
---
## Метод IOpenAIClient.CreateAssistantAsync

Создает нового ассистента асинхронно.

```csharp
public Task<AssistantResponse> CreateAssistantAsync(AssistantCreateRequest assistantCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| assistantCreateRequest | AssistantCreateRequest | Объект запроса, содержащий детали для создания ассистента. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит ответ от создания ассистента.

### См. также

* класс [AssistantResponse](../../assistantresponse/)
* класс [AssistantCreateRequest](../../assistantcreaterequest/)
* интерфейс [IOpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)