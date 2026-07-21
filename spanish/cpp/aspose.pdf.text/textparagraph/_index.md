---
title: "Aspose::Pdf::Text::TextParagraph clase"
linktitle: "TextParagraph"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Text::TextParagraph clase. Representa párrafos de texto como un objeto de texto multilínea en C++."
type: docs
weight: 4800
url: /es/cpp/aspose.pdf.text/textparagraph/
---
## TextParagraph class


Representa párrafos de texto como un objeto de texto multilínea.

```cpp
class TextParagraph : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AppendLine](./appendline/)(const System::String\&) | Añade una línea de texto. |
| [AppendLine](./appendline/)(const System::String\&, float) | Añade una línea de texto. |
| [AppendLine](./appendline/)(const System::String\&, const System::SharedPtr\<TextState\>\&) | Añade una línea de texto con parámetros de estado de texto. |
| [AppendLine](./appendline/)(const System::String\&, const System::SharedPtr\<TextState\>\&, float) | Añade una línea de texto con parámetros de estado de texto. |
| [AppendLine](./appendline/)(const System::SharedPtr\<TextFragment\>\&) | Añade una línea de texto con parámetros de estado de texto. |
| [AppendLine](./appendline/)(const System::SharedPtr\<TextFragment\>\&, const System::SharedPtr\<TextState\>\&) | Añade una línea de texto con parámetros de estado de texto. |
| [AppendLine](./appendline/)(const System::SharedPtr\<TextFragment\>\&, const System::SharedPtr\<TextState\>\&, float) | Añade una línea de texto con parámetros de estado de texto. |
| [BeginEdit](./beginedit/)() | Inicia la edición del [TextParagraph](./). |
| [EndEdit](./endedit/)() | Finaliza la edición del [TextParagraph](./). |
| [get_FirstLineIndent](./get_firstlineindent/)() const | Obtiene el valor de sangría de líneas subsiguientes. Si se establece en un valor distinto de cero, tiene una ventaja sobre el valor FormattingOptions.SubsequentLinesIndent. |
| [get_FormattingOptions](./get_formattingoptions/)() const | Obtiene opciones de formato. |
| [get_HorizontalAlignment](./get_horizontalalignment/)() const | Obtiene la alineación horizontal del texto dentro del [Rectangle](../../aspose.pdf/rectangle/) del párrafo. |
| [get_Justify](./get_justify/)() | Obtiene el valor que indica si el texto está justificado. |
| [get_Margin](./get_margin/)() const | Obtiene el relleno. |
| [get_Position](./get_position/)() const | Obtiene la posición del párrafo. |
| [get_Rectangle](./get_rectangle/)() const | Obtiene el rectángulo del párrafo. |
| [get_Rotation](./get_rotation/)() const | Obtiene el ángulo de rotación en grados. |
| [get_SubsequentLinesIndent](./get_subsequentlinesindent/)() const | Obtiene el valor de sangría de líneas subsiguientes. Si se establece en un valor distinto de cero, tiene una ventaja sobre el valor FormattingOptions.SubsequentLinesIndent. |
| [get_TextRectangle](./get_textrectangle/)() | Obtiene el rectángulo del texto colocado en el párrafo. |
| [get_VerticalAlignment](./get_verticalalignment/)() const | Obtiene la alineación vertical del texto dentro del [Rectangle](../../aspose.pdf/rectangle/) del párrafo. |
| [set_FirstLineIndent](./set_firstlineindent/)(float) | Establece el valor de sangría de líneas subsiguientes. Si se establece en un valor distinto de cero, tiene una ventaja sobre el valor FormattingOptions.SubsequentLinesIndent. |
| [set_FormattingOptions](./set_formattingoptions/)(const System::SharedPtr\<TextFormattingOptions\>\&) | Establece opciones de formato. |
| [set_HorizontalAlignment](./set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) | Establece la alineación horizontal del texto dentro del [Rectangle](../../aspose.pdf/rectangle/) del párrafo. |
| [set_Justify](./set_justify/)(bool) | Establece el valor de si el texto está justificado. |
| [set_Margin](./set_margin/)(const System::SharedPtr\<MarginInfo\>\&) | Establece el relleno. |
| [set_Position](./set_position/)(const System::SharedPtr\<Aspose::Pdf::Text::Position\>\&) | Establece la posición del párrafo. |
| [set_Rectangle](./set_rectangle/)(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Establece el rectángulo del párrafo. |
| [set_Rotation](./set_rotation/)(double) | Establece el ángulo de rotación en grados. |
| [set_SubsequentLinesIndent](./set_subsequentlinesindent/)(float) | Establece el valor de sangría de líneas subsiguientes. Si se establece en un valor distinto de cero, tiene una ventaja sobre el valor FormattingOptions.SubsequentLinesIndent. |
| [set_VerticalAlignment](./set_verticalalignment/)(Aspose::Pdf::VerticalAlignment) | Establece la alineación vertical del texto dentro del [Rectangle](../../aspose.pdf/rectangle/) del párrafo. |
| [TextParagraph](./textparagraph/)() | Crea el objeto [TextParagraph](./). |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
