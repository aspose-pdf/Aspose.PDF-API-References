---
title: "Clase Aspose::Pdf::Text::TextFormattingOptions"
linktitle: "TextFormattingOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Text::TextFormattingOptions. Representa opciones de formato de texto en C++."
type: docs
weight: 4200
url: /es/cpp/aspose.pdf.text/textformattingoptions/
---
## TextFormattingOptions class


Representa opciones de formato de texto.

```cpp
class TextFormattingOptions : public Aspose::Pdf::Text::TextOptions
```

## Enums

| Enumeración | Descripción |
| --- | --- |
| [LineSpacingMode](./linespacingmode/) | Define los detalles del interlineado. |
| [WordWrapMode](./wordwrapmode/) | Define estrategias de ajuste de palabras. |
## Métodos

| Método | Descripción |
| --- | --- |
| [get_FirstLineIndent](./get_firstlineindent/)() const | Obtiene el valor de sangría de la primera línea. |
| [get_HyphenSymbol](./get_hyphensymbol/)() const | Obtiene el símbolo de guión que se utiliza en el proceso de separación silábica. |
| [get_LineSpacing](./get_linespacing/)() const | Obtiene el modo de interlineado. El valor predeterminado es [LineSpacingMode.FontSize](./linespacingmode/). |
| [get_SubsequentLinesIndent](./get_subsequentlinesindent/)() const | Obtiene el valor de sangría de las líneas subsiguientes. |
| [get_WrapMode](./get_wrapmode/)() const | Obtiene el modo de ajuste de texto. El valor predeterminado es [WordWrapMode.NoWrap](./wordwrapmode/). |
| [set_FirstLineIndent](./set_firstlineindent/)(float) | Establece el valor de sangría de la primera línea. |
| [set_HyphenSymbol](./set_hyphensymbol/)(const System::String\&) | Establece el símbolo de guión que se usa en el proceso de separación silábica. |
| [set_LineSpacing](./set_linespacing/)(TextFormattingOptions::LineSpacingMode) | Establece el modo de interlineado. El valor predeterminado es [LineSpacingMode.FontSize](./linespacingmode/). |
| [set_SubsequentLinesIndent](./set_subsequentlinesindent/)(float) | Establece el valor de sangría de las líneas subsiguientes. |
| [set_WrapMode](./set_wrapmode/)(TextFormattingOptions::WordWrapMode) | Establece el modo de ajuste de texto. El valor predeterminado es [WordWrapMode.NoWrap](./wordwrapmode/). |
| [TextFormattingOptions](./textformattingoptions/)(TextFormattingOptions::WordWrapMode) | Inicializa una nueva instancia del objeto [TextFormattingOptions](./) para el modo de ajuste de texto especificado. |
| [TextFormattingOptions](./textformattingoptions/)() | Inicializa una nueva instancia del objeto [TextFormattingOptions](./) con un modo de ajuste de texto indefinido. |
## Ver también

* Class [TextOptions](../textoptions/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
