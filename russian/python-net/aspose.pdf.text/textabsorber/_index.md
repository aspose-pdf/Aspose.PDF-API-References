---
title: "TextAbsorber"
second_title: "Aspose.PDF for Python via .NET справочник API"
description: "Представляет объект‑поглотитель текста.<br/>            Выполняет извлечение текста и предоставляет доступ к результату через объект [text](/pdf/python-net/aspose.pdf.text/textabsorber/)."
type: docs
weight: 320
url: /ru/python-net/aspose.pdf.text/textabsorber/
---

## TextAbsorber class

Представляет объект‑поглотитель текста.<br/>            Выполняет извлечение текста и предоставляет доступ к результату через объект [text](/pdf/python-net/aspose.pdf.text/textabsorber/).

Тип TextAbsorber раскрывает следующие члены:
## Конструкторы
| Имя | Описание |
| :- | :- |
| TextAbsorber() | Инициализирует новый экземпляр [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/). |
| TextAbsorber(extraction_options) | Инициализирует новый экземпляр класса TextAbsorber |
| TextAbsorber(extraction_options, text_search_options) | Инициализирует новый экземпляр класса TextAbsorber |
| TextAbsorber(text_search_options) | Инициализирует новый экземпляр класса TextAbsorber |
## Свойства
| Имя | Описание |
| :- | :- |
| text | Получает извлечённый текст, который [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) извлекает из PDF‑документа или страницы. |
| has_errors | Значение указывает, были ли найдены ошибки во время извлечения текста.<br/>            Поиск ошибок будет выполнен только если TextSearchOptions.LogTextExtractionErrors = true; И это может снизить производительность. |
| errors | Список объектов [TextExtractionError](/pdf/python-net/aspose.pdf.text/textextractionerror/). Он содержит информацию об ошибках, найденных во время извлечения текста.<br/>            Поиск ошибок будет выполнен только если TextSearchOptions.LogTextExtractionErrors = true; И это может снизить производительность. |
| extraction_options | Получает или задает параметры извлечения текста. |
| text_search_options | Получает или задает параметры поиска текста. |
## Методы
| Имя | Описание |
| :- | :- |
| visit(page) | Извлекает текст на указанной странице |
| visit(form) | Извлекает текст из указанного XForm. |
| visit(pdf) | Извлекает текст из указанного документа |

### См. также

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

