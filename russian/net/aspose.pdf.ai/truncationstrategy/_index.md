---
title: "Класс TruncationStrategy"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.AI.TruncationStrategy. Представляет стратегию усечения, которая контролирует, как поток будет усечён перед запуском."
type: docs
weight: 1330
url: /ru/net/aspose.pdf.ai/truncationstrategy/
---
## TruncationStrategy class

Представляет стратегию усечения, определяющую, как ветка будет усечена перед запуском.

```csharp
public class TruncationStrategy
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TruncationStrategy](truncationstrategy/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [LastMessages](../../aspose.pdf.ai/truncationstrategy/lastmessages/) { get; set; } | Получает или задаёт количество самых последних сообщений из потока при построении контекста для выполнения. |
| [StrategyType](../../aspose.pdf.ai/truncationstrategy/strategytype/) { get; set; } | Получает или задаёт стратегию усечения, используемую для потока. По умолчанию — auto. Если установить значение last_messages, поток будет усечён до n самых последних сообщений. При установке auto сообщения в середине потока будут удаляться, чтобы соответствовать длине контекста модели, max_prompt_tokens. |

### См. также

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


