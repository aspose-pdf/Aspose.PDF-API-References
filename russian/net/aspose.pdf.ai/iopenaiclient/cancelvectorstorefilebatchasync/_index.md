---
title: "IOpenAIClient.CancelVectorStoreFileBatchAsync"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод IOpenAIClient. Отменяет конкретную партию файлов векторного хранилища асинхронно"
type: docs
weight: 20
url: /ru/net/aspose.pdf.ai/iopenaiclient/cancelvectorstorefilebatchasync/
---
## IOpenAIClient.CancelVectorStoreFileBatchAsync method

Асинхронно отменяет конкретный пакет файлов векторного хранилища.

```csharp
public Task<VectorStoreFileBatchResponse> CancelVectorStoreFileBatchAsync(string vectorStoreId, 
    string fileBatchId, CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| vectorStoreId | String | Идентификатор векторного хранилища, содержащего пакет файлов для отмены. |
| fileBatchId | String | Идентификатор пакета файлов для отмены. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит ответ от отмены пакета файлов.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор векторного хранилища равен null или пуст. |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор партии файлов векторного хранилища равен null или пуст. |

### См. также

* class [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


