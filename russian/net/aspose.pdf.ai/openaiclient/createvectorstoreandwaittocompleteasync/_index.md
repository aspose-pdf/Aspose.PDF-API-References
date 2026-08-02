---
title: "OpenAIClient.CreateVectorStoreAndWaitToCompleteAsync"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод OpenAIClient. Создаёт новый векторный магазин и ждёт его завершения асинхронно."
type: docs
weight: 90
url: /ru/net/aspose.pdf.ai/openaiclient/createvectorstoreandwaittocompleteasync/
---
## OpenAIClient.CreateVectorStoreAndWaitToCompleteAsync method

Создает новое хранилище векторов и ожидает его завершения асинхронно.

```csharp
public Task<VectorStoreResponse> CreateVectorStoreAndWaitToCompleteAsync(
    VectorStoreCreateRequest vectorStoreCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| vectorStoreCreateRequest | VectorStoreCreateRequest | Объект запроса, содержащий детали создания векторного хранилища. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит ответ от создания векторного магазина после завершения.

### См. также

* class [VectorStoreResponse](../../vectorstoreresponse/)
* class [VectorStoreCreateRequest](../../vectorstorecreaterequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


