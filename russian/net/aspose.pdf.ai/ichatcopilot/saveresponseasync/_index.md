---
title: IChatCopilot.SaveResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод IChatCopilot. Асинхронно сохраняет ответ для данного сообщения в PDF файл
type: docs
weight: 40
url: /ru/net/aspose.pdf.ai/ichatcopilot/saveresponseasync/
---
## SaveResponseAsync(string, string, CancellationToken?) {#saveresponseasync_3}

Асинхронно сохраняет ответ для данного сообщения в PDF файл.

```csharp
public Task SaveResponseAsync(string message, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| message | String | Входящее сообщение, для которого сохраняется ответ. |
| outputFileName | String | Имя выходного PDF файла для сохранения ответа. |
| cancellationToken | Nullable`1 | Токен отмены (необязательно). |

### Возвращаемое значение

Задача, представляющая асинхронную операцию.

### См. также

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(string, string, SaveFormat, CancellationToken?) {#saveresponseasync_2}

Асинхронно сохраняет ответ для данного сообщения в файл с указанным форматом.

```csharp
public Task SaveResponseAsync(string message, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| message | String | Входящее сообщение, для которого сохраняется ответ. |
| outputFileName | String | Имя выходного файла для сохранения ответа. |
| saveFormat | SaveFormat | Формат, в котором нужно сохранить ответ (PDF, если не указано). |
| cancellationToken | Nullable`1 | Токен отмены (необязательно). |

### Возвращаемое значение

Задача, представляющая асинхронную операцию.

### См. также

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List&lt;string&gt;, string, CancellationToken?) {#saveresponseasync_1}

Асинхронно сохраняет ответы для данного списка сообщений в PDF файл.

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messages | List`1 | Список входящих сообщений, для которых сохраняются ответы. |
| outputFileName | String | Имя выходного PDF файла для сохранения ответов. |
| cancellationToken | Nullable`1 | Токен отмены (необязательно). |

### Возвращаемое значение

Задача, представляющая асинхронную операцию.

### См. также

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List&lt;string&gt;, string, SaveFormat, CancellationToken?) {#saveresponseasync}

Асинхронно сохраняет ответы для данного списка сообщений в файл с указанным форматом.

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messages | List`1 | Список входящих сообщений, для которых сохраняются ответы. |
| outputFileName | String | Имя выходного файла для сохранения ответов. |
| saveFormat | SaveFormat | Формат, в котором нужно сохранить ответы (PDF, если не указано). |
| cancellationToken | Nullable`1 | Токен отмены (необязательно). |

### Возвращаемое значение

Задача, представляющая асинхронную операцию.

### См. также

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)