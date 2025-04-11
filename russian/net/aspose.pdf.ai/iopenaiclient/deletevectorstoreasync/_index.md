---
title: IOpenAIClient.DeleteVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод IOpenAIClient. Удаляет векторное хранилище асинхронно
type: docs
weight: 170
url: /ru/net/aspose.pdf.ai/iopenaiclient/deletevectorstoreasync/
---
## Метод IOpenAIClient.DeleteVectorStoreAsync

Удаляет векторное хранилище асинхронно.

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

* класс [DeleteStatusResponse](../../deletestatusresponse/)
* интерфейс [IOpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)