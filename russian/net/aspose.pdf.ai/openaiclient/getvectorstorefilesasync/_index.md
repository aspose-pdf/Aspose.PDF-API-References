---
title: OpenAIClient.GetVectorStoreFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод OpenAIClient. Асинхронно извлекает список файлов в конкретном векторном хранилище
type: docs
weight: 370
url: /ru/net/aspose.pdf.ai/openaiclient/getvectorstorefilesasync/
---
## Метод OpenAIClient.GetVectorStoreFilesAsync

Асинхронно извлекает список файлов в конкретном векторном хранилище.

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFilesAsync(string vectorStoreId, 
    VectorStoreFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| vectorStoreId | String | Идентификатор векторного хранилища, содержащего файлы. |
| queryParameters | VectorStoreFileListQueryParameters | Необязательные параметры запроса для фильтрации списка файлов. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит список файлов в векторном хранилище.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор векторного хранилища равен null или пуст. |

### См. также

* класс [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* класс [VectorStoreFileListQueryParameters](../../vectorstorefilelistqueryparameters/)
* класс [OpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)