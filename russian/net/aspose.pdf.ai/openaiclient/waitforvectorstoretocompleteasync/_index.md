---
title: "OpenAIClient.WaitForVectorStoreToCompleteAsync"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод OpenAIClient. Ожидает завершения конкретного векторного хранилища асинхронно"
type: docs
weight: 510
url: /ru/net/aspose.pdf.ai/openaiclient/waitforvectorstoretocompleteasync/
---
## OpenAIClient.WaitForVectorStoreToCompleteAsync method

Ожидает завершения конкретного векторного хранилища асинхронно.

```csharp
public Task<VectorStoreResponse> WaitForVectorStoreToCompleteAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| vectorStoreId | String | Идентификатор векторного хранилища для мониторинга до завершения. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит окончательный статус векторного хранилища.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор векторного хранилища равен null или пуст. |

### См. также

* class [VectorStoreResponse](../../vectorstoreresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


