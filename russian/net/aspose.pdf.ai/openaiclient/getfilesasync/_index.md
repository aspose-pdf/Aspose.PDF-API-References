---
title: "OpenAIClient.GetFilesAsync"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод OpenAIClient. Получает список файлов асинхронно на основе указанной цели."
type: docs
weight: 230
url: /ru/net/aspose.pdf.ai/openaiclient/getfilesasync/
---
## OpenAIClient.GetFilesAsync method

Получает список файлов асинхронно на основе указанной цели.

```csharp
public Task<FileListResponse> GetFilesAsync(string purpose = null, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| purpose | String | Необязательно. Цель файлов для получения. Если null, будут получены файлы для всех целей. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит список файлов.

### См. также

* class [FileListResponse](../../filelistresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


