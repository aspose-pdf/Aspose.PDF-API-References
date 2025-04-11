---
title: IOpenAIClient.GetAssistantsAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод IOpenAIClient. Асинхронно получает список ассистентов
type: docs
weight: 200
url: /ru/net/aspose.pdf.ai/iopenaiclient/getassistantsasync/
---
## Метод IOpenAIClient.GetAssistantsAsync

Асинхронно получает список ассистентов.

```csharp
public Task<AssistantListResponse> GetAssistantsAsync(
    AssistantListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| queryParameters | AssistantListQueryParameters | Необязательные параметры запроса для фильтрации списка ассистентов. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит список ассистентов.

### См. также

* класс [AssistantListResponse](../../assistantlistresponse/)
* класс [AssistantListQueryParameters](../../assistantlistqueryparameters/)
* интерфейс [IOpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)