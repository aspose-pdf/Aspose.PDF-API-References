---
title: "OpenAIClient.DeleteVectorStoreAsync"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод OpenAIClient. Удаляет векторное хранилище асинхронно"
type: docs
weight: 170
url: /ru/net/aspose.pdf.ai/openaiclient/deletevectorstoreasync/
---
## OpenAIClient.DeleteVectorStoreAsync method

Удаляет хранилище векторов асинхронно.

```csharp
public Task<DeleteStatusResponse> DeleteVectorStoreAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| vectorStoreId | String | Идентификатор векторного хранилища для удаления. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит статус операции удаления.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор векторного хранилища равен null или пуст. |

### См. также

* class [DeleteStatusResponse](../../deletestatusresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


