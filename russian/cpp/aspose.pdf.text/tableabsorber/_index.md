---
title: "Aspose::Pdf::Text::TableAbsorber класс"
linktitle: "TableAbsorber"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Text::TableAbsorber класс. Представляет объект‑поглотитель элементов таблицы. Выполняет поиск и предоставляет доступ к результатам поиска через коллекцию TableAbsorber::TableList в C++."
type: docs
weight: 3300
url: /ru/cpp/aspose.pdf.text/tableabsorber/
---
## TableAbsorber class


Представляет объект-абсорбер элементов таблицы. Выполняет поиск и предоставляет доступ к результатам поиска через коллекцию [TableAbsorber::TableList](../).

```cpp
class TableAbsorber : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [get_TableList](./get_tablelist/)() | Возвращает только для чтения IList, содержащий найденные таблицы. |
| virtual [get_TextSearchOptions](./get_textsearchoptions/)() | Получает параметры поиска текста. |
| [get_UseFlowEngine](./get_useflowengine/)() const |  |
| [Remove](./remove/)(const System::SharedPtr\<AbsorbedTable\>\&) | Удаляет [AbsorbedTable](../absorbedtable/) со страницы. |
| [Replace](./replace/)(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<AbsorbedTable\>\&, const System::SharedPtr\<Table\>\&) | Заменяет [AbsorbedTable](../absorbedtable/) на [Table](../../aspose.pdf/table/) на странице. |
| virtual [set_TextSearchOptions](./set_textsearchoptions/)(System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>) | Устанавливает параметры поиска текста. |
| [set_UseFlowEngine](./set_useflowengine/)(bool) |  |
| [TableAbsorber](./tableabsorber/)(const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&) | Инициализирует новый экземпляр [TableAbsorber](./) с параметрами поиска текста. |
| [TableAbsorber](./tableabsorber/)() | Инициализирует новый экземпляр [TableAbsorber](./). |
| virtual [Visit](./visit/)(System::SharedPtr\<Page\>) | Извлекает таблицы на указанной странице. |
| [Visit](./visit/)(const System::SharedPtr\<Document\>\&) | Извлекает таблицы в указанном документе. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
