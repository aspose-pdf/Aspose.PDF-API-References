---
title: OpenAIClient.GetFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод OpenAIClient. Асинхронно получает список файлов на основе указанной цели
type: docs
weight: 230
url: /ru/net/aspose.pdf.ai/openaiclient/getfilesasync/
---
## Метод OpenAIClient.GetFilesAsync

Асинхронно получает список файлов на основе указанной цели.

```csharp
public Task<FileListResponse> GetFilesAsync(string purpose = null, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| purpose | String | Необязательно. Цель файлов для получения. Если null, получаются файлы для всех целей. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит список файлов.

### См. также

* класс [FileListResponse](../../filelistresponse/)
* класс [OpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)