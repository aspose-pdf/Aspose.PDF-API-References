---
title: "TextFragmentAbsorber"
second_title: "Aspose.PDF for Python via .NET справочник API"
description: "Представляет объект‑поглотитель текстовых фрагментов.<br/>            Выполняет поиск текста и предоставляет доступ к результатам поиска через коллекцию [text_fragments](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/)."
type: docs
weight: 400
url: /ru/python-net/aspose.pdf.text/textfragmentabsorber/
---

## TextFragmentAbsorber class

Представляет объект‑поглотитель текстовых фрагментов.<br/>            Выполняет поиск текста и предоставляет доступ к результатам поиска через коллекцию [text_fragments](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/).

Тип TextFragmentAbsorber раскрывает следующие члены:
## Конструкторы
| Имя | Описание |
| :- | :- |
| TextFragmentAbsorber() | Инициализирует новый экземпляр [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/), который выполняет поиск всех текстовых сегментов документа или страницы. |
| TextFragmentAbsorber(text_edit_options) | Инициализирует новый экземпляр класса TextFragmentAbsorber |
| TextFragmentAbsorber(phrase) | Инициализирует новый экземпляр класса TextFragmentAbsorber |
| TextFragmentAbsorber(phrase, text_search_options) | Инициализирует новый экземпляр класса TextFragmentAbsorber |
| TextFragmentAbsorber(phrase, text_search_options, text_edit_options) | Инициализирует новый экземпляр класса TextFragmentAbsorber |
| TextFragmentAbsorber(phrase, text_edit_options) | Инициализирует новый экземпляр класса TextFragmentAbsorber |
## Свойства
| Имя | Описание |
| :- | :- |
| text | Получает извлечённый текст, который [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) извлекает из PDF‑документа или страницы. |
| has_errors | Значение указывает, были ли найдены ошибки во время извлечения текста.<br/>            Поиск ошибок будет выполнен только если TextSearchOptions.LogTextExtractionErrors = true; И это может снизить производительность. |
| errors | Список объектов [TextExtractionError](/pdf/python-net/aspose.pdf.text/textextractionerror/). Он содержит информацию об ошибках, найденных во время извлечения текста.<br/>            Поиск ошибок будет выполнен только если TextSearchOptions.LogTextExtractionErrors = true; И это может снизить производительность. |
| extraction_options | Получает или задает параметры извлечения текста. |
| text_search_options | Получает или задает параметры поиска. Параметры позволяют выполнять поиск с использованием регулярных выражений. |
| text_fragments | Получает коллекцию вхождений поиска, представленных объектами [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| phrase | Получает или задает фразу, которую [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) ищет в PDF‑документе или на странице. |
| text_edit_options | Получает или задает параметры редактирования текста. Параметры определяют особое поведение, когда запрашиваемый символ нельзя отобразить выбранным шрифтом. |
| text_replace_options | Получает или задает параметры замены текста. Параметры определяют поведение, когда текст фрагмента заменяется на более короткий или более длинный. |
## Методы
| Имя | Описание |
| :- | :- |
| visit(page) | Выполняет поиск на указанной странице. |
| visit(pdf) | Выполняет поиск в указанном документе. |
| visit(x_form) | Выполняет поиск в указанном объекте формы. |
| apply_for_all_fragments(font) | Применяет шрифт ко всем поглощённым текстовым фрагментам. Это работает быстрее, чем перебор фрагментов, если все фрагменты на странице(ах) были поглощены. В противном случае работает аналогично перебору. |
| apply_for_all_fragments(font_size) | Применяет размер шрифта ко всем поглощённым текстовым фрагментам. Это работает быстрее, чем перебор фрагментов, если все фрагменты на странице(ах) были поглощены. В противном случае работает аналогично перебору. |
| apply_for_all_fragments(font, font_size) | Применяет шрифт и размер ко всем поглощённым текстовым фрагментам. Это работает быстрее, чем перебор фрагментов, если все фрагменты на странице(ах) были поглощены. В противном случае работает аналогично перебору. |
| remove_all_text(page) | Удаляет весь текст с указанной страницы. |
| remove_all_text(page, rect) | Удаляет текст внутри указанного прямоугольника на указанной странице. |
| remove_all_text(document) | Удаляет весь текст из документа. |
| reset() | Очищает коллекцию TextFragments этого объекта [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/). |

### См. также

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

