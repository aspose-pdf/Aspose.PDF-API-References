---
title: "класс Aspose::Pdf::Text::AbsorbedCell"
linktitle: "AbsorbedCell"
second_title: "Справочник API Aspose.PDF для C++"
description: "класс Aspose::Pdf::Text::AbsorbedCell. Представляет ячейку таблицы, существующей на странице в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.text/absorbedcell/
---
## AbsorbedCell class


Представляет ячейку таблицы, существующую на странице.

```cpp
class AbsorbedCell : public Aspose::Pdf::Text::ITableElement,
                     public System::IComparable<System::SharedPtr<AbsorbedCell>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [CompareTo](./compareto/)(System::SharedPtr\<AbsorbedCell\>) override | Сравнивает текущий объект [AbsorbedCell](./) с другим объектом [AbsorbedCell](./) и возвращает целое число, указывающее, предшествует ли текущий объект, следует за ним или находится в том же положении в порядке сортировки, что и другой объект. |
| [get_BorderInfo](./get_borderinfo/)() const | Возвращает информацию о границе ячейки, когда свойство FlowEngine.TableAbsorber.UseFlowEngine установлено в true. |
| [get_ColSpan](./get_colspan/)() const | Возвращает количество столбцов, которые должна охватывать ячейка, когда свойство TableAbsorber.UseFlowEngine установлено в true. |
| [get_Rectangle](./get_rectangle/)() override | Получает прямоугольник, описывающий положение ячейки на странице. |
| [get_TextFragments](./get_textfragments/)() const | Получает коллекцию объектов [TextFragment](../textfragment/), описывающих текст, содержащийся в ячейке. |
## См. также

* Class [ITableElement](../itableelement/)
* Class [IComparable](../../system/icomparable/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
