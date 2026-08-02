---
title: "OpenAIClient.GetAssistantAsync"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод OpenAIClient. Асинхронно получает детали конкретного помощника"
type: docs
weight: 190
url: /ru/net/aspose.pdf.ai/openaiclient/getassistantasync/
---
## OpenAIClient.GetAssistantAsync method

Получает детали конкретного помощника асинхронно.

```csharp
public Task<AssistantResponse> GetAssistantAsync(string assistantId, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| assistantId | String | Идентификатор помощника для получения. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит детали помощника.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор помощника равен null или пустой. |

### См. также

* class [AssistantResponse](../../assistantresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


