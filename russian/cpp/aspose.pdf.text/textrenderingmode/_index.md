---
title: "Aspose::Pdf::Text::TextRenderingMode enum"
linktitle: "TextRenderingMode"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Text::TextRenderingMode enum. Режим отображения текста, Tmode, определяет, будет ли отображение текста вызывать обводку контуров глифов, их заполнение, использование в качестве границы обрезки или комбинацию этих трёх вариантов в C++."
type: docs
weight: 6100
url: /ru/cpp/aspose.pdf.text/textrenderingmode/
---
## TextRenderingMode enum


Режим отображения текста, Tmode, определяет, будет ли отображение текста вызывать обводку контуров глифов, их заполнение, использование в качестве границы обрезки или любую комбинацию этих трёх вариантов.

```cpp
enum class TextRenderingMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| FillText | 0 | Заполняет текст. |
| StrokeText | 1 | Обводит текст. |
| FillThenStrokeText | 2 | Заполняет, затем обводит текст. |
| Невидимый | 3 | Не заполняет и не обводит текст (невидимый). |
| FillTextAndAddPathToClipping | 4 | Заполняет текст и добавляет в путь для обрезки (см. 9.3.6, "Text Rendering Mode,"). |
| StrokeTextAndAddPathToClipping | 5 | Обводит текст и добавляет в путь для обрезки. |
| FillThenStrokeTextAndAddPathToClipping | 6 | Заполняет, затем обводит текст и добавляет в путь для обрезки. |
| AddPathToClipping | 7 | Добавляет текст в путь для обрезки. |

## См. также

* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
