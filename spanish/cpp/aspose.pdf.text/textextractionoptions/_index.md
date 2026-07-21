---
title: "Aspose::Pdf::Text::TextExtractionOptions class"
linktitle: "TextExtractionOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Text::TextExtractionOptions class. Representa opciones de extracción de texto en C++."
type: docs
weight: 4100
url: /es/cpp/aspose.pdf.text/textextractionoptions/
---
## TextExtractionOptions class


Representa opciones de extracción de texto.

```cpp
class TextExtractionOptions : public Aspose::Pdf::Text::TextOptions
```

## Enums

| Enumeración | Descripción |
| --- | --- |
| [TextFormattingMode](./textformattingmode/) | Define diferentes modos que pueden usarse al convertir un documento pdf a texto. Consulte la clase [TextDevice](../). |
## Métodos

| Método | Descripción |
| --- | --- |
| [get_FormattingMode](./get_formattingmode/)() const | Obtiene el modo de formato. |
| [get_ScaleFactor](./get_scalefactor/)() const | Obtiene el factor que se aplicará para escalar el tamaño de la fuente durante la extracción en modo puro. Un valor menor genera más espacios en el texto extraído. El valor predeterminado es 1 - sin escalado; establecer el valor a cero permite que el algoritmo elija el escalado automáticamente. |
| [set_FormattingMode](./set_formattingmode/)(TextExtractionOptions::TextFormattingMode) | Obtiene el modo de formato. |
| [set_ScaleFactor](./set_scalefactor/)(double) | Establece el factor que se aplicará para escalar el tamaño de la fuente durante la extracción en modo puro. Un valor menor genera más espacios en el texto extraído. El valor predeterminado es 1 - sin escalado; establecer el valor a cero permite que el algoritmo elija el escalado automáticamente. |
| [TextExtractionOptions](./textextractionoptions/)(TextExtractionOptions::TextFormattingMode) | Inicializa una nueva instancia del objeto [TextExtractionOptions](./) para el modo de formato de texto especificado. |
## Ver también

* Class [TextOptions](../textoptions/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
