---
title: "TextFragment"
second_title: "Aspose.PDF for Python via .NET справочник API"
description: "Представляет фрагмент текста PDF."
type: docs
weight: 390
url: /ru/python-net/aspose.pdf.text/textfragment/
---

## TextFragment class

Представляет фрагмент текста PDF.

Тип TextFragment раскрывает следующие члены:
## Конструкторы
| Имя | Описание |
| :- | :- |
| TextFragment() | Инициализирует новый экземпляр объекта [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| TextFragment(tab_stops) | Инициализирует новый экземпляр класса TextFragment |
| TextFragment(text) | Инициализирует новый экземпляр класса TextFragment |
| TextFragment(text, tab_stops) | Инициализирует новый экземпляр класса TextFragment |
## Свойства
| Имя | Описание |
| :- | :- |
| vertical_alignment | Получает или задает вертикальное выравнивание фрагмента текста. |
| horizontal_alignment | Получает или задает горизонтальное выравнивание фрагмента текста. |
| margin | Получает или задает внешний отступ для абзаца (для генерации PDF) |
| is_first_paragraph_in_column | Получает или задает значение типа bool, указывающее, будет ли этот абзац в следующей колонке.<br/>            По умолчанию false. (для генерации PDF) |
| is_kept_with_next | Получает или задает значение типа bool, указывающее, останется ли текущий абзац на той же странице вместе со следующим абзацем.<br/>            По умолчанию false. (для генерации PDF) |
| is_in_new_page | Получает или задает значение типа bool, принуждающее этот абзац генерироваться на новой странице.<br/>            По умолчанию false. (для генерации PDF) |
| is_in_line_paragraph | Получает или задает, является ли абзац встроенным.<br/>            По умолчанию false. (для генерации PDF) |
| hyperlink | Устанавливает гиперссылку фрагмента |
| z_index | Получает или задает целочисленное значение, указывающее порядок Z графа. Граф с большим ZIndex <br/> будет размещён над графом с меньшим ZIndex. ZIndex может быть отрицательным. Граф с отрицательным <br/> ZIndex будет размещён позади текста на странице. |
| replace_options | Получает параметры замены текста. Параметры определяют поведение при замене текста фрагмента на более короткий/длинный. |
| text | Получает или задает строковый объект текста, который представляет объект [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| text_state | Получает или задает состояние текста для текста, который представляет объект [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| segments | Получает сегменты текста для текущего [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| position | Получает или задает позицию текста для текста, представленного объектом [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| baseline_position | Получает позицию текста для текста, представленного объектом [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/).<br/>            YIndent структуры Position представляет координату базовой линии фрагмента текста. |
| rectangle | Получает прямоугольник TextFragment |
| страница | Получает страницу, содержащую TextFragment |
| форма | Получает объект формы, содержащий TextFragment |
| wrap_lines_count | Получает или задает количество переносимых строк для этого абзаца (только для генерации PDF) |
| end_note | Получает или задает конец примечания абзаца.(только для генерации PDF) |
| foot_note | Получает или задает сноску абзаца.(только для генерации PDF) |
## Методы
| Имя | Описание |
| :- | :- |
| clone() | Клонировать фрагмент. |
| isolate_text_segments(start_index, length) | Получает [TextSegment](/pdf/python-net/aspose.pdf.text/textsegment/)(ы), представляющие указанную часть текста [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| clone_with_segments() | Клонировать фрагмент со всеми сегментами. |

### См. также

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

