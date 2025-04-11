---
title: Class MarkupParagraph
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Text.MarkupParagraph. Представляет абзац
type: docs
weight: 10630
url: /ru/net/aspose.pdf.text/markupparagraph/
---
## Класс MarkupParagraph

Представляет абзац.

```csharp
public sealed class MarkupParagraph
```

## Свойства

| Имя | Описание |
| --- | --- |
| [ContinuationPageNumbers](../../aspose.pdf.text/markupparagraph/continuationpagenumbers/) { get; } | Список номеров страниц, на которых продолжается абзац. Он будет совпадать со страницей, на которой начался абзац, если он продолжается в следующем столбце на той же странице. |
| [Fragments](../../aspose.pdf.text/markupparagraph/fragments/) { get; } | Коллекция непустых [`TextFragment`](../textfragment/) объектов абзаца. |
| [Lines](../../aspose.pdf.text/markupparagraph/lines/) { get; } | Строки абзаца. Каждая строка представлена списком текстовых фрагментов. |
| [Points](../../aspose.pdf.text/markupparagraph/points/) { get; } | Точки многоугольника, описывающего абзац. Начальная точка — нижний левый угол абзаца. Следующие точки расположены в противочасовой последовательности. |
| [SecondaryPoints](../../aspose.pdf.text/markupparagraph/secondarypoints/) { get; } | Точки вторичного многоугольника, описывающего продолжение абзаца. Она не будет равна null, если абзац продолжается в следующем столбце или на следующей странице. Начальная точка — нижний левый угол абзаца. Следующие точки расположены в противочасовой последовательности. |
| [Text](../../aspose.pdf.text/markupparagraph/text/) { get; set; } | Получает или задает текст абзаца. |

### См. также

* пространство имен [Aspose.Pdf.Text](../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../)