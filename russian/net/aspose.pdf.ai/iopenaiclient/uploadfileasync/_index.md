---
title: "IOpenAIClient.UploadFileAsync"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод IOpenAIClient. Асинхронно загружает файл на сервер OpenAI"
type: docs
weight: 420
url: /ru/net/aspose.pdf.ai/iopenaiclient/uploadfileasync/
---
## IOpenAIClient.UploadFileAsync method

Асинхронно загружает файл на сервер OpenAI.

```csharp
public Task<FileResponse> UploadFileAsync(string purpose, string fileName, byte[] fileBytes, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| purpose | String | Назначение загрузки файла, обычно описывающее, как будет использоваться файл. |
| fileName | String | Имя файла для загрузки. |
| fileBytes | Byte[] | Массив байтов, содержащий данные файла. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит ответ от загрузки файла.

### Исключения

| исключение | условие |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда назначение файла равно null или пусто. |
| [AIClientException](../../aiclientexception/) | Выбрасывается, когда имя файла равно null или пусто. |

### См. также

* class [FileResponse](../../fileresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


