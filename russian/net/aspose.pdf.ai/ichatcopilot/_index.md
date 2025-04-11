---
title: Interface IChatCopilot
second_title: Aspose.PDF for .NET API Reference
description: Интерфейс Aspose.Pdf.AI.IChatCopilot. Представляет собой чат-коопилота для взаимодействия с документами через AI модели
type: docs
weight: 470
url: /ru/net/aspose.pdf.ai/ichatcopilot/
---
## Интерфейс IChatCopilot

Представляет собой чат-коопилота для взаимодействия с документами через AI модели.

```csharp
public interface IChatCopilot : IAICopilot
```

## Методы

| Название | Описание |
| --- | --- |
| [DeleteContextAsync](../../aspose.pdf.ai/ichatcopilot/deletecontextasync/)(CancellationToken?) | Асинхронно удаляет контекст. |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync)(List&lt;string&gt;, CancellationToken?) | Асинхронно получает ответ для данного списка сообщений. |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync_1)(string, CancellationToken?) | Асинхронно получает ответ для данного сообщения. |
| [SaveContextAsync](../../aspose.pdf.ai/ichatcopilot/savecontextasync/)(string, CancellationToken?) | Асинхронно сохраняет контекст в JSON файл. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_1)(List&lt;string&gt;, string, CancellationToken?) | Асинхронно сохраняет ответы для данного списка сообщений в PDF файл. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_3)(string, string, CancellationToken?) | Асинхронно сохраняет ответ для данного сообщения в PDF файл. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync)(List&lt;string&gt;, string, SaveFormat, CancellationToken?) | Асинхронно сохраняет ответы для данного списка сообщений в файл с указанным форматом. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_2)(string, string, SaveFormat, CancellationToken?) | Асинхронно сохраняет ответ для данного сообщения в файл с указанным форматом. |

### См. также

* интерфейс [IAICopilot](../iaicopilot/)
* пространство имен [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../)