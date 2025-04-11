---
title: OpenAIClient.GetVectorStoreFileBatchFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод OpenAIClient. Асинхронно извлекает список файлов в рамках конкретной партии файлов векторного хранилища
type: docs
weight: 360
url: /ru/net/aspose.pdf.ai/openaiclient/getvectorstorefilebatchfilesasync/
---
## Метод OpenAIClient.GetVectorStoreFileBatchFilesAsync

Асинхронно извлекает список файлов в рамках конкретной партии файлов векторного хранилища.

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFileBatchFilesAsync(string vectorStoreId, 
    string fileBatchId, VectorStoreFileBatchFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| vectorStoreId | String | Идентификатор векторного хранилища, содержащего партию файлов. |
| fileBatchId | String | Идентификатор партии файлов, из которой нужно извлечь файлы. |
| queryParameters | VectorStoreFileBatchFileListQueryParameters | Необязательные параметры запроса для фильтрации списка файлов. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит список файлов в рамках партии файлов.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор векторного хранилища равен null или пуст. |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор партии файлов векторного хранилища равен null или пуст. |

### См. также

* класс [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* класс [VectorStoreFileBatchFileListQueryParameters](../../vectorstorefilebatchfilelistqueryparameters/)
* класс [OpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)