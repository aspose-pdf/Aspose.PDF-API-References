---
title: OpenAIClient.UploadFileAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод OpenAIClient. Асинхронно загружает файл на сервер OpenAI
type: docs
weight: 450
url: /ru/net/aspose.pdf.ai/openaiclient/uploadfileasync/
---
## Метод OpenAIClient.UploadFileAsync

Асинхронно загружает файл на сервер OpenAI.

```csharp
public Task<FileResponse> UploadFileAsync(string purpose, string fileName, byte[] fileBytes, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| purpose | String | Цель загрузки файла, обычно описывающая, как будет использоваться файл. |
| fileName | String | Имя файла для загрузки. |
| fileBytes | Byte[] | Массив байтов, содержащий данные файла. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит ответ на загрузку файла.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда цель файла равна null или пуста. |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда имя файла равно null или пусто. |

### См. также

* класс [FileResponse](../../fileresponse/)
* класс [OpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)