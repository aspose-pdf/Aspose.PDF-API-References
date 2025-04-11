---
title: OpenAIClient.CreateVectorStoreFileAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод OpenAIClient. Асинхронно создает новый файл векторного хранилища
type: docs
weight: 110
url: /ru/net/aspose.pdf.ai/openaiclient/createvectorstorefileasync/
---
## Метод OpenAIClient.CreateVectorStoreFileAsync

Асинхронно создает новый файл векторного хранилища.

```csharp
public Task<VectorStoreFileResponse> CreateVectorStoreFileAsync(string vectorStoreId, 
    VectorStoreFileCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| vectorStoreId | String | Идентификатор векторного хранилища, в котором будет создан файл. |
| vectorStoreFileCreateRequest | VectorStoreFileCreateRequest | Объект запроса, содержащий детали для создания файла. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит ответ на создание файла.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор векторного хранилища равен null или пуст. |

### См. также

* класс [VectorStoreFileResponse](../../vectorstorefileresponse/)
* класс [VectorStoreFileCreateRequest](../../vectorstorefilecreaterequest/)
* класс [OpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)