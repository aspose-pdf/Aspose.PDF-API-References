---
title: "IOpenAIClient.DeleteFileAsync"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод IOpenAIClient. Асинхронно удаляет конкретный файл"
type: docs
weight: 140
url: /ru/net/aspose.pdf.ai/iopenaiclient/deletefileasync/
---
## IOpenAIClient.DeleteFileAsync method

Удаляет конкретный файл асинхронно.

```csharp
public Task<DeleteStatusResponse> DeleteFileAsync(string fileId, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileId | String | Идентификатор файла, который нужно удалить. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит статус операции удаления.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор файла равен null или пуст. |

### См. также

* class [DeleteStatusResponse](../../deletestatusresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


