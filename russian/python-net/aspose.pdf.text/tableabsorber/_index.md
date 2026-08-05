---
title: "TableAbsorber"
second_title: "Aspose.PDF for Python via .NET справочник API"
description: "Представляет объект‑поглотитель элементов таблицы.<br/>            Выполняет поиск и предоставляет доступ к результатам поиска через коллекцию [table_list](/pdf/python-net/aspose.pdf.text/tableabsorber/)."
type: docs
weight: 310
url: /ru/python-net/aspose.pdf.text/tableabsorber/
---

## TableAbsorber class

Представляет объект‑поглотитель элементов таблицы.<br/>            Выполняет поиск и предоставляет доступ к результатам поиска через коллекцию [table_list](/pdf/python-net/aspose.pdf.text/tableabsorber/).

Тип TableAbsorber раскрывает следующие члены:
## Конструкторы
| Имя | Описание |
| :- | :- |
| TableAbsorber(text_search_options) | Инициализирует новый экземпляр класса TableAbsorber |
| TableAbsorber() | Инициализирует новый экземпляр [TableAbsorber](/pdf/python-net/aspose.pdf.text/tableabsorber/). |
## Свойства
| Имя | Описание |
| :- | :- |
| text_search_options | Получает или задает параметры поиска текста. |
| table_list | Возвращает только для чтения IList, содержащий найденные таблицы |
| use_flow_engine | * Активировать раннюю альфа-версию альтернативного движка распознавания таблиц, который может использоваться для конвертации таблиц <br/>            без границ.<br/>            Пока не поддерживает редактирование таблиц и получение стилей текста. Значение по умолчанию — false; |
## Методы
| Имя | Описание |
| :- | :- |
| visit(page) | Извлекает таблицы на указанной странице |
| remove(table) | Удаляет [AbsorbedTable](/pdf/python-net/aspose.pdf.text/absorbedtable/) со страницы. |
| replace(page, old_table, new_table) | Заменяет [AbsorbedTable](/pdf/python-net/aspose.pdf.text/absorbedtable/) на [Table](/pdf/python-net/aspose.pdf/table/) на странице. |

### См. также

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

