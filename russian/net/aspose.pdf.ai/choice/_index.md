---
title: Class Choice
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.AI.Choice. Представляет выбор в ответе на завершение чата
type: docs
weight: 200
url: /ru/net/aspose.pdf.ai/choice/
---
## Класс Choice

Представляет выбор в ответе на завершение чата.

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
| [FinishReason](../../aspose.pdf.ai/choice/finishreason/) { get; set; } | Получает или задает причину, по которой модель прекратила генерацию токенов. Это произойдет, если модель достигла естественной точки остановки или предоставленной последовательности остановки, длины, если максимальное количество токенов, указанное в запросе, было достигнуто. |
| [Index](../../aspose.pdf.ai/choice/index/) { get; set; } | Получает или задает индекс выбора в списке выборов. |
| [Logprobs](../../aspose.pdf.ai/choice/logprobs/) { get; set; } | Получает или задает информацию о логарифмической вероятности для выбора. |
| [Message](../../aspose.pdf.ai/choice/message/) { get; set; } | Получает или задает сообщение о завершении чата, сгенерированное моделью. |

## Методы

| Имя | Описание |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/choice/tostring/)() | Возвращает содержимое выбора в виде строки. |

### См. также

* пространство имен [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../)