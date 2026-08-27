---
title: "IOpenAIClient.CreateThreadAsync"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод IOpenAIClient. Асинхронно создает новый поток."
type: docs
weight: 70
url: /ru/net/aspose.pdf.ai/iopenaiclient/createthreadasync/
---
## IOpenAIClient.CreateThreadAsync method

Создает новый поток асинхронно.

```csharp
public Task<ThreadResponse> CreateThreadAsync(ThreadCreateRequest threadCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| threadCreateRequest | ThreadCreateRequest | Объект запроса, содержащий детали создания потока. |
| cancellationToken | Nullable`1 | Токен для отмены операции. |

### Возвращаемое значение

Задача, представляющая асинхронную операцию. Результат задачи содержит ответ от создания потока.

### См. также

* class [ThreadResponse](../../threadresponse/)
* class [ThreadCreateRequest](../../threadcreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


