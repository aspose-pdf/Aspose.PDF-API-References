---
title: IOpenAIClient.GetVectorStoreFileBatchFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод IOpenAIClient. Асинхронно извлекает список файлов в рамках конкретной партии файлов в векторном хранилище
type: docs
weight: 330
url: /ru/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchfilesasync/
---
## Метод IOpenAIClient.GetVectorStoreFileBatchFilesAsync

Асинхронно извлекает список файлов в рамках конкретной партии файлов в векторном хранилище.

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
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор партии файлов в векторном хранилище равен null или пуст. |

### См. также

* класс [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* класс [VectorStoreFileBatchFileListQueryParameters](../../vectorstorefilebatchfilelistqueryparameters/)
* интерфейс [IOpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)