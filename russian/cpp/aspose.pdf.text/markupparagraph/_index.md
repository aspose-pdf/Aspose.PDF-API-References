---
title: "Aspose::Pdf::Text::MarkupParagraph класс"
linktitle: "MarkupParagraph"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Text::MarkupParagraph класс. Представляет абзац в C++."
type: docs
weight: 2100
url: /ru/cpp/aspose.pdf.text/markupparagraph/
---
## MarkupParagraph class


Представляет абзац.

```cpp
class MarkupParagraph : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_ContinuationPageNumbers](./get_continuationpagenumbers/)() const | Список номеров страниц, на которых продолжается абзац. Он будет совпадать со страницей, где абзац начался, если он продолжается в следующей колонке на той же странице. |
| [get_Fragments](./get_fragments/)() | [Collection](../../aspose.pdf/collection/) непустых объектов [TextFragment](../textfragment/) абзаца. |
| [get_Lines](./get_lines/)() const | Строки абзаца. Каждая строка представлена списком текстовых фрагментов. |
| [get_Points](./get_points/)() | Точки многоугольника, описывающего абзац. Начальная точка — нижний левый угол абзаца. Последующие точки идут в порядке против часовой стрелки. |
| [get_SecondaryPoints](./get_secondarypoints/)() const | Точки вторичного многоугольника, описывающего продолжение абзаца. Он не будет null, если абзац продолжается в следующей колонке или на странице. Начальная точка — нижний левый угол абзаца. Последующие точки идут в порядке против часовой стрелки. |
| [get_Text](./get_text/)() | Получает текст абзаца. |
| [set_Text](./set_text/)(const System::String\&) | Устанавливает текст абзаца. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
