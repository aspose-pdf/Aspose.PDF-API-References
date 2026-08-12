---
title: "Aspose::Pdf::TextStamp clase"
linktitle: "TextStamp"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::TextStamp clase. Representa un sello textual en C++."
type: docs
weight: 18400
url: /es/cpp/aspose.pdf/textstamp/
---
## TextStamp class


Representa un sello textual.

```cpp
class TextStamp : public Aspose::Pdf::Stamp
```

## Enums

| Enumeración | Descripción |
| --- | --- |
| [NoCharacterAction](./nocharacteraction/) | Acción a realizar si la fuente no contiene el carácter requerido. |
## Métodos

| Método | Descripción |
| --- | --- |
| [get_AutoAdjustFontSizePrecision](./get_autoadjustfontsizeprecision/)() const | Ajustar automáticamente la precisión del tamaño de fuente. Valor predeterminado: 0.1;. |
| [get_AutoAdjustFontSizeToFitStampRectangle](./get_autoadjustfontsizetofitstamprectangle/)() const | Si está habilitado, el tamaño de fuente se ajustará automáticamente para encajar en el rectángulo del sello de tamaño: [Width](../) y [Height](../). El ancho y alto predeterminados se derivan del rectángulo de la página. |
| [get_Draw](./get_draw/)() const | Esta propiedad determina cómo se dibuja el sello en la página. Si Draw = true, el sello se dibuja como operadores gráficos y si draw = false, el sello se dibuja como texto. |
| [get_FontSize](./get_fontsize/)() | Tamaño de fuente real después de que el sello se haya colocado. (Puede diferir del tamaño de fuente inicial proporcionado a través del constructor si la opción 'AutoAdjustFontSizeToFitStampRectangle' está habilitada.) |
| [get_Height](./get_height/)() override | Altura deseada del sello en la página. |
| [get_Justify](./get_justify/)() | Define la justificación del texto. Si esta propiedad se establece en true, ambos bordes izquierdo y derecho del texto se alinean. Valor predeterminado: false. |
| [get_MaxRowWidth](./get_maxrowwidth/)() const | Altura máxima de fila para la opción WordWrap. |
| [get_NoCharacterBehavior](./get_nocharacterbehavior/)() const | Obtiene el modo que define el comportamiento en caso de que las fuentes no contengan los caracteres solicitados. |
| [get_ReplacementFont](./get_replacementfont/)() const | Obtiene la fuente utilizada para la sustitución si la fuente del usuario no contiene el carácter requerido. |
| [get_Scale](./get_scale/)() const | Define el escalado del texto. Si esta propiedad se establece en true y se especifica un valor para Width, el texto se escalará para ajustarse al ancho especificado. |
| [get_TextAlignment](./get_textalignment/)() const | Alineación del texto dentro del sello. |
| [get_TextState](./get_textstate/)() const | Obtiene las propiedades de texto del sello. Consulte **TextState** para obtener más detalles. |
| [get_TreatYIndentAsBaseLine](./get_treatyindentasbaseline/)() const | Define el origen de coordenadas para colocar el texto. Si TreatYIndentAsBaseLine = true (valor predeterminado cuando Draw = true) el valor de YIndent se tratará como la línea base del texto. Si TreatYIndentAsBaseLine = false (valor predeterminado cuando Draw = false) el valor de YIndent se tratará como la parte inferior (línea de descenso) del texto. |
| [get_Value](./get_value/)() | Obtiene el valor de cadena que se utiliza como sello en la página. |
| [get_Width](./get_width/)() override | Ancho deseado del sello en la página. |
| [get_WordWrap](./get_wordwrap/)() const | Define el ajuste de línea. Si esta propiedad se establece en true y se especifica un valor para Width, el texto se dividirá en varias líneas para ajustarse al ancho especificado. Valor predeterminado: false. |
| [get_WordWrapMode](./get_wordwrapmode/)() const | Obtiene el modo de ajuste de línea para la renderización del texto. |
| [Put](./put/)(System::SharedPtr\<Page\>) override | Agrega un sello textual en la página. |
| [set_AutoAdjustFontSizePrecision](./set_autoadjustfontsizeprecision/)(float) | Ajustar automáticamente la precisión del tamaño de fuente. Valor predeterminado: 0.1;. |
| [set_AutoAdjustFontSizeToFitStampRectangle](./set_autoadjustfontsizetofitstamprectangle/)(bool) | Si está habilitado, el tamaño de fuente se ajustará automáticamente para encajar en el rectángulo del sello de tamaño: [Width](../) y [Height](../). El ancho y alto predeterminados se derivan del rectángulo de la página. |
| [set_Draw](./set_draw/)(bool) | Esta propiedad determina cómo se dibuja el sello en la página. Si Draw = true, el sello se dibuja como operadores gráficos y si draw = false, el sello se dibuja como texto. |
| [set_Height](./set_height/)(double) override | Altura deseada del sello en la página. |
| [set_Justify](./set_justify/)(bool) | Define la justificación del texto. Si esta propiedad se establece en true, ambos bordes izquierdo y derecho del texto se alinean. Valor predeterminado: false. |
| [set_MaxRowWidth](./set_maxrowwidth/)(double) | Altura máxima de fila para la opción WordWrap. |
| [set_NoCharacterBehavior](./set_nocharacterbehavior/)(TextStamp::NoCharacterAction) | Establece el modo que define el comportamiento en caso de que las fuentes no contengan los caracteres solicitados. |
| [set_ReplacementFont](./set_replacementfont/)(const System::SharedPtr\<Text::Font\>\&) | Establece la fuente utilizada para la sustitución si la fuente del usuario no contiene el carácter requerido. |
| [set_Scale](./set_scale/)(bool) | Define el escalado del texto. Si esta propiedad se establece en true y se especifica un valor para Width, el texto se escalará para ajustarse al ancho especificado. |
| [set_TextAlignment](./set_textalignment/)(Aspose::Pdf::HorizontalAlignment) | Alineación del texto dentro del sello. |
| [set_TreatYIndentAsBaseLine](./set_treatyindentasbaseline/)(bool) | Define el origen de coordenadas para colocar el texto. Si TreatYIndentAsBaseLine = true (valor predeterminado cuando Draw = true) el valor de YIndent se tratará como la línea base del texto. Si TreatYIndentAsBaseLine = false (valor predeterminado cuando Draw = false) el valor de YIndent se tratará como la parte inferior (línea de descenso) del texto. |
| [set_Value](./set_value/)(const System::String\&) | Establece el valor de cadena que se utiliza como sello en la página. |
| [set_Width](./set_width/)(double) override | Ancho deseado del sello en la página. |
| [set_WordWrap](./set_wordwrap/)(bool) | Define el ajuste de línea. Si esta propiedad se establece en true y se especifica un valor para Width, el texto se dividirá en varias líneas para ajustarse al ancho especificado. Valor predeterminado: false. |
| [set_WordWrapMode](./set_wordwrapmode/)(Aspose::Pdf::Text::TextFormattingOptions::WordWrapMode) | Establece el modo de ajuste de línea para la renderización del texto. |
| [TextStamp](./textstamp/)(const System::String\&) | Inicializa una nueva instancia de la clase [TextStamp](./). |
| [TextStamp](./textstamp/)(const System::String\&, const System::SharedPtr\<Aspose::Pdf::Text::TextState\>\&) | Inicializa una nueva instancia de la clase [TextStamp](./). |
| [TextStamp](./textstamp/)(const System::SharedPtr\<Facades::FormattedText\>\&) | Inicializa una nueva instancia de la clase [TextStamp](./) con el objeto formattedText. |
## Ver también

* Class [Stamp](../stamp/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
