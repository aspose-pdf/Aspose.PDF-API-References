---
title: OpenAIClient.ModifyVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод OpenAIClient. Асинхронно изменяет существующее хранилище векторов
type: docs
weight: 430
url: /ru/net/aspose.pdf.ai/openaiclient/modifyvectorstoreasync/
---
## Метод OpenAIClient.ModifyVectorStoreAsync

Асинхронно изменяет существующее хранилище векторов.

```csharp
public Task<VectorStoreResponse> ModifyVectorStoreAsync(string vectorStoreId, 
    VectorStoreModifyRequest vectorStoreModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| vectorStoreId | String | Идентификатор хранилища векторов для изменения. |
| vectorStoreModifyRequest | VectorStoreModifyRequest | Объект запроса, содержащий детали изменения. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит ответ на изменение хранилища векторов.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор хранилища векторов равен null или пуст. |

### См. также

* класс [VectorStoreResponse](../../vectorstoreresponse/)
* класс [VectorStoreModifyRequest](../../vectorstoremodifyrequest/)
* класс [OpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)