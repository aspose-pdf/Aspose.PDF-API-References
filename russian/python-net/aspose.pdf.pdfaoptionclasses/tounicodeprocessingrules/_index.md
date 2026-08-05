---
title: "ToUnicodeProcessingRules"
second_title: "Aspose.PDF for Python via .NET справочник API"
description: "Этот класс описывает правила, которые могут быть использованы для решения ошибки Adobe Preflight <br/>            \"Текст нельзя сопоставить с Unicode\"."
type: docs
weight: 20
url: /ru/python-net/aspose.pdf.pdfaoptionclasses/tounicodeprocessingrules/
---

## ToUnicodeProcessingRules class

Этот класс описывает правила, которые могут быть использованы для решения ошибки Adobe Preflight <br/>            "Текст нельзя сопоставить с Unicode".

Тип ToUnicodeProcessingRules раскрывает следующие члены:
## Конструкторы
| Имя | Описание |
| :- | :- |
| ToUnicodeProcessingRules() | Конструктор |
| ToUnicodeProcessingRules(remove_spaces) | Инициализирует новый экземпляр класса ToUnicodeProcessingRules |
| ToUnicodeProcessingRules(remove_spaces, map_non_linked_unicodes_on_space) | Инициализирует новый экземпляр класса ToUnicodeProcessingRules |
## Свойства
| Имя | Описание |
| :- | :- |
| remove_spaces_from_c_map_names | Некоторые шрифты имеют карты кодов символов ToUnicode с пробелами в названиях. Эти пробелы могут вызывать ошибки<br/>            при сопоставлении текста Unicode. Этот флаг указывает удалять пробелы из названий карт кодов символов ToUnicode.<br/>            По умолчанию false. |
| map_non_linked_symbols_on_space | Некоторые шрифты не предоставляют информацию о Unicode для некоторых текстовых символов. <br/>            Отсутствие этой информации вызывает ошибку "Text cannot be mapped to Unicode".<br/>            Используйте этот флаг, чтобы сопоставлять несвязанные символы с Unicode "space" (код 32). |

### См. также

* namespace [aspose.pdf.pdfaoptionclasses](/pdf/python-net/aspose.pdf.pdfaoptionclasses/)
* assembly [Aspose.PDF](/pdf/python-net/)

