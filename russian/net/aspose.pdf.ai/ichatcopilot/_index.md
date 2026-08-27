---
title: "Интерфейс IChatCopilot"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Интерфейс Aspose.Pdf.AI.IChatCopilot. Представляет чат‑помощника для взаимодействия с документами через модели ИИ"
type: docs
weight: 490
url: /ru/net/aspose.pdf.ai/ichatcopilot/
---
## IChatCopilot interface

Представляет чат‑помощника для взаимодействия с документами через модели ИИ.

```csharp
public interface IChatCopilot : IAICopilot
```

## Методы

| Имя | Описание |
| --- | --- |
| [DeleteContextAsync](../../aspose.pdf.ai/ichatcopilot/deletecontextasync/)(CancellationToken?) | Асинхронно удаляет контекст. |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync)(List&lt;string&gt;, CancellationToken?) | Асинхронно получает ответ для указанного списка сообщений. |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync_1)(string, CancellationToken?) | Асинхронно получает ответ для указанного сообщения. |
| [SaveContextAsync](../../aspose.pdf.ai/ichatcopilot/savecontextasync/)(string, CancellationToken?) | Асинхронно сохраняет контекст в файл JSON. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_1)(List&lt;string&gt;, string, CancellationToken?) | Асинхронно сохраняет ответы для указанного списка сообщений в файл PDF. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_3)(string, string, CancellationToken?) | Асинхронно сохраняет ответ для указанного сообщения в файл PDF. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync)(List&lt;string&gt;, string, SaveFormat, CancellationToken?) | Асинхронно сохраняет ответы для указанного списка сообщений в файл указанного формата. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_2)(string, string, SaveFormat, CancellationToken?) | Асинхронно сохраняет ответ для указанного сообщения в файл указанного формата. |

### См. также

* interface [IAICopilot](../iaicopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


