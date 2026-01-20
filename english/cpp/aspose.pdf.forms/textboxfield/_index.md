---
title: Aspose::Pdf::Forms::TextBoxField class
linktitle: TextBoxField
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Forms::TextBoxField class. Class representing text box field in C++.'
type: docs
weight: 2900
url: /cpp/aspose.pdf.forms/textboxfield/
---
## TextBoxField class


Class representing text box field.

```cpp
class TextBoxField : public Aspose::Pdf::Forms::Field
```

## Methods

| Method | Description |
| --- | --- |
| [AddBarcode](./addbarcode/)(System::String) | Adds barcode 128 into the field. [Field](../field/) value will be changed onto the code and field become read only. |
| [AddImage](./addimage/)(System::SharedPtr\<System::Drawing::Image\>) | Adds image into the field resources and draws it. |
| [get_ForceCombs](./get_forcecombs/)() | Gets flag which indicates is field divided into spaced positions. |
| [get_MaxLen](./get_maxlen/)() | Gets maximum length of text in the field. |
| [get_Multiline](./get_multiline/)() | Gets multiline flag of the field. If Multiline is true field can contain multiple lines of text. |
| [get_Scrollable](./get_scrollable/)() | Gets scrollable flag of field. If true field can be scrolled. |
| [get_SpellCheck](./get_spellcheck/)() | Gets spellcheck flag for field. If true field shall be spell checked. |
| [get_TextVerticalAlignment](./get_textverticalalignment/)() const | Gets text vertical alignment for annotation. |
| [get_Value](./get_value/)() override | Gets value of the field. |
| [set_ForceCombs](./set_forcecombs/)(bool) | Sets flag which indicates is field divided into spaced positions. |
| [set_MaxLen](./set_maxlen/)(int32_t) | Sets maximum length of text in the field. |
| [set_Multiline](./set_multiline/)(bool) | Sets multiline flag of the field. If Multiline is true field can contain multiple lines of text. |
| [set_Scrollable](./set_scrollable/)(bool) | Sets scrollable flag of field. If true field can be scrolled. |
| [set_SpellCheck](./set_spellcheck/)(bool) | Sets spellcheck flag for field. If true field shall be spell checked. |
| [set_TextVerticalAlignment](./set_textverticalalignment/)(Aspose::Pdf::VerticalAlignment) | Sets text vertical alignment for annotation. |
| [set_Value](./set_value/)(System::String) override | Sets value of the field. |
| [TextBoxField](./textboxfield/)(System::SharedPtr\<Document\>) | Constructor which should be used with Generator. |
| [TextBoxField](./textboxfield/)() | Create instance of [TextBoxField](./). |
| [TextBoxField](./textboxfield/)(System::SharedPtr\<Aspose::Pdf::Page\>, System::SharedPtr\<Rectangle\>) | Constructor of TextBox field. |
| [TextBoxField](./textboxfield/)(System::SharedPtr\<Aspose::Pdf::Page\>, System::ArrayPtr\<System::SharedPtr\<Rectangle\>\>) | Constructor of TextBox field. |
| [TextBoxField](./textboxfield/)(System::SharedPtr\<Document\>, System::SharedPtr\<Rectangle\>) | Constructor of TextBox field. |
## See Also

* Class [Field](../field/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
