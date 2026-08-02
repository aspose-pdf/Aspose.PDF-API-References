---
title: "OpenAIClient.DeleteAssistantAsync"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод OpenAIClient. Асинхронно удаляет существующего помощника"
type: docs
weight: 130
url: /ru/net/aspose.pdf.ai/openaiclient/deleteassistantasync/
---
## OpenAIClient.DeleteAssistantAsync method

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
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор помощника равен null или пустой. |

### См. также

* class [DeleteStatusResponse](../../deletestatusresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


