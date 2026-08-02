---
title: "IOpenAIClient.DeleteVectorStoreFileAsync"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод IOpenAIClient. Удаляет файл в векторном хранилище асинхронно"
type: docs
weight: 180
url: /ru/net/aspose.pdf.ai/iopenaiclient/deletevectorstorefileasync/
---
## IOpenAIClient.DeleteVectorStoreFileAsync method

Удаляет файл в хранилище векторов асинхронно.

```csharp
public Task<DeleteStatusResponse> DeleteVectorStoreFileAsync(string vectorStoreId, string fileId, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| vectorStoreId | String | Идентификатор векторного хранилища, содержащего файл для удаления. |
| fileId | String | Идентификатор файла, который нужно удалить. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит статус операции удаления.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор векторного хранилища равен null или пуст. |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор файла равен null или пуст. |

### См. также

* class [DeleteStatusResponse](../../deletestatusresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


