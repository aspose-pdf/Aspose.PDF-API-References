---
title: OpenAIClient.DeleteAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод OpenAIClient. Удаляет существующего помощника асинхронно
type: docs
weight: 130
url: /ru/net/aspose.pdf.ai/openaiclient/deleteassistantasync/
---
## Метод OpenAIClient.DeleteAssistantAsync

Удаляет существующего помощника асинхронно.

```csharp
public Task<DeleteStatusResponse> DeleteAssistantAsync(string assistantId, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| assistantId | String | Идентификатор помощника для удаления. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит статус операции удаления.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор помощника равен null или пуст. |

### См. также

* класс [DeleteStatusResponse](../../deletestatusresponse/)
* класс [OpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)