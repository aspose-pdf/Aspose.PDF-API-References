---
title: OpenAIClient.CreateCompletionAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод OpenAIClient. Создает новое завершение асинхронно
type: docs
weight: 40
url: /ru/net/aspose.pdf.ai/openaiclient/createcompletionasync/
---
## Метод OpenAIClient.CreateCompletionAsync

Создает новое завершение асинхронно.

```csharp
public Task<CompletionResponse> CreateCompletionAsync(
    CompletionCreateRequest completionCreateRequest, CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| completionCreateRequest | CompletionCreateRequest | Объект запроса, содержащий детали для создания завершения. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит ответ от создания завершения.

### См. также

* класс [CompletionResponse](../../completionresponse/)
* класс [CompletionCreateRequest](../../completioncreaterequest/)
* класс [OpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)