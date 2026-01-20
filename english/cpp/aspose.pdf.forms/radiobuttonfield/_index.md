---
title: Aspose::Pdf::Forms::RadioButtonField class
linktitle: RadioButtonField
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Forms::RadioButtonField class. Class representing radio button field in C++.'
type: docs
weight: 2100
url: /cpp/aspose.pdf.forms/radiobuttonfield/
---
## RadioButtonField class


Class representing radio button field.

```cpp
class RadioButtonField : public Aspose::Pdf::Forms::ChoiceField
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<RadioButtonOptionField\>\&) | Adds new option field to RadioButton field. |
| [AddOption](./addoption/)(System::String, System::SharedPtr\<Rectangle\>) | Add to radio button option with specifed rectangle. |
| [AddOption](./addoption/)(System::String) override | Add option to radion button. |
| [get_NoToggleToOff](./get_notoggletooff/)() | Get or sets the flag that allows the radiobutton to have no selected value. If **true**

, exactly one radio button shall be selected at all times; selecting the currently selected button has no effect. If **false**

, clicking the selected button deselects it, leaving no button selected. |
| [get_Options](./get_options/)() override | Gets collection of options of the radio button. |
| [get_PageIndex](./get_pageindex/)() override | Gets index of page which contains this RadioButton field. |
| [get_Selected](./get_selected/)() override | Gets index of selected item. Numbering of items is started from 1. |
| [get_Style](./get_style/)() | Style of field box. |
| [get_Value](./get_value/)() override | Gets value of field. |
| [RadioButtonField](./radiobuttonfield/)(System::SharedPtr\<Aspose::Pdf::Page\>) | Constructor for RadiouttonField. |
| [RadioButtonField](./radiobuttonfield/)(System::SharedPtr\<Document\>) | Constructor for [RadioButtonField](./). |
| [set_NoToggleToOff](./set_notoggletooff/)(bool) | Get or sets the flag that allows the radiobutton to have no selected value. If **true**

, exactly one radio button shall be selected at all times; selecting the currently selected button has no effect. If **false**

, clicking the selected button deselects it, leaving no button selected. |
| [set_Selected](./set_selected/)(int32_t) override | Sets index of selected item. Numbering of items is started from 1. |
| [set_Style](./set_style/)(BoxStyle) | Style of field box. |
| [set_Value](./set_value/)(System::String) override | Sets value of field. |
| [SetPosition](./setposition/)(System::SharedPtr\<Point\>) override | Move all subitems of radio button to specified positins on the page. |
## See Also

* Class [ChoiceField](../choicefield/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
