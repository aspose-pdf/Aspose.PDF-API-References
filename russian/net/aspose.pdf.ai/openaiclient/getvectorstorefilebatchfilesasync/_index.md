---
title: "OpenAIClient.GetVectorStoreFileBatchFilesAsync"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод OpenAIClient. Асинхронно получает список файлов в конкретном пакете файлов векторного хранилища"
type: docs
weight: 370
url: /ru/net/aspose.pdf.ai/openaiclient/getvectorstorefilebatchfilesasync/
---
## OpenAIClient.GetVectorStoreFileBatchFilesAsync method

Получает список файлов в конкретной партии файлов векторного хранилища асинхронно.

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFileBatchFilesAsync(string vectorStoreId, 
    string fileBatchId, VectorStoreFileBatchFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| vectorStoreId | String | Идентификатор векторного хранилища, содержащего партию файлов. |
| fileBatchId | String | Идентификатор пакета файлов, из которого нужно получить файлы. |
| queryParameters | VectorStoreFileBatchFileListQueryParameters | Необязательные параметры запроса для фильтрации списка файлов. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит список файлов в пакете файлов.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор векторного хранилища равен null или пуст. |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор партии файлов векторного хранилища равен null или пуст. |

### См. также

* class [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* class [VectorStoreFileBatchFileListQueryParameters](../../vectorstorefilebatchfilelistqueryparameters/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


