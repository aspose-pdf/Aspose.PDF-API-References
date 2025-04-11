---
title: IOpenAIClient.CreateThreadAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод IOpenAIClient. Создает новый поток асинхронно
type: docs
weight: 70
url: /ru/net/aspose.pdf.ai/iopenaiclient/createthreadasync/
---
## Метод IOpenAIClient.CreateThreadAsync

Создает новый поток асинхронно.

```csharp
public Task<ThreadResponse> CreateThreadAsync(ThreadCreateRequest threadCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| threadCreateRequest | ThreadCreateRequest | Объект запроса, содержащий детали для создания потока. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит ответ на создание потока.

### См. также

* класс [ThreadResponse](../../threadresponse/)
* класс [ThreadCreateRequest](../../threadcreaterequest/)
* интерфейс [IOpenAIClient](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)