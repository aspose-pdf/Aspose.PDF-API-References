---
title: IChatCopilot.GetResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод IChatCopilot. Асинхронно получает ответ на данное сообщение
type: docs
weight: 20
url: /ru/net/aspose.pdf.ai/ichatcopilot/getresponseasync/
---
## GetResponseAsync(string, CancellationToken?) {#getresponseasync_1}

Асинхронно получает ответ на данное сообщение.

```csharp
public Task<string> GetResponseAsync(string message, CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| message | String | Входящее сообщение, для которого запрашивается ответ. |
| cancellationToken | Nullable`1 | Токен отмены (необязательный). |

### Возвращаемое значение

Задача, представляющая асинхронную операцию с ответной строкой.

### См. также

* интерфейс [IChatCopilot](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)

---

## GetResponseAsync(List&lt;string&gt;, CancellationToken?) {#getresponseasync}

Асинхронно получает ответ на данный список сообщений.

```csharp
public Task<string> GetResponseAsync(List<string> messages, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messages | List`1 | Список входящих сообщений, для которых запрашиваются ответы. |
| cancellationToken | Nullable`1 | Токен отмены (необязательный). |

### Возвращаемое значение

Задача, представляющая асинхронную операцию с ответной строкой.

### См. также

* интерфейс [IChatCopilot](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)