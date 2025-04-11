---
title: IOpenAIClient.GetAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод IOpenAIClient. Асинхронно извлекает данные о конкретном ассистенте
type: docs
weight: 190
url: /ru/net/aspose.pdf.ai/iopenaiclient/getassistantasync/
---
## Метод IOpenAIClient.GetAssistantAsync

Асинхронно извлекает данные о конкретном ассистенте.

```csharp
public Task<AssistantResponse> GetAssistantAsync(string assistantId, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| assistantId | String | Идентификатор ассистента для извлечения. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит данные об ассистенте.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор ассистента равен null или пуст. |

### См. также

* класс [AssistantResponse](../../assistantresponse/)
* интерфейс [IOpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)