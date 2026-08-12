---
title: "Clase Aspose::Pdf::Text::TextState"
linktitle: "TextState"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Text::TextState. Representa el estado de un texto en C++."
type: docs
weight: 5300
url: /es/cpp/aspose.pdf.text/textstate/
---
## TextState class


Representa el estado de texto de un texto.

```cpp
class TextState : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [ApplyChangesFrom](./applychangesfrom/)(const System::SharedPtr\<TextState\>\&) | Aplica la configuración de otro textState. |
| virtual [get_BackgroundColor](./get_backgroundcolor/)() | Establece el color de fondo del texto. |
| virtual [get_CharacterSpacing](./get_characterspacing/)() | Obtiene el espaciado de caracteres del texto. |
| virtual [get_CoordinateOrigin](./get_coordinateorigin/)() | Obtiene el [CoordinateOrigin](../coordinateorigin/) del texto. Si el [CoordinateOrigin](../coordinateorigin/) es Descender, la coordenada Y del texto corresponde al punto más bajo de la fuente. Si el [CoordinateOrigin](../coordinateorigin/) es BaseLine, la coordenada Y del texto corresponde a la línea base de la fuente. El valor predeterminado es Descender. Si el valor de Descent de la fuente es demasiado grande, el texto puede renderizarse más alto que otras fuentes. En este caso, se puede seleccionar el [CoordinateOrigin](../coordinateorigin/) BaseLine para una mejor renderización del texto. |
| virtual [get_Font](./get_font/)() | Obtiene la fuente del texto. |
| virtual [get_FontSize](./get_fontsize/)() | Obtiene el tamaño de fuente del texto. |
| virtual [get_FontStyle](./get_fontstyle/)() | Establece el estilo de fuente del texto. |
| virtual [get_ForegroundColor](./get_foregroundcolor/)() | Obtiene el color de primer plano del texto. |
| virtual [get_HorizontalAlignment](./get_horizontalalignment/)() | Obtiene la alineación horizontal del texto. |
| virtual [get_HorizontalScaling](./get_horizontalscaling/)() | Obtiene la escala horizontal del texto. |
| virtual [get_Invisible](./get_invisible/)() | Obtiene la invisibilidad del texto. Esto básicamente refleja el estado de [RenderingMode](../), excepto en algunos casos especiales (como el recorte). |
| virtual [get_LineSpacing](./get_linespacing/)() | Obtiene el interlineado del texto. |
| virtual [get_RenderingMode](./get_renderingmode/)() | Obtiene el modo de renderizado del texto. |
| virtual [get_StrikeOut](./get_strikeout/)() | Obtiene el tachado del texto, representado por el objeto [TextSegment](../textsegment/). |
| virtual [get_StrokingColor](./get_strokingcolor/)() | Obtiene el color de primer plano del texto. |
| virtual [get_Subscript](./get_subscript/)() | Obtiene el subíndice del texto. |
| virtual [get_Superscript](./get_superscript/)() | Obtiene el superíndice del texto. |
| [get_TabTag](./get_tabtag/)() | Puedes colocar esta etiqueta en el texto para declarar tabulación. |
| virtual [get_Underline](./get_underline/)() | Obtiene el subrayado del texto, representado por el objeto [TextFragment](../textfragment/). |
| virtual [get_WordSpacing](./get_wordspacing/)() | Obtiene el espaciado de palabras del texto. |
| [MeasureHeight](./measureheight/)(char16_t) | Mide la altura de los caracteres. |
| virtual [MeasureString](./measurestring/)(const System::String\&) | Mide la cadena. |
| virtual [set_BackgroundColor](./set_backgroundcolor/)(System::SharedPtr\<Color\>) | Establece el color de fondo del texto. |
| virtual [set_CharacterSpacing](./set_characterspacing/)(float) | Establece el espaciado de caracteres del texto. |
| virtual [set_CoordinateOrigin](./set_coordinateorigin/)(Aspose::Pdf::Text::CoordinateOrigin) | Establece el [CoordinateOrigin](../coordinateorigin/) del texto. Si [CoordinateOrigin](../coordinateorigin/) es Descender, la coordenada Y del texto corresponde al punto más bajo de la fuente. Si [CoordinateOrigin](../coordinateorigin/) es BaseLine, la coordenada Y del texto corresponde a la línea base de la fuente. El valor predeterminado es Descender. Si el valor Descent de la fuente es demasiado grande, el texto puede renderizarse más alto que otras fuentes. En este caso, se puede seleccionar [CoordinateOrigin](../coordinateorigin/) BaseLine para un mejor renderizado del texto. |
| virtual [set_Font](./set_font/)(System::SharedPtr\<Aspose::Pdf::Text::Font\>) | Establece la fuente del texto. |
| virtual [set_FontSize](./set_fontsize/)(float) | Establece el tamaño de fuente del texto. |
| virtual [set_FontStyle](./set_fontstyle/)(FontStyles) | Establece el estilo de fuente del texto. |
| virtual [set_ForegroundColor](./set_foregroundcolor/)(System::SharedPtr\<Color\>) | Establece el color de primer plano del texto. |
| virtual [set_HorizontalAlignment](./set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) | Establece la alineación horizontal del texto. |
| virtual [set_HorizontalScaling](./set_horizontalscaling/)(float) | Establece la escala horizontal del texto. |
| virtual [set_Invisible](./set_invisible/)(bool) | Establece la invisibilidad del texto. Esto básicamente refleja el estado de [RenderingMode](../), excepto en algunos casos especiales (como el recorte). |
| virtual [set_LineSpacing](./set_linespacing/)(float) | Establece el interlineado del texto. |
| virtual [set_RenderingMode](./set_renderingmode/)(TextRenderingMode) | Establece el modo de renderizado del texto. |
| virtual [set_StrikeOut](./set_strikeout/)(bool) | Establece el tachado para el texto, representado por el objeto [TextSegment](../textsegment/). |
| virtual [set_StrokingColor](./set_strokingcolor/)(System::SharedPtr\<Color\>) | Establece el color de primer plano del texto. |
| virtual [set_Subscript](./set_subscript/)(bool) | Establece el subíndice del texto. |
| virtual [set_Superscript](./set_superscript/)(bool) | Establece el superíndice del texto. |
| virtual [set_Underline](./set_underline/)(bool) | Establece el subrayado para el texto, representado por el objeto [TextFragment](../textfragment/). |
| virtual [set_WordSpacing](./set_wordspacing/)(float) | Establece el espaciado entre palabras del texto. |
| [TextState](./textstate/)() | Crea un objeto de estado de texto. |
| [TextState](./textstate/)(double) | Crea un objeto de estado de texto con especificación de tamaño de fuente. |
| [TextState](./textstate/)(System::Drawing::Color) | Crea un objeto de estado de texto con especificación de color de primer plano. |
| [TextState](./textstate/)(System::Drawing::Color, double) | Crea un objeto de estado de texto con especificación de color de primer plano y tamaño de fuente. |
| [TextState](./textstate/)(const System::String\&) | Crea un objeto de estado de texto con especificación de familia de fuente. |
| [TextState](./textstate/)(const System::String\&, bool, bool) | Crea un objeto de estado de texto con especificación de familia de fuente y estilo de fuente. |
| [TextState](./textstate/)(const System::String\&, double) | Crea un objeto de estado de texto con especificación de familia de fuente y tamaño de fuente. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
