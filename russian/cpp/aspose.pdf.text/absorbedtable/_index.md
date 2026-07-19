---
title: "Класс Aspose::Pdf::Text::AbsorbedTable"
linktitle: "AbsorbedTable"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Text::AbsorbedTable. Представляет таблицу, существующую на странице в C++."
type: docs
weight: 300
url: /ru/cpp/aspose.pdf.text/absorbedtable/
---
## AbsorbedTable class


Представляет таблицу, существующую на странице.

```cpp
class AbsorbedTable : public Aspose::Pdf::Text::ITableElement,
                      public System::IComparable<System::SharedPtr<AbsorbedTable>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [CompareTo](./compareto/)(System::SharedPtr\<AbsorbedTable\>) override | Сравнивает текущий объект [AbsorbedTable](./) с другим объектом [AbsorbedTable](./) и возвращает целое число, указывающее, предшествует ли текущий объект, следует за ним или находится в том же положении в порядке сортировки, что и другой объект. |
| [get_PageNum](./get_pagenum/)() const | Получает номер страницы, содержащей эту таблицу. |
| [get_Rectangle](./get_rectangle/)() override | Получает прямоугольник, описывающий положение таблицы на странице. |
| [get_RowList](./get_rowlist/)() | Получает только для чтения IList, содержащий строки таблицы. |
## См. также

* Class [ITableElement](../itableelement/)
* Class [IComparable](../../system/icomparable/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
