---
title: "Clase Aspose::Pdf::Text::TextReplaceOptions"
linktitle: "TextReplaceOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Text::TextReplaceOptions. Representa opciones de reemplazo de texto en C++."
type: docs
weight: 4900
url: /es/cpp/aspose.pdf.text/textreplaceoptions/
---
## TextReplaceOptions class


Representa opciones de reemplazo de texto.

```cpp
class TextReplaceOptions : public Aspose::Pdf::Text::TextOptions
```

## Enums

| Enumeración | Descripción |
| --- | --- |
| [FontSizeAdjustment](./fontsizeadjustment/) | Especifica una política sobre cómo debe ajustarse el tamaño de fuente del texto para encajar dentro de un área contenedora. |
| [ReplaceAdjustment](./replaceadjustment/) | Determina la acción que se realizará después de reemplazar un fragmento de texto por uno más corto. Ninguna - sin acción, el texto reemplazado puede superponerse al resto de la línea; AdjustSpaceWidth - intenta ajustar los espacios entre palabras para mantener la longitud de la línea; WholeWordsHyphenation - intenta distribuir palabras entre líneas del párrafo para mantener el margen derecho del párrafo; ShiftRestOfLine - desplaza el resto de la línea según el cambio de longitud del texto, la longitud de la línea puede cambiar; El valor predeterminado es ShiftRestOfLine. |
| [Scope](./scope/) | [Scope](./scope/) donde se aplica la operación de reemplazo de texto REPLACE_FIRST por defecto Esta opción obsoleta se mantuvo por compatibilidad. Afecta a PdfContentEditor y no tiene efecto en [TextFragmentAbsorber](../textfragmentabsorber/). |
## Métodos

| Método | Descripción |
| --- | --- |
| [get_AdjustmentNewLineSpacing](./get_adjustmentnewlinespacing/)() const | Obtiene el valor del interlineado que se usa si el ajuste de reemplazo se fuerza a crear una nueva línea de texto. El valor esperado es un multiplicador del tamaño de fuente del texto reemplazado. El valor predeterminado es 1.2. |
| [get_FontSizeAdjustmentAction](./get_fontsizeadjustmentaction/)() const | Obtiene la política para ajustar el tamaño de fuente para que encaje dentro de los límites definidos por el [TextReplaceOptions::Rectangle](../). |
| [get_IgnoreParagraphs](./get_ignoreparagraphs/)() const | Obtiene un valor que indica si se deben ignorar los párrafos distintos al ajustar el texto en la página después del reemplazo de texto. |
| [get_LeftAdjustment](./get_leftadjustment/)() const | Establece u obtiene el ajuste de posición izquierda para el texto reemplazado al usar [TextReplaceOptions](./): |
| [get_Rectangle](./get_rectangle/)() const | Obtiene el rectángulo para ajustar el texto después del reemplazo. |
| [get_ReplaceAdjustmentAction](./get_replaceadjustmentaction/)() const | Obtiene una acción que se realizará después de reemplazar un fragmento de texto por uno más corto. |
| [get_ReplaceScope](./get_replacescope/)() const | Obtiene un alcance donde se aplica la operación de reemplazo de texto. |
| [get_RightAdjustment](./get_rightadjustment/)() const | Establece u obtiene el ajuste de posición derecha para el texto reemplazado al usar [TextReplaceOptions](./): |
| [set_AdjustmentNewLineSpacing](./set_adjustmentnewlinespacing/)(double) | Establece el valor del interlineado que se usa si el ajuste de reemplazo se fuerza a crear una nueva línea de texto. El valor esperado es un multiplicador del tamaño de fuente del texto reemplazado. El valor predeterminado es 1.2. |
| [set_FontSizeAdjustmentAction](./set_fontsizeadjustmentaction/)(TextReplaceOptions::FontSizeAdjustment) | Establece la política para ajustar el tamaño de fuente para que encaje dentro de los límites definidos por el [TextReplaceOptions::Rectangle](../). |
| [set_IgnoreParagraphs](./set_ignoreparagraphs/)(bool) | Establece un valor que indica si se deben ignorar los párrafos distintos al ajustar el texto en la página después del reemplazo de texto. |
| [set_LeftAdjustment](./set_leftadjustment/)(double) | Establece u obtiene el ajuste de posición izquierda para el texto reemplazado al usar [TextReplaceOptions](./): |
| [set_Rectangle](./set_rectangle/)(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Establece el rectángulo para ajustar el texto después del reemplazo. |
| [set_ReplaceAdjustmentAction](./set_replaceadjustmentaction/)(TextReplaceOptions::ReplaceAdjustment) | Establece una acción que se realizará después de reemplazar un fragmento de texto por uno más corto. |
| [set_ReplaceScope](./set_replacescope/)(TextReplaceOptions::Scope) | Establece un alcance donde se aplica la operación de reemplazo de texto. |
| [set_RightAdjustment](./set_rightadjustment/)(double) | Establece u obtiene el ajuste de posición derecha para el texto reemplazado al usar [TextReplaceOptions](./): |
| [TextReplaceOptions](./textreplaceoptions/)(TextReplaceOptions::Scope) | Inicializa una nueva instancia del objeto [TextReplaceOptions](./) para el alcance especificado. |
| [TextReplaceOptions](./textreplaceoptions/)(TextReplaceOptions::ReplaceAdjustment) | Inicializa una nueva instancia del objeto [TextReplaceOptions](./) para la acción después del reemplazo especificada. |
## Ver también

* Class [TextOptions](../textoptions/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
