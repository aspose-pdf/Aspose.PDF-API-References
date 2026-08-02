---
title: "Класс Choice"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.AI.Choice. Представляет вариант в ответе завершения чата."
type: docs
weight: 210
url: /ru/net/aspose.pdf.ai/choice/
---
## Choice class

Представляет вариант в ответе завершения чата.

```csharp
public class Choice
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Choice](choice/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [FinishReason](../../aspose.pdf.ai/choice/finishreason/) { get; set; } | Получает или задает причину, по которой модель прекратила генерировать токены. Это будет stop, если модель достигла естественной точки остановки или предоставленной последовательности остановки, length, если было достигнуто максимальное количество токенов, указанное в запросе. |
| [Index](../../aspose.pdf.ai/choice/index/) { get; set; } | Получает или задает индекс варианта в списке вариантов. |
| [Logprobs](../../aspose.pdf.ai/choice/logprobs/) { get; set; } | Получает или задает информацию о лог‑вероятности для варианта. |
| [Message](../../aspose.pdf.ai/choice/message/) { get; set; } | Получает или задает сообщение завершения чата, сгенерированное моделью. |

## Методы

| Имя | Описание |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/choice/tostring/)() | Возвращает содержимое варианта в виде строки. |

### См. также

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


