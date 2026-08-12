---
title: "Класс Aspose::Pdf::Facades::FormFieldFacade"
linktitle: "FormFieldFacade"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Facades::FormFieldFacade. Класс для представления свойств полей в C++."
type: docs
weight: 1100
url: /ru/cpp/aspose.pdf.facades/formfieldfacade/
---
## FormFieldFacade class


Класс для представления свойств поля.

```cpp
class FormFieldFacade : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [FormFieldFacade](./formfieldfacade/)() |  |
| [get_Alignment](./get_alignment/)() const | Выравнивание текста поля, по умолчанию — выравнивание по левому краю. |
| [get_BackgroundColor](./get_backgroundcolor/)() const | Цвет фона поля, по умолчанию — белый. |
| [get_BorderColor](./get_bordercolor/)() const | Цвет границы поля. |
| [get_BorderStyle](./get_borderstyle/)() const | Стиль границы поля. |
| [get_BorderWidth](./get_borderwidth/)() const | Ширина границы поля. |
| [get_Box](./get_box/)() const | Объект прямоугольника, содержащий расположение поля. |
| [get_ButtonStyle](./get_buttonstyle/)() const | Стиль поля флажка или переключателя, определённый в FormFieldFacade.CheckBoxStyle*. |
| [get_Caption](./get_caption/)() const | Нормальная подпись поля формы. |
| [get_CustomFont](./get_customfont/)() const | Получает имя шрифта, когда он не‑стандартный (не один из 14 стандартных шрифтов). |
| [get_ExportItems](./get_exportitems/)() const | Опции для добавления списка/комбо‑поля/переключателя. |
| [get_Font](./get_font/)() const | Тип шрифта текста поля. |
| [get_FontSize](./get_fontsize/)() const | Размер текста поля. |
| [get_Items](./get_items/)() const | Массив строк, каждая из которых представляет вариант поля комбобокса/списка/переключателя. |
| [get_PageNumber](./get_pagenumber/)() const | Целочисленное значение, содержащее номер страницы, на которой находится поле. |
| [get_Position](./get_position/)() const | Объект прямоугольника, содержащий расположение поля. |
| [get_Rotation](./get_rotation/)() const | Поворот текста поля. |
| [get_TextColor](./get_textcolor/)() const | Цвет текста поля. |
| [get_TextEncoding](./get_textencoding/)() const | Тип кодировки текста поля. |
| [Reset](./reset/)() | Сбрасывает все визуальные атрибуты в пустое значение. |
| [set_Alignment](./set_alignment/)(int32_t) | Выравнивание текста поля, по умолчанию — выравнивание по левому краю. |
| [set_BackgroundColor](./set_backgroundcolor/)(System::Drawing::Color) | Цвет фона поля, по умолчанию — белый. |
| [set_BorderColor](./set_bordercolor/)(System::Drawing::Color) | Цвет границы поля. |
| [set_BorderStyle](./set_borderstyle/)(int32_t) | Стиль границы поля. |
| [set_BorderWidth](./set_borderwidth/)(float) | Ширина границы поля. |
| [set_Box](./set_box/)(System::Drawing::Rectangle) | Объект прямоугольника, содержащий расположение поля. |
| [set_ButtonStyle](./set_buttonstyle/)(int32_t) | Стиль поля флажка или переключателя, определённый в FormFieldFacade.CheckBoxStyle*. |
| [set_Caption](./set_caption/)(const System::String\&) | Нормальная подпись поля формы. |
| [set_CustomFont](./set_customfont/)(const System::String\&) | Устанавливает имя шрифта, когда он не‑стандартный (не один из 14 стандартных шрифтов). |
| [set_ExportItems](./set_exportitems/)(const System::ArrayPtr\<System::ArrayPtr\<System::String\>\>\&) | Опции для добавления списка/комбо‑поля/переключателя. |
| [set_Font](./set_font/)(FontStyle) | Тип шрифта текста поля. |
| [set_FontSize](./set_fontsize/)(float) | Размер текста поля. |
| [set_Items](./set_items/)(const System::ArrayPtr\<System::String\>\&) | Массив строк, каждая из которых представляет вариант поля комбобокса/списка/переключателя. |
| [set_PageNumber](./set_pagenumber/)(int32_t) | Целочисленное значение, содержащее номер страницы, на которой находится поле. |
| [set_Position](./set_position/)(const System::ArrayPtr\<float\>\&) | Объект прямоугольника, содержащий расположение поля. |
| [set_Rotation](./set_rotation/)(int32_t) | Поворот текста поля. |
| [set_TextColor](./set_textcolor/)(System::Drawing::Color) | Цвет текста поля. |
| [set_TextEncoding](./set_textencoding/)(EncodingType) | Тип кодировки текста поля. |
## Поля

| Поле | Описание |
| --- | --- |
| static constexpr [AlignBottom](./alignbottom/) | Определяет вертикальное выравнивание как нижний стиль. |
| static constexpr [AlignCenter](./aligncenter/) | Определяет выравнивание по центру. |
| static constexpr [AlignJustified](./alignjustified/) | Определяет стиль выравнивания текста по ширине. |
| static constexpr [AlignLeft](./alignleft/) | Определяет выравнивание по левому краю. |
| static constexpr [AlignMiddle](./alignmiddle/) | Определяет вертикальное выравнивание как средний стиль. |
| static constexpr [AlignRight](./alignright/) | Определяет выравнивание по правому краю. |
| static constexpr [AlignTop](./aligntop/) | Определяет вертикальное выравнивание как верхний стиль. |
| static constexpr [AlignUndefined](./alignundefined/) | Неопределённый стиль выравнивания. |
| static constexpr [BorderStyleBeveled](./borderstylebeveled/) | Определяет стиль с фаской границы. |
| static constexpr [BorderStyleDashed](./borderstyledashed/) | Определяет пунктирный стиль границы. |
| static constexpr [BorderStyleInset](./borderstyleinset/) | Определяет врезанный стиль границы. |
| static constexpr [BorderStyleSolid](./borderstylesolid/) | Определяет сплошной стиль границы. |
| static constexpr [BorderStyleUndefined](./borderstyleundefined/) | Неопределённый стиль границы. |
| static constexpr [BorderStyleUnderline](./borderstyleunderline/) | Определяет подчёркнутый стиль границы. |
| static constexpr [BorderWidthMedium](./borderwidthmedium/) | Определяет среднюю ширину границы. |
| static constexpr [BorderWidthThick](./borderwidththick/) | Определяет толстую ширину границы. |
| static constexpr [BorderWidthThin](./borderwidththin/) | Определяет тонкую ширину границы. |
| static constexpr [BorderWidthUndefined](./borderwidthundefined/) | Неопределённая ширина границы. |
| static constexpr [CheckBoxStyleCheck](./checkboxstylecheck/) | Определяет форму поля флажка, когда он отмечен. |
| static constexpr [CheckBoxStyleCircle](./checkboxstylecircle/) | Определяет стиль круглого флажка. |
| static constexpr [CheckBoxStyleCross](./checkboxstylecross/) | Определяет стиль крестового флажка. |
| static constexpr [CheckBoxStyleDiamond](./checkboxstylediamond/) | Определяет стиль ромбовидного флажка. |
| static constexpr [CheckBoxStyleSquare](./checkboxstylesquare/) | Определяет стиль квадратного флажка. |
| static constexpr [CheckBoxStyleStar](./checkboxstylestar/) | Определяет стиль звёздного флажка. |
| static constexpr [CheckBoxStyleUndefined](./checkboxstyleundefined/) | Определяет неопределённый стиль флажка. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
