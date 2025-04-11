---
title: IOpenAIClient.WaitForVectorStoreFileToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод IOpenAIClient. Ожидает завершения конкретного файла векторного хранилища асинхронно
type: docs
weight: 460
url: /ru/net/aspose.pdf.ai/iopenaiclient/waitforvectorstorefiletocompleteasync/
---
## Метод IOpenAIClient.WaitForVectorStoreFileToCompleteAsync

Ожидает завершения конкретного файла векторного хранилища асинхронно.

```csharp
public Task<VectorStoreFileResponse> WaitForVectorStoreFileToCompleteAsync(string vectorStoreId, 
    string fileId, CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| vectorStoreId | String | Идентификатор векторного хранилища, содержащего файл. |
| fileId | String | Идентификатор файла, который нужно отслеживать до завершения. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит окончательный статус файла.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор векторного хранилища равен null или пуст. |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор файла равен null или пуст. |

### См. также

* класс [VectorStoreFileResponse](../../vectorstorefileresponse/)
* интерфейс [IOpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)