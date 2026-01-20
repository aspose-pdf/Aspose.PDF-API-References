---
title: Aspose::Pdf::Forms::ChoiceField class
linktitle: ChoiceField
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Forms::ChoiceField class. Represents base class for choice fields in C++.'
type: docs
weight: 400
url: /cpp/aspose.pdf.forms/choicefield/
---
## ChoiceField class


Represents base class for choice fields.

```cpp
class ChoiceField : public Aspose::Pdf::Forms::Field
```

## Methods

| Method | Description |
| --- | --- |
| virtual [AddOption](./addoption/)(System::String) | Adds new option with specified name. |
| virtual [AddOption](./addoption/)(System::String, System::String) | Adds new option with specified export value and name. |
| [ChoiceField](./choicefield/)(System::SharedPtr\<Aspose::Pdf::Page\>, System::SharedPtr\<Rectangle\>) | Constructor for [ChoiceField](./). |
| [ChoiceField](./choicefield/)(System::SharedPtr\<Document\>) | Creates choice field (for Generator) |
| [ChoiceField](./choicefield/)(System::SharedPtr\<Document\>, System::SharedPtr\<Rectangle\>) | Constructor for [ChoiceField](./). |
| virtual [DeleteOption](./deleteoption/)(System::String) | Deletes option by its name. |
| [get_CommitImmediately](./get_commitimmediately/)() | Gets commit on selection change flag. |
| [get_MultiSelect](./get_multiselect/)() | Gets multiselection flag. |
| virtual [get_Options](./get_options/)() | Gets collection of choice options. |
| virtual [get_Selected](./get_selected/)() | Gets index of selected option. This property allows to change selection. |
| virtual [get_SelectedItems](./get_selecteditems/)() | Gets array of selected items. For multiselect list array contains more then one item. For single selection list it contains single item. |
| [get_Value](./get_value/)() override | Gets value of the field. |
| [set_CommitImmediately](./set_commitimmediately/)(bool) | Sets commit on selection change flag. |
| [set_MultiSelect](./set_multiselect/)(bool) | Sets multiselection flag. |
| virtual [set_Selected](./set_selected/)(int32_t) | Sets index of selected option. This property allows to change selection. |
| virtual [set_SelectedItems](./set_selecteditems/)(System::ArrayPtr\<int32_t\>) | Sets array of selected items. For multiselect list array contains more then one item. For single selection list it contains single item. |
| [set_Value](./set_value/)(System::String) override | Sets value of the field. |
## See Also

* Class [Field](../field/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
