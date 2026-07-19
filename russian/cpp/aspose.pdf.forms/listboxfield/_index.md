---
title: "Aspose::Pdf::Forms::ListBoxField класс"
linktitle: "ListBoxField"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Forms::ListBoxField класс. Класс представляет поле ListBox в C++."
type: docs
weight: 1300
url: /ru/cpp/aspose.pdf.forms/listboxfield/
---
## ListBoxField class


Класс представляет поле ListBox.

```cpp
class ListBoxField : public Aspose::Pdf::Forms::ChoiceField
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_TopIndex](./get_topindex/)() | Получает индекс верхнего видимого элемента списка. |
| [ListBoxField](./listboxfield/)() | Конструктор для [ListBoxField](./), используемый в Generator. |
| [ListBoxField](./listboxfield/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Создаёт новое поле ListBox. |
| [ListBoxField](./listboxfield/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Rectangle\>\&) | Конструктор для поля ListBox. |
| [set_Selected](./set_selected/)(int32_t) override | Устанавливает индекс выбранного элемента. Элементы нумеруются с 1. |
| [set_SelectedItems](./set_selecteditems/)(System::ArrayPtr\<int32_t\>) override | Устанавливает массив выбранных элементов в списке с множественным выбором. Для списка с одиночным выбором возвращает массив с одним элементом. |
| [set_TopIndex](./set_topindex/)(int32_t) | Устанавливает индекс верхнего видимого элемента списка. |
## См. также

* Class [ChoiceField](../choicefield/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
