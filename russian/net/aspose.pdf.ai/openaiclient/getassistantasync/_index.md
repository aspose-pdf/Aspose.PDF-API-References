---
title: OpenAIClient.GetAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод OpenAIClient. Асинхронно получает данные о конкретном ассистенте
type: docs
weight: 190
url: /ru/net/aspose.pdf.ai/openaiclient/getassistantasync/
---
## Метод OpenAIClient.GetAssistantAsync

Асинхронно получает данные о конкретном ассистенте.

```csharp
public Task<AssistantResponse> GetAssistantAsync(string assistantId, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| assistantId | String | Идентификатор ассистента для получения. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит данные об ассистенте.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор ассистента равен null или пуст. |

### См. также

* класс [AssistantResponse](../../assistantresponse/)
* класс [OpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)