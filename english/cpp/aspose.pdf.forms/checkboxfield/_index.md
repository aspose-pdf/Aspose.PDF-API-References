---
title: Aspose::Pdf::Forms::CheckboxField class
linktitle: CheckboxField
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Forms::CheckboxField class. Class representing checkbox field in C++.'
type: docs
weight: 300
url: /cpp/aspose.pdf.forms/checkboxfield/
---
## CheckboxField class


Class representing checkbox field.

```cpp
class CheckboxField : public Aspose::Pdf::Forms::Field
```

## Methods

| Method | Description |
| --- | --- |
| [AddOption](./addoption/)(System::String) | Adds new checkbox into a checkbox group, in which at most one of the checkboxes may be checked at any time. The new checkbox is added to the bottom of the group. |
| [AddOption](./addoption/)(System::String, System::SharedPtr\<Rectangle\>) | Adds new checkbox into a checkbox group, in which at most one of the checkboxes may be checked at any time. |
| [AddOption](./addoption/)(System::String, int32_t, System::SharedPtr\<Rectangle\>) | Adds new checkbox into a checkbox group, in which at most one of the checkboxes may be checked at any time. |
| [CheckboxField](./checkboxfield/)(System::SharedPtr\<Aspose::Pdf::Page\>, System::SharedPtr\<Rectangle\>) | Constructor for [CheckboxField](./) class. |
| [CheckboxField](./checkboxfield/)(System::SharedPtr\<Document\>, System::SharedPtr\<Rectangle\>) | Constructor for [CheckboxField](./) class. |
| [CheckboxField](./checkboxfield/)() | Create instance of [CheckboxField](./). |
| [CheckboxField](./checkboxfield/)(System::SharedPtr\<Document\>) | Constructor to use with Generator. |
| [Clone](./clone/)() override | Clone the checkbox. |
| [get_ActiveState](./get_activestate/)() override | Gets current annotation appearance state. |
| [get_AllowedStates](./get_allowedstates/)() | Returns list of allowed states. |
| [get_Checked](./get_checked/)() | Gets state of check box. |
| [get_ExportValue](./get_exportvalue/)() | Gets export value of CheckBox field. |
| [get_Style](./get_style/)() | Gets style of check box. |
| [get_Value](./get_value/)() override | Gets value of check box field. |
| [set_ActiveState](./set_activestate/)(System::String) override | Sets current annotation appearance state. |
| [set_Checked](./set_checked/)(bool) | Sets state of check box. |
| [set_ExportValue](./set_exportvalue/)(System::String) | Sets export value of CheckBox field. |
| [set_Style](./set_style/)(BoxStyle) | Sets style of check box. |
| [set_Value](./set_value/)(System::String) override | Sets value of check box field. |
## See Also

* Class [Field](../field/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
