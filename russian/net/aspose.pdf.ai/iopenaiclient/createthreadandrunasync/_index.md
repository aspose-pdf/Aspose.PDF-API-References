---
title: IOpenAIClient.CreateThreadAndRunAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод IOpenAIClient. Создает поток и выполняет его асинхронно
type: docs
weight: 60
url: /ru/net/aspose.pdf.ai/iopenaiclient/createthreadandrunasync/
---
## Метод IOpenAIClient.CreateThreadAndRunAsync

Создает поток и выполняет его асинхронно.

```csharp
public Task<RunResponse> CreateThreadAndRunAsync(RunThreadCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| runCreateRequest | RunThreadCreateRequest | Детали запроса для создания потока и выполнения. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит ответ на создание потока и выполнения.

### См. также

* класс [RunResponse](../../runresponse/)
* класс [RunThreadCreateRequest](../../runthreadcreaterequest/)
* интерфейс [IOpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)