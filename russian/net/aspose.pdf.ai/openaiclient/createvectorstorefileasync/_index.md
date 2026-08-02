---
title: "OpenAIClient.CreateVectorStoreFileAsync"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод OpenAIClient. Создаёт новый файл векторного хранилища асинхронно"
type: docs
weight: 110
url: /ru/net/aspose.pdf.ai/openaiclient/createvectorstorefileasync/
---
## OpenAIClient.CreateVectorStoreFileAsync method

Создает новый файл хранилища векторов асинхронно.

```csharp
public Task<VectorStoreFileResponse> CreateVectorStoreFileAsync(string vectorStoreId, 
    VectorStoreFileCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| vectorStoreId | String | Идентификатор векторного хранилища, в котором будет создан файл. |
| vectorStoreFileCreateRequest | VectorStoreFileCreateRequest | Объект запроса, содержащий детали создания файла. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит ответ от создания файла.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор векторного хранилища равен null или пуст. |

### См. также

* class [VectorStoreFileResponse](../../vectorstorefileresponse/)
* class [VectorStoreFileCreateRequest](../../vectorstorefilecreaterequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


