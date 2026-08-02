---
title: "IOpenAIClient.CreateVectorStoreAsync"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод IOpenAIClient. Асинхронно создает новое векторное хранилище"
type: docs
weight: 100
url: /ru/net/aspose.pdf.ai/iopenaiclient/createvectorstoreasync/
---
## IOpenAIClient.CreateVectorStoreAsync method

Создает новое хранилище векторов асинхронно.

```csharp
public Task<VectorStoreResponse> CreateVectorStoreAsync(
    VectorStoreCreateRequest vectorStoreCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| vectorStoreCreateRequest | VectorStoreCreateRequest | Объект запроса, содержащий детали создания векторного хранилища. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит ответ от создания векторного хранилища.

### См. также

* class [VectorStoreResponse](../../vectorstoreresponse/)
* class [VectorStoreCreateRequest](../../vectorstorecreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


