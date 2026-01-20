---
title: Aspose::Pdf::Facades::FormFieldFacade class
linktitle: FormFieldFacade
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::FormFieldFacade class. Class for representing field properties in C++.'
type: docs
weight: 1100
url: /cpp/aspose.pdf.facades/formfieldfacade/
---
## FormFieldFacade class


Class for representing field properties.

```cpp
class FormFieldFacade : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [FormFieldFacade](./formfieldfacade/)() |  |
| [get_Alignment](./get_alignment/)() const | The alignment of a field text, default is left alignment. |
| [get_BackgroundColor](./get_backgroundcolor/)() const | The color of a field background, default is white. |
| [get_BorderColor](./get_bordercolor/)() const | The color of a field border. |
| [get_BorderStyle](./get_borderstyle/)() const | The style of a field border. |
| [get_BorderWidth](./get_borderwidth/)() const | The width of a field border. |
| [get_Box](./get_box/)() const | A rectangle object holding field's location. |
| [get_ButtonStyle](./get_buttonstyle/)() const | The style of check box or radio box field, defined by FormFieldFacade.CheckBoxStyle*. |
| [get_Caption](./get_caption/)() const | The normal caption of form field. |
| [get_CustomFont](./get_customfont/)() const | Gets name of the font when this is non-standart (other then 14 standard fonts). |
| [get_ExportItems](./get_exportitems/)() const | The options for adding a list/combo/radio box. |
| [get_Font](./get_font/)() const | The font type of a field text. |
| [get_FontSize](./get_fontsize/)() const | The size of a field text. |
| [get_Items](./get_items/)() const | An array of string, each representing an option of a combo box/list/radio box field. |
| [get_PageNumber](./get_pagenumber/)() const | An integer value holding the number of page on which field locates. |
| [get_Position](./get_position/)() const | A rectangle object holding field's location. |
| [get_Rotation](./get_rotation/)() const | The rotation of a field text. |
| [get_TextColor](./get_textcolor/)() const | The color of the field text. |
| [get_TextEncoding](./get_textencoding/)() const | The text encoding type of the field text. |
| [Reset](./reset/)() | Reset all visual attribtues to empty value. |
| [set_Alignment](./set_alignment/)(int32_t) | The alignment of a field text, default is left alignment. |
| [set_BackgroundColor](./set_backgroundcolor/)(System::Drawing::Color) | The color of a field background, default is white. |
| [set_BorderColor](./set_bordercolor/)(System::Drawing::Color) | The color of a field border. |
| [set_BorderStyle](./set_borderstyle/)(int32_t) | The style of a field border. |
| [set_BorderWidth](./set_borderwidth/)(float) | The width of a field border. |
| [set_Box](./set_box/)(System::Drawing::Rectangle) | A rectangle object holding field's location. |
| [set_ButtonStyle](./set_buttonstyle/)(int32_t) | The style of check box or radio box field, defined by FormFieldFacade.CheckBoxStyle*. |
| [set_Caption](./set_caption/)(System::String) | The normal caption of form field. |
| [set_CustomFont](./set_customfont/)(System::String) | Sets name of the font when this is non-standart (other then 14 standard fonts). |
| [set_ExportItems](./set_exportitems/)(System::ArrayPtr\<System::ArrayPtr\<System::String\>\>) | The options for adding a list/combo/radio box. |
| [set_Font](./set_font/)(FontStyle) | The font type of a field text. |
| [set_FontSize](./set_fontsize/)(float) | The size of a field text. |
| [set_Items](./set_items/)(System::ArrayPtr\<System::String\>) | An array of string, each representing an option of a combo box/list/radio box field. |
| [set_PageNumber](./set_pagenumber/)(int32_t) | An integer value holding the number of page on which field locates. |
| [set_Position](./set_position/)(System::ArrayPtr\<float\>) | A rectangle object holding field's location. |
| [set_Rotation](./set_rotation/)(int32_t) | The rotation of a field text. |
| [set_TextColor](./set_textcolor/)(System::Drawing::Color) | The color of the field text. |
| [set_TextEncoding](./set_textencoding/)(EncodingType) | The text encoding type of the field text. |
## Fields

| Field | Description |
| --- | --- |
| static constexpr [AlignBottom](./alignbottom/) | Defines vertical aglignment as bottom style. |
| static constexpr [AlignCenter](./aligncenter/) | Defines aglignment to center style. |
| static constexpr [AlignJustified](./alignjustified/) | Defines text justification alignment style. |
| static constexpr [AlignLeft](./alignleft/) | Defines aglignment to left style. |
| static constexpr [AlignMiddle](./alignmiddle/) | Defines vertical aglignment as middle style. |
| static constexpr [AlignRight](./alignright/) | Defines aglignment to right style. |
| static constexpr [AlignTop](./aligntop/) | Defines vertical aglignment as top style. |
| static constexpr [AlignUndefined](./alignundefined/) | Undefined aglignment style. |
| static constexpr [BorderStyleBeveled](./borderstylebeveled/) | Defines a beveled border style. |
| static constexpr [BorderStyleDashed](./borderstyledashed/) | Defines a dashed border style. |
| static constexpr [BorderStyleInset](./borderstyleinset/) | Defines an inseted border style. |
| static constexpr [BorderStyleSolid](./borderstylesolid/) | Defines a solid border style. |
| static constexpr [BorderStyleUndefined](./borderstyleundefined/) | Undefined border style. |
| static constexpr [BorderStyleUnderline](./borderstyleunderline/) | Defines an underlined border style. |
| static constexpr [BorderWidthMedium](./borderwidthmedium/) | Defines a medium border width. |
| static constexpr [BorderWidthThick](./borderwidththick/) | Defines a thick border width. |
| static constexpr [BorderWidthThin](./borderwidththin/) | Defines a thin border width. |
| static constexpr [BorderWidthUndefined](./borderwidthundefined/) | Undefined border width. |
| static constexpr [CheckBoxStyleCheck](./checkboxstylecheck/) | Defines the shape of a check box field when it checked. |
| static constexpr [CheckBoxStyleCircle](./checkboxstylecircle/) | Defines a circle check box style. |
| static constexpr [CheckBoxStyleCross](./checkboxstylecross/) | Defines a cross check box style. |
| static constexpr [CheckBoxStyleDiamond](./checkboxstylediamond/) | Defines a diamond check box style. |
| static constexpr [CheckBoxStyleSquare](./checkboxstylesquare/) | Defines a square check box style. |
| static constexpr [CheckBoxStyleStar](./checkboxstylestar/) | Defines a star check box style. |
| static constexpr [CheckBoxStyleUndefined](./checkboxstyleundefined/) | Defines an undefined check box style. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
