---
title: "Aspose::Pdf::Facades::FormFieldFacade-klass"
linktitle: "FormFieldFacade"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::FormFieldFacade-klass. Klass för att representera fältegenskaper i C++."
type: docs
weight: 1100
url: /sv/cpp/aspose.pdf.facades/formfieldfacade/
---
## FormFieldFacade class


Klass för att representera fältens egenskaper.

```cpp
class FormFieldFacade : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [FormFieldFacade](./formfieldfacade/)() |  |
| [get_Alignment](./get_alignment/)() const | Justeringen av ett fälttext, standard är vänsterjustering. |
| [get_BackgroundColor](./get_backgroundcolor/)() const | Färgen på ett fältbakgrund, standard är vit. |
| [get_BorderColor](./get_bordercolor/)() const | Färgen på ett fältkant. |
| [get_BorderStyle](./get_borderstyle/)() const | Stilen på ett fältkant. |
| [get_BorderWidth](./get_borderwidth/)() const | Bredden på ett fältkant. |
| [get_Box](./get_box/)() const | Ett rektangelobjekt som innehåller fältets position. |
| [get_ButtonStyle](./get_buttonstyle/)() const | Stilen på kryssruta- eller radioknappsfält, definierad av FormFieldFacade.CheckBoxStyle*. |
| [get_Caption](./get_caption/)() const | Den normala rubriken för formulärfältet. |
| [get_CustomFont](./get_customfont/)() const | Hämtar namn på teckensnittet när detta är icke‑standard (annat än de 14 standardteckensnitten). |
| [get_ExportItems](./get_exportitems/)() const | Alternativen för att lägga till en lista/kombo/radioknapp. |
| [get_Font](./get_font/)() const | Teckensnittstypen för ett fälttext. |
| [get_FontSize](./get_fontsize/)() const | Storleken på ett fälttext. |
| [get_Items](./get_items/)() const | En array av strängar, där varje representerar ett alternativ för ett kombinationsruta/lista/radioknappfält. |
| [get_PageNumber](./get_pagenumber/)() const | Ett heltal som innehåller sidnumret där fältet är placerat. |
| [get_Position](./get_position/)() const | Ett rektangelobjekt som innehåller fältets position. |
| [get_Rotation](./get_rotation/)() const | Roteringen av en fälttext. |
| [get_TextColor](./get_textcolor/)() const | Färgen på fälttexten. |
| [get_TextEncoding](./get_textencoding/)() const | Textkodningstypen för fälttexten. |
| [Reset](./reset/)() | Återställ alla visuella attribut till tomt värde. |
| [set_Alignment](./set_alignment/)(int32_t) | Justeringen av ett fälttext, standard är vänsterjustering. |
| [set_BackgroundColor](./set_backgroundcolor/)(System::Drawing::Color) | Färgen på ett fältbakgrund, standard är vit. |
| [set_BorderColor](./set_bordercolor/)(System::Drawing::Color) | Färgen på ett fältkant. |
| [set_BorderStyle](./set_borderstyle/)(int32_t) | Stilen på ett fältkant. |
| [set_BorderWidth](./set_borderwidth/)(float) | Bredden på ett fältkant. |
| [set_Box](./set_box/)(System::Drawing::Rectangle) | Ett rektangelobjekt som innehåller fältets position. |
| [set_ButtonStyle](./set_buttonstyle/)(int32_t) | Stilen på kryssruta- eller radioknappsfält, definierad av FormFieldFacade.CheckBoxStyle*. |
| [set_Caption](./set_caption/)(const System::String\&) | Den normala rubriken för formulärfältet. |
| [set_CustomFont](./set_customfont/)(const System::String\&) | Ställer in namn på teckensnittet när detta är icke‑standard (annat än 14 standardteckensnitt). |
| [set_ExportItems](./set_exportitems/)(const System::ArrayPtr\<System::ArrayPtr\<System::String\>\>\&) | Alternativen för att lägga till en lista/kombo/radioknapp. |
| [set_Font](./set_font/)(FontStyle) | Teckensnittstypen för ett fälttext. |
| [set_FontSize](./set_fontsize/)(float) | Storleken på ett fälttext. |
| [set_Items](./set_items/)(const System::ArrayPtr\<System::String\>\&) | En array av strängar, där varje representerar ett alternativ för ett kombinationsruta/lista/radioknappfält. |
| [set_PageNumber](./set_pagenumber/)(int32_t) | Ett heltal som innehåller sidnumret där fältet är placerat. |
| [set_Position](./set_position/)(const System::ArrayPtr\<float\>\&) | Ett rektangelobjekt som innehåller fältets position. |
| [set_Rotation](./set_rotation/)(int32_t) | Roteringen av en fälttext. |
| [set_TextColor](./set_textcolor/)(System::Drawing::Color) | Färgen på fälttexten. |
| [set_TextEncoding](./set_textencoding/)(EncodingType) | Textkodningstypen för fälttexten. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static constexpr [AlignBottom](./alignbottom/) | Definierar vertikal justering som bottenstil. |
| static constexpr [AlignCenter](./aligncenter/) | Definierar justering till centrerad stil. |
| static constexpr [AlignJustified](./alignjustified/) | Definierar textjusteringsstil. |
| static constexpr [AlignLeft](./alignleft/) | Definierar justering till vänsterstil. |
| static constexpr [AlignMiddle](./alignmiddle/) | Definierar vertikal justering som mittstil. |
| static constexpr [AlignRight](./alignright/) | Definierar justering till högerstil. |
| static constexpr [AlignTop](./aligntop/) | Definierar vertikal justering som toppstil. |
| static constexpr [AlignUndefined](./alignundefined/) | Odefinierad justeringsstil. |
| static constexpr [BorderStyleBeveled](./borderstylebeveled/) | Definierar en avfasad kantstil. |
| static constexpr [BorderStyleDashed](./borderstyledashed/) | Definierar en streckad kantstil. |
| static constexpr [BorderStyleInset](./borderstyleinset/) | Definierar en infälld kantstil. |
| static constexpr [BorderStyleSolid](./borderstylesolid/) | Definierar en solid kantstil. |
| static constexpr [BorderStyleUndefined](./borderstyleundefined/) | Odefinierad kantstil. |
| static constexpr [BorderStyleUnderline](./borderstyleunderline/) | Definierar en understruken kantstil. |
| static constexpr [BorderWidthMedium](./borderwidthmedium/) | Definierar en medelbredd på kanten. |
| static constexpr [BorderWidthThick](./borderwidththick/) | Definierar en tjock kantbredd. |
| static constexpr [BorderWidthThin](./borderwidththin/) | Definierar en tunn kantbredd. |
| static constexpr [BorderWidthUndefined](./borderwidthundefined/) | Odefinierad kantbredd. |
| static constexpr [CheckBoxStyleCheck](./checkboxstylecheck/) | Definierar formen på en kryssruta när den är markerad. |
| static constexpr [CheckBoxStyleCircle](./checkboxstylecircle/) | Definierar en cirkelkryssruta stil. |
| static constexpr [CheckBoxStyleCross](./checkboxstylecross/) | Definierar en korskryssruta stil. |
| static constexpr [CheckBoxStyleDiamond](./checkboxstylediamond/) | Definierar en diamantkryssruta‑stil. |
| static constexpr [CheckBoxStyleSquare](./checkboxstylesquare/) | Definierar en fyrkantig kryssruta‑stil. |
| static constexpr [CheckBoxStyleStar](./checkboxstylestar/) | Definierar en stjärnkryssruta‑stil. |
| static constexpr [CheckBoxStyleUndefined](./checkboxstyleundefined/) | Definierar en odefinierad kryssruta‑stil. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
