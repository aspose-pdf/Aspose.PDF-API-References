---
title: "Aspose::Pdf::Facades::FormFieldFacade class"
linktitle: "FormFieldFacade"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Facades::FormFieldFacade. Clase para representar propiedades de campo en C++."
type: docs
weight: 1100
url: /es/cpp/aspose.pdf.facades/formfieldfacade/
---
## FormFieldFacade class


Clase para representar las propiedades del campo.

```cpp
class FormFieldFacade : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [FormFieldFacade](./formfieldfacade/)() |  |
| [get_Alignment](./get_alignment/)() const | La alineación del texto de un campo, por defecto es alineación a la izquierda. |
| [get_BackgroundColor](./get_backgroundcolor/)() const | El color del fondo de un campo, por defecto es blanco. |
| [get_BorderColor](./get_bordercolor/)() const | El color del borde del campo. |
| [get_BorderStyle](./get_borderstyle/)() const | El estilo del borde del campo. |
| [get_BorderWidth](./get_borderwidth/)() const | El ancho del borde del campo. |
| [get_Box](./get_box/)() const | Un objeto rectángulo que contiene la ubicación del campo. |
| [get_ButtonStyle](./get_buttonstyle/)() const | El estilo del campo de casilla de verificación o botón de opción, definido por FormFieldFacade.CheckBoxStyle*. |
| [get_Caption](./get_caption/)() const | El título normal del campo de formulario. |
| [get_CustomFont](./get_customfont/)() const | Obtiene el nombre de la fuente cuando no es estándar (distinto de las 14 fuentes estándar). |
| [get_ExportItems](./get_exportitems/)() const | Las opciones para agregar una lista/combo/botón de opción. |
| [get_Font](./get_font/)() const | El tipo de fuente del texto del campo. |
| [get_FontSize](./get_fontsize/)() const | El tamaño del texto del campo. |
| [get_Items](./get_items/)() const | Una matriz de cadenas, cada una representando una opción de un campo de lista/combo/botón de opción. |
| [get_PageNumber](./get_pagenumber/)() const | Un valor entero que indica el número de página en la que se encuentra el campo. |
| [get_Position](./get_position/)() const | Un objeto rectángulo que contiene la ubicación del campo. |
| [get_Rotation](./get_rotation/)() const | La rotación del texto del campo. |
| [get_TextColor](./get_textcolor/)() const | El color del texto del campo. |
| [get_TextEncoding](./get_textencoding/)() const | El tipo de codificación de texto del campo. |
| [Reset](./reset/)() | Restablecer todos los atributos visuales a valor vacío. |
| [set_Alignment](./set_alignment/)(int32_t) | La alineación del texto de un campo, por defecto es alineación a la izquierda. |
| [set_BackgroundColor](./set_backgroundcolor/)(System::Drawing::Color) | El color del fondo de un campo, por defecto es blanco. |
| [set_BorderColor](./set_bordercolor/)(System::Drawing::Color) | El color del borde del campo. |
| [set_BorderStyle](./set_borderstyle/)(int32_t) | El estilo del borde del campo. |
| [set_BorderWidth](./set_borderwidth/)(float) | El ancho del borde del campo. |
| [set_Box](./set_box/)(System::Drawing::Rectangle) | Un objeto rectángulo que contiene la ubicación del campo. |
| [set_ButtonStyle](./set_buttonstyle/)(int32_t) | El estilo del campo de casilla de verificación o botón de opción, definido por FormFieldFacade.CheckBoxStyle*. |
| [set_Caption](./set_caption/)(const System::String\&) | El título normal del campo de formulario. |
| [set_CustomFont](./set_customfont/)(const System::String\&) | Establece el nombre de la fuente cuando no es estándar (distinto de las 14 fuentes estándar). |
| [set_ExportItems](./set_exportitems/)(const System::ArrayPtr\<System::ArrayPtr\<System::String\>\>\&) | Las opciones para agregar una lista/combo/botón de opción. |
| [set_Font](./set_font/)(FontStyle) | El tipo de fuente del texto del campo. |
| [set_FontSize](./set_fontsize/)(float) | El tamaño del texto del campo. |
| [set_Items](./set_items/)(const System::ArrayPtr\<System::String\>\&) | Una matriz de cadenas, cada una representando una opción de un campo de lista/combo/botón de opción. |
| [set_PageNumber](./set_pagenumber/)(int32_t) | Un valor entero que indica el número de página en la que se encuentra el campo. |
| [set_Position](./set_position/)(const System::ArrayPtr\<float\>\&) | Un objeto rectángulo que contiene la ubicación del campo. |
| [set_Rotation](./set_rotation/)(int32_t) | La rotación del texto del campo. |
| [set_TextColor](./set_textcolor/)(System::Drawing::Color) | El color del texto del campo. |
| [set_TextEncoding](./set_textencoding/)(EncodingType) | El tipo de codificación de texto del campo. |
## Campos

| Campo | Descripción |
| --- | --- |
| static constexpr [AlignBottom](./alignbottom/) | Define la alineación vertical como estilo inferior. |
| static constexpr [AlignCenter](./aligncenter/) | Define la alineación al estilo centrado. |
| static constexpr [AlignJustified](./alignjustified/) | Define el estilo de alineación de justificación de texto. |
| static constexpr [AlignLeft](./alignleft/) | Define la alineación al estilo izquierdo. |
| static constexpr [AlignMiddle](./alignmiddle/) | Define la alineación vertical como estilo medio. |
| static constexpr [AlignRight](./alignright/) | Define la alineación a la derecha. |
| static constexpr [AlignTop](./aligntop/) | Define la alineación vertical como estilo superior. |
| static constexpr [AlignUndefined](./alignundefined/) | Estilo de alineación indefinido. |
| static constexpr [BorderStyleBeveled](./borderstylebeveled/) | Define un estilo de borde biselado. |
| static constexpr [BorderStyleDashed](./borderstyledashed/) | Define un estilo de borde punteado. |
| static constexpr [BorderStyleInset](./borderstyleinset/) | Define un estilo de borde incrustado. |
| static constexpr [BorderStyleSolid](./borderstylesolid/) | Define un estilo de borde sólido. |
| static constexpr [BorderStyleUndefined](./borderstyleundefined/) | Estilo de borde indefinido. |
| static constexpr [BorderStyleUnderline](./borderstyleunderline/) | Define un estilo de borde subrayado. |
| static constexpr [BorderWidthMedium](./borderwidthmedium/) | Define un ancho de borde medio. |
| static constexpr [BorderWidthThick](./borderwidththick/) | Define un ancho de borde grueso. |
| static constexpr [BorderWidthThin](./borderwidththin/) | Define un ancho de borde fino. |
| static constexpr [BorderWidthUndefined](./borderwidthundefined/) | Ancho de borde indefinido. |
| static constexpr [CheckBoxStyleCheck](./checkboxstylecheck/) | Define la forma del campo de casilla de verificación cuando está marcada. |
| static constexpr [CheckBoxStyleCircle](./checkboxstylecircle/) | Define un estilo de casilla de verificación circular. |
| static constexpr [CheckBoxStyleCross](./checkboxstylecross/) | Define un estilo de casilla de verificación cruzada. |
| static constexpr [CheckBoxStyleDiamond](./checkboxstylediamond/) | Define un estilo de casilla de verificación en forma de diamante. |
| static constexpr [CheckBoxStyleSquare](./checkboxstylesquare/) | Define un estilo de casilla de verificación cuadrada. |
| static constexpr [CheckBoxStyleStar](./checkboxstylestar/) | Define un estilo de casilla de verificación en forma de estrella. |
| static constexpr [CheckBoxStyleUndefined](./checkboxstyleundefined/) | Define un estilo de casilla de verificación indefinido. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
