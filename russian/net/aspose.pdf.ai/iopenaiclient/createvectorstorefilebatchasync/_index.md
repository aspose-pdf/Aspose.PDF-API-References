---
title: IOpenAIClient.CreateVectorStoreFileBatchAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод IOpenAIClient. Асинхронно создает новую партию файлов в векторном хранилище
type: docs
weight: 120
url: /ru/net/aspose.pdf.ai/iopenaiclient/createvectorstorefilebatchasync/
---
## Метод IOpenAIClient.CreateVectorStoreFileBatchAsync

Асинхронно создает новую партию файлов в векторном хранилище.

```csharp
public Task<VectorStoreFileBatchResponse> CreateVectorStoreFileBatchAsync(string vectorStoreId, 
    VectorStoreFileBatchCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| vectorStoreId | String | Идентификатор векторного хранилища, в котором будет создана партия файлов. |
| vectorStoreFileCreateRequest | VectorStoreFileBatchCreateRequest | Объект запроса, содержащий детали для создания партии файлов. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит ответ на создание партии файлов.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор векторного хранилища равен null или пуст. |

### См. также

* класс [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* класс [VectorStoreFileBatchCreateRequest](../../vectorstorefilebatchcreaterequest/)
* интерфейс [IOpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)