---
title: Aspose::Pdf::Forms::ListBoxField class
linktitle: ListBoxField
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Forms::ListBoxField class. Class represents ListBox field in C++.'
type: docs
weight: 1300
url: /cpp/aspose.pdf.forms/listboxfield/
---
## ListBoxField class


Class represents ListBox field.

```cpp
class ListBoxField : public Aspose::Pdf::Forms::ChoiceField
```

## Methods

| Method | Description |
| --- | --- |
| [get_TopIndex](./get_topindex/)() | Gets index of the top visible element of the list. |
| [ListBoxField](./listboxfield/)() | Constructor for [ListBoxField](./) to be used in Generator. |
| [ListBoxField](./listboxfield/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Creates new ListBox field. |
| [ListBoxField](./listboxfield/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Rectangle\>\&) | Constructor for ListBox field. |
| [set_Selected](./set_selected/)(int32_t) override | Sets index of the selected item. Items are numbered from 1. |
| [set_SelectedItems](./set_selecteditems/)(System::ArrayPtr\<int32_t\>) override | Sets array of the selected items in the multiselect list. For single-select list returns array with single item. |
| [set_TopIndex](./set_topindex/)(int32_t) | Sets index of the top visible element of the list. |
## See Also

* Class [ChoiceField](../choicefield/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
