---
title: IOpenAIClient.GetFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод IOpenAIClient. Асинхронно извлекает список файлов на основе указанной цели
type: docs
weight: 220
url: /ru/net/aspose.pdf.ai/iopenaiclient/getfilesasync/
---
## Метод IOpenAIClient.GetFilesAsync

Асинхронно извлекает список файлов на основе указанной цели.

```csharp
public Task<FileListResponse> GetFilesAsync(string purpose = null, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| purpose | String | Необязательный. Цель файлов для извлечения. Если null, извлекаются файлы для всех целей. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит список файлов.

### См. также

* класс [FileListResponse](../../filelistresponse/)
* интерфейс [IOpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)