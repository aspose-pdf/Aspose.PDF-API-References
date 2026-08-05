---
title: "TextState"
second_title: "Aspose.PDF for Python via .NET справочник API"
description: "Представляет состояние текста"
type: docs
weight: 490
url: /ru/python-net/aspose.pdf.text/textstate/
---

## TextState class

Представляет состояние текста

Тип TextState содержит следующие члены:
## Конструкторы
| Имя | Описание |
| :- | :- |
| TextState() | Создает объект состояния текста. |
| TextState(font_size) | Инициализирует новый экземпляр класса TextState |
| TextState(foreground_color) | Инициализирует новый экземпляр класса TextState |
| TextState(foreground_color, font_size) | Инициализирует новый экземпляр класса TextState |
| TextState(font_family) | Инициализирует новый экземпляр класса TextState |
| TextState(font_family, bold, italic) | Инициализирует новый экземпляр класса TextState |
| TextState(font_family, font_size) | Инициализирует новый экземпляр класса TextState |
## Свойства
| Имя | Описание |
| :- | :- |
| character_spacing | Получает или задает межсимвольный интервал текста. |
| line_spacing | Получает или задает межстрочный интервал текста. |
| horizontal_scaling | Получает или задает горизонтальное масштабирование текста. |
| subscript | Получает или задает нижний индекс текста. |
| superscript | Получает или задает верхний индекс текста. |
| word_spacing | Получает или задает интервал между словами текста. |
| invisible | Получает или задает невидимость текста. По сути это отражает состояние [rendering_mode](/pdf/python-net/aspose.pdf.text/textstate/), за исключением некоторых особых случаев (например, обрезка). |
| rendering_mode | Получает или задает режим рендеринга текста. |
| font_size | Получает или задает размер шрифта текста. |
| font | Получает или задает шрифт текста. |
| foreground_color | Получает или задает цвет переднего плана текста. |
| stroking_color | Получает или задает цвет переднего плана текста. |
| underline | Получает или задает подчеркивание текста, представленного объектом [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| strike_out | Устанавливает зачеркивание текста, представленного объектом [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| background_color | Устанавливает цвет фона текста. |
| font_style | Устанавливает стиль шрифта текста. |
| horizontal_alignment | Получает или задает горизонтальное выравнивание текста. |
| TAB_TAG | Вы можете разместить этот тег в тексте, чтобы объявить табуляцию. |
| TABSTOP_DEFAULT_VALUE | Значение табуляции по умолчанию в ширине символа пробела шрифта по умолчанию. |
## Методы
| Имя | Описание |
| :- | :- |
| apply_changes_from(text_state) | Применяет настройки из другого textState. |
| measure_string(str) | Измеряет строку. |

### См. также

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

