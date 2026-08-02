---
title: "IOpenAIClient.GetVectorStoreFilesAsync"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод IOpenAIClient. Получает список файлов в конкретном векторном хранилище асинхронно"
type: docs
weight: 340
url: /ru/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilesasync/
---
## IOpenAIClient.GetVectorStoreFilesAsync method

Получает список файлов в конкретном векторном хранилище асинхронно.

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

* class [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* class [VectorStoreFileListQueryParameters](../../vectorstorefilelistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


