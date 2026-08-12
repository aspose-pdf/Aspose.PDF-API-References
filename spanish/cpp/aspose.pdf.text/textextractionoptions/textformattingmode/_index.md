---
title: "Aspose::Pdf::Text::TextExtractionOptions::TextFormattingMode enum"
linktitle: "TextFormattingMode"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Text::TextExtractionOptions::TextFormattingMode enum. Define diferentes modos que pueden usarse al convertir un documento pdf a texto. Ver la clase TextDevice en C++."
type: docs
weight: 600
url: /es/cpp/aspose.pdf.text/textextractionoptions/textformattingmode/
---
## TextFormattingMode enum


Define diferentes modos que pueden usarse al convertir un documento pdf a texto. Consulte la clase [TextDevice](../).

```cpp
enum class TextFormattingMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Pure | 0 | Representa el contenido del pdf con un poco de rutinas de formato. |
| Raw | 1 | Representa el contenido del pdf tal cual, es decir, sin formato. |
| Aplanar | 2 | Representa el contenido del pdf con fragmentos de texto posicionados por sus coordenadas. Es básicamente similar al modo "Raw". Pero mientras que "Raw" se centra en preservar la estructura de los fragmentos de texto (operadores) en un documento, "Flatten" se centra en mantener el texto en el orden en que se lee. |
| MemorySaving | 3 | Extracción con ahorro de memoria. Es casi igual al modo 'Raw' pero funciona ligeramente más rápido y usa menos memoria. |

## Ver también

* Class [TextExtractionOptions](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
