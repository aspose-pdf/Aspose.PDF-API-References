---
title: "OpenAIClient.ModifyVectorStoreAsync"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод OpenAIClient. Асинхронно изменяет существующее векторное хранилище"
type: docs
weight: 440
url: /ru/net/aspose.pdf.ai/openaiclient/modifyvectorstoreasync/
---
## OpenAIClient.ModifyVectorStoreAsync method

Изменяет существующее векторное хранилище асинхронно.

```csharp
public Task<VectorStoreResponse> ModifyVectorStoreAsync(string vectorStoreId, 
    VectorStoreModifyRequest vectorStoreModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| vectorStoreId | String | Идентификатор векторного хранилища для изменения. |
| vectorStoreModifyRequest | VectorStoreModifyRequest | Объект запроса, содержащий детали изменения. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит ответ от изменения векторного хранилища.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор векторного хранилища равен null или пуст. |

### См. также

* class [VectorStoreResponse](../../vectorstoreresponse/)
* class [VectorStoreModifyRequest](../../vectorstoremodifyrequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


