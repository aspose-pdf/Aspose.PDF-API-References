---
title: Class TruncationStrategy
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.AI.TruncationStrategy. Представляет стратегию усечения, которая контролирует, как поток будет усечен перед выполнением
type: docs
weight: 1240
url: /ru/net/aspose.pdf.ai/truncationstrategy/
---
## Класс TruncationStrategy

Представляет стратегию усечения, которая контролирует, как поток будет усечен перед выполнением.

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
| [LastMessages](../../aspose.pdf.ai/truncationstrategy/lastmessages/) { get; set; } | Получает или задает количество самых последних сообщений из потока при построении контекста для выполнения. |
| [StrategyType](../../aspose.pdf.ai/truncationstrategy/strategytype/) { get; set; } | Получает или задает стратегию усечения, которую следует использовать для потока. По умолчанию - auto. Если установлено значение last_messages, поток будет усечен до n самых последних сообщений в потоке. При установке на auto сообщения в середине потока будут отброшены, чтобы соответствовать длине контекста модели, max_prompt_tokens. |

### См. также

* пространство имен [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../)