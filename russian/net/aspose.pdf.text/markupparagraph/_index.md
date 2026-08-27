---
title: "Класс MarkupParagraph"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Text.MarkupParagraph. Представляет абзац"
type: docs
weight: 10810
url: /ru/net/aspose.pdf.text/markupparagraph/
---
## MarkupParagraph class

Представляет абзац.

```csharp
public sealed class MarkupParagraph
```

## Свойства

| Имя | Описание |
| --- | --- |
| [ContinuationPageNumbers](../../aspose.pdf.text/markupparagraph/continuationpagenumbers/) { get; } | Список номеров страниц, на которых продолжается абзац. Он будет совпадать со страницей, где абзац начался, если он продолжается в следующей колонке на той же странице. |
| [Fragments](../../aspose.pdf.text/markupparagraph/fragments/) { get; } | Коллекция непустых объектов [`TextFragment`](../textfragment/) абзаца. |
| [Lines](../../aspose.pdf.text/markupparagraph/lines/) { get; } | Строки абзаца. Каждая строка представлена списком фрагментов текста. |
| [Points](../../aspose.pdf.text/markupparagraph/points/) { get; } | Точки многоугольника, описывающего абзац. Начальная точка — нижний левый угол абзаца. Последующие точки идут в порядке против часовой стрелки. |
| [SecondaryPoints](../../aspose.pdf.text/markupparagraph/secondarypoints/) { get; } | Точки вторичного многоугольника, описывающего продолжение абзаца. Они не будут null, если абзац продолжается в следующей колонке или на странице. Начальная точка — нижний левый угол абзаца. Последующие точки идут в порядке против часовой стрелки. |
| [Text](../../aspose.pdf.text/markupparagraph/text/) { get; set; } | Получает или задает текст абзаца. |

### См. также

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


