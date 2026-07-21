---
title: "Aspose::Pdf::Text::TextFragmentState class"
linktitle: "TextFragmentState"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Text::TextFragmentState class. Representa el estado de texto de un fragmento de texto en C++."
type: docs
weight: 4600
url: /es/cpp/aspose.pdf.text/textfragmentstate/
---
## TextFragmentState class


Representa el estado de texto de un fragmento de texto.

```cpp
class TextFragmentState : public Aspose::Pdf::Text::TextState
```

## Métodos

| Método | Descripción |
| --- | --- |
| [ApplyChangesFrom](./applychangesfrom/)(const System::SharedPtr\<TextState\>\&) override | Aplica la configuración de otro textState. |
| [get_BackgroundColor](./get_backgroundcolor/)() override | Establece el color de fondo del texto, representado por el objeto [TextFragment](../textfragment/). |
| [get_CharacterSpacing](./get_characterspacing/)() override | Obtiene el espaciado de caracteres del texto, representado por el objeto [TextFragment](../textfragment/). |
| [get_CoordinateOrigin](./get_coordinateorigin/)() override | Obtiene el [CoordinateOrigin](../coordinateorigin/) del texto. Si el [CoordinateOrigin](../coordinateorigin/) es Descender, la coordenada Y del texto corresponde al punto más bajo de la fuente. Si el [CoordinateOrigin](../coordinateorigin/) es BaseLine, la coordenada Y del texto corresponde a la línea base de la fuente. El valor predeterminado es Descender. Si el valor de Descent de la fuente es demasiado grande, el texto puede renderizarse más alto que otras fuentes. En este caso, se puede seleccionar el [CoordinateOrigin](../coordinateorigin/) BaseLine para una mejor renderización del texto. |
| [get_DrawTextRectangleBorder](./get_drawtextrectangleborder/)() const | Obtiene la bandera que indica si se dibuja el borde del rectángulo de texto. |
| [get_Font](./get_font/)() override | Obtiene la fuente del texto, representada por el objeto [TextFragment](../textfragment/). |
| [get_FontSize](./get_fontsize/)() override | Obtiene el tamaño de fuente del texto, representado por el objeto [TextFragment](../textfragment/). |
| [get_FontStyle](./get_fontstyle/)() override | Establece el estilo de fuente del texto, representado por el objeto [TextFragment](../textfragment/). |
| [get_ForegroundColor](./get_foregroundcolor/)() override | Obtiene el color de primer plano del texto, representado por el objeto [TextFragment](../textfragment/). |
| [get_FormattingOptions](./get_formattingoptions/)() const | Obtiene las opciones de formato. La configuración de las opciones será efectiva solo en escenarios de generador. |
| [get_HorizontalAlignment](./get_horizontalalignment/)() override | Obtiene la alineación horizontal del texto. |
| [get_HorizontalScaling](./get_horizontalscaling/)() override | Obtiene el escalado horizontal del texto, representado por el objeto [TextFragment](../textfragment/). |
| [get_Invisible](./get_invisible/)() override | Obtiene la invisibilidad del texto. |
| [get_LineSpacing](./get_linespacing/)() override | Obtiene el interlineado del texto. |
| [get_RenderingMode](./get_renderingmode/)() override | Obtiene el modo de renderizado del texto. |
| [get_Rotation](./get_rotation/)() | Obtiene el ángulo de rotación en grados. |
| [get_StrikeOut](./get_strikeout/)() override | Obtiene el tachado del texto, representado por el objeto [TextFragment](../textfragment/). |
| [get_StrokingColor](./get_strokingcolor/)() override | Obtiene las operaciones de trazo de color del renderizado de [TextFragment](../textfragment/) (texto con trazo, borde del rectángulo) |
| [get_Subscript](./get_subscript/)() override | Obtiene el subíndice del texto, representado por el objeto [TextFragment](../textfragment/). |
| [get_Superscript](./get_superscript/)() override | Obtiene el superíndice del texto, representado por el objeto [TextFragment](../textfragment/). |
| [get_TabStops](./get_tabstops/)() const | Obtiene los tabuladores del texto. |
| [get_Underline](./get_underline/)() override | Obtiene el subrayado del texto, representado por el objeto [TextFragment](../textfragment/). |
| [get_WordSpacing](./get_wordspacing/)() override | Obtiene el espaciado de palabras del texto. |
| [IsFitRectangle](./isfitrectangle/)(const System::String\&, const System::SharedPtr\<Rectangle\>\&) | Comprueba si la cadena de entrada puede colocarse dentro del rectángulo definido. |
| [MeasureHeight](./measureheight/)(char16_t) | Mide la altura de los caracteres. |
| [MeasureString](./measurestring/)(const System::String\&) override | Mide la cadena. |
| [set_BackgroundColor](./set_backgroundcolor/)(System::SharedPtr\<Color\>) override | Establece el color de fondo del texto, representado por el objeto [TextFragment](../textfragment/). |
| [set_CharacterSpacing](./set_characterspacing/)(float) override | Establece el espaciado de caracteres del texto, representado por el objeto [TextFragment](../textfragment/). |
| [set_CoordinateOrigin](./set_coordinateorigin/)(Aspose::Pdf::Text::CoordinateOrigin) override | Establece el [CoordinateOrigin](../coordinateorigin/) del texto. Si [CoordinateOrigin](../coordinateorigin/) es Descender, la coordenada Y del texto corresponde al punto más bajo de la fuente. Si [CoordinateOrigin](../coordinateorigin/) es BaseLine, la coordenada Y del texto corresponde a la línea base de la fuente. El valor predeterminado es Descender. Si el valor Descent de la fuente es demasiado grande, el texto puede renderizarse más alto que otras fuentes. En este caso, se puede seleccionar [CoordinateOrigin](../coordinateorigin/) BaseLine para un mejor renderizado del texto. |
| [set_DrawTextRectangleBorder](./set_drawtextrectangleborder/)(bool) | Establece la bandera de dibujo del borde del rectángulo de texto. |
| [set_Font](./set_font/)(System::SharedPtr\<Aspose::Pdf::Text::Font\>) override | Establece la fuente del texto, representada por el objeto [TextFragment](../textfragment/). |
| [set_FontSize](./set_fontsize/)(float) override | Establece el tamaño de fuente del texto, representado por el objeto [TextFragment](../textfragment/). |
| [set_FontStyle](./set_fontstyle/)(FontStyles) override | Establece el estilo de fuente del texto, representado por el objeto [TextFragment](../textfragment/). |
| [set_ForegroundColor](./set_foregroundcolor/)(System::SharedPtr\<Color\>) override | Establece el color de primer plano del texto, representado por el objeto [TextFragment](../textfragment/). |
| [set_FormattingOptions](./set_formattingoptions/)(const System::SharedPtr\<TextFormattingOptions\>\&) | Establece opciones de formato. La configuración de las opciones será efectiva solo en escenarios de generador. |
| [set_HorizontalAlignment](./set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) override | Establece la alineación horizontal del texto. |
| [set_HorizontalScaling](./set_horizontalscaling/)(float) override | Establece el escalado horizontal del texto, representado por el objeto [TextFragment](../textfragment/). |
| [set_Invisible](./set_invisible/)(bool) override | Establece la invisibilidad del texto. |
| [set_LineSpacing](./set_linespacing/)(float) override | Establece el interlineado del texto. |
| [set_RenderingMode](./set_renderingmode/)(TextRenderingMode) override | Establece el modo de renderizado del texto. |
| [set_Rotation](./set_rotation/)(double) | Establece el ángulo de rotación en grados. |
| [set_StrikeOut](./set_strikeout/)(bool) override | Establece el tachado del texto, representado por el objeto [TextFragment](../textfragment/). |
| [set_StrokingColor](./set_strokingcolor/)(System::SharedPtr\<Color\>) override | Establece las operaciones de trazo de color del renderizado de [TextFragment](../textfragment/) (texto con trazo, borde del rectángulo) |
| [set_Subscript](./set_subscript/)(bool) override | Establece el subíndice del texto, representado por el objeto [TextFragment](../textfragment/). |
| [set_Superscript](./set_superscript/)(bool) override | Establece el superíndice del texto, representado por el objeto [TextFragment](../textfragment/). |
| [set_Underline](./set_underline/)(bool) override | Establece el subrayado para el texto, representado por el objeto [TextFragment](../textfragment/). |
| [set_WordSpacing](./set_wordspacing/)(float) override | Establece el espaciado entre palabras del texto. |
| [TextFragmentState](./textfragmentstate/)(const System::SharedPtr\<TextFragment\>\&) | Inicializa una nueva instancia del objeto [TextFragmentState](./) con el objeto [TextFragment](../textfragment/) especificado. Esta inicialización de [TextFragmentState](./) no es compatible. [TextFragmentState](./) solo está disponible con la propiedad [TextFragment::TextState](../). |
## Observaciones


Proporciona una forma de cambiar las siguientes propiedades del texto: fuente ([TextFragmentState::Font](../) propiedad) tamaño de fuente ([TextFragmentState::FontSize](../) propiedad) estilo de fuente ([TextFragmentState::FontStyle](../) propiedad) color de primer plano ([TextFragmentState::ForegroundColor](../) propiedad) color de fondo ([TextFragmentState::BackgroundColor](../) propiedad)

[Note](../../aspose.pdf/note/) that changing [TextFragmentState](./) properties may change inner [TextFragment::Segments](../) collection because [TextFragment](../textfragment/) is an aggregate object and it may rearrange internal segments or merge them into single segment. If your requirement is to leave the [TextFragment::Segments](../) collection unchanged, please change inner segments individually. 


## Ver también

* Class [TextState](../textstate/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
