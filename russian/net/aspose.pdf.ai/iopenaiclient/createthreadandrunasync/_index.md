---
title: "IOpenAIClient.CreateThreadAndRunAsync"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод IOpenAIClient. Асинхронно создает поток и запуск в нём"
type: docs
weight: 60
url: /ru/net/aspose.pdf.ai/iopenaiclient/createthreadandrunasync/
---
## IOpenAIClient.CreateThreadAndRunAsync method

Создает поток и запуск в нем асинхронно.

```csharp
public Task<RunResponse> CreateThreadAndRunAsync(RunThreadCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| runCreateRequest | RunThreadCreateRequest | Подробности запроса для создания потока и запуска. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит ответ от создания потока и запуска.

### См. также

* class [RunResponse](../../runresponse/)
* class [RunThreadCreateRequest](../../runthreadcreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


