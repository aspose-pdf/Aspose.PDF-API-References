---
title: OpenAIClient.GetFileAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод OpenAIClient. Асинхронно извлекает детали конкретного файла
type: docs
weight: 220
url: /ru/net/aspose.pdf.ai/openaiclient/getfileasync/
---
## Метод OpenAIClient.GetFileAsync

Асинхронно извлекает детали конкретного файла.

```csharp
public Task<FileResponse> GetFileAsync(string fileId, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileId | String | Идентификатор файла для извлечения. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит детали файла.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда идентификатор файла равен null или пуст. |

### См. также

* класс [FileResponse](../../fileresponse/)
* класс [OpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)