---
title: "Класс Aspose::Pdf::Forms::ChoiceField"
linktitle: "ChoiceField"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Forms::ChoiceField. Представляет базовый класс для полей выбора в C++."
type: docs
weight: 400
url: /ru/cpp/aspose.pdf.forms/choicefield/
---
## ChoiceField class


Представляет базовый класс для полей выбора.

```cpp
class ChoiceField : public Aspose::Pdf::Forms::Field
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [AddOption](./addoption/)(System::String) | Добавляет новую опцию с указанным именем. |
| virtual [AddOption](./addoption/)(System::String, System::String) | Добавляет новую опцию с указанным экспортным значением и именем. |
| [ChoiceField](./choicefield/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Конструктор для [ChoiceField](./). |
| [ChoiceField](./choicefield/)(const System::SharedPtr\<Document\>\&) | Создаёт поле выбора (для Generator) |
| [ChoiceField](./choicefield/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Rectangle\>\&) | Конструктор для [ChoiceField](./). |
| virtual [DeleteOption](./deleteoption/)(System::String) | Удаляет опцию по её имени. |
| [get_CommitImmediately](./get_commitimmediately/)() | Получает флаг подтверждения при изменении выбора. |
| [get_MultiSelect](./get_multiselect/)() | Получает флаг множественного выбора. |
| virtual [get_Options](./get_options/)() | Получает коллекцию вариантов выбора. |
| virtual [get_Selected](./get_selected/)() | Получает индекс выбранной опции. Это свойство позволяет изменить выбор. |
| virtual [get_SelectedItems](./get_selecteditems/)() | Получает массив выбранных элементов. Для списка с множественным выбором массив содержит более одного элемента. Для списка с одиночным выбором он содержит один элемент. |
| [get_Value](./get_value/)() override | Получает значение поля. |
| [set_CommitImmediately](./set_commitimmediately/)(bool) | Устанавливает флаг подтверждения при изменении выбора. |
| [set_MultiSelect](./set_multiselect/)(bool) | Устанавливает флаг множественного выбора. |
| virtual [set_Selected](./set_selected/)(int32_t) | Устанавливает индекс выбранной опции. Это свойство позволяет изменить выбор. |
| virtual [set_SelectedItems](./set_selecteditems/)(System::ArrayPtr\<int32_t\>) | Устанавливает массив выбранных элементов. Для списка с множественным выбором массив содержит более одного элемента. Для списка с одиночным выбором он содержит один элемент. |
| [set_Value](./set_value/)(System::String) override | Устанавливает значение поля. |
## См. также

* Class [Field](../field/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
