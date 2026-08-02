---
title: "OpenAIClient.GetVectorStoreFilesAsync"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод OpenAIClient. Асинхронно получает список файлов в конкретном векторном хранилище"
type: docs
weight: 380
url: /ru/net/aspose.pdf.ai/openaiclient/getvectorstorefilesasync/
---
## OpenAIClient.GetVectorStoreFilesAsync method

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
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


