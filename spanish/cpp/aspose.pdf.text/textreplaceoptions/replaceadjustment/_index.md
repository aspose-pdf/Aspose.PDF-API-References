---
title: "Aspose::Pdf::Text::TextReplaceOptions::ReplaceAdjustment enumeración"
linktitle: "ReplaceAdjustment"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Text::TextReplaceOptions::ReplaceAdjustment enumeración. Determina la acción que se realizará después de reemplazar un fragmento de texto por uno más corto. None - sin acción, el texto reemplazado puede superponerse al resto de la línea; AdjustSpaceWidth - intenta ajustar los espacios entre palabras para mantener la longitud de la línea; WholeWordsHyphenation - intenta distribuir palabras entre las líneas del párrafo para mantener el margen derecho del párrafo; ShiftRestOfLine - desplaza el resto de la línea según la longitud cambiada del texto, la longitud de la línea puede modificarse; El valor predeterminado es ShiftRestOfLine en C++."
type: docs
weight: 1900
url: /es/cpp/aspose.pdf.text/textreplaceoptions/replaceadjustment/
---
## ReplaceAdjustment enum


Determina la acción que se realizará después de reemplazar un fragmento de texto por uno más corto. Ninguna - sin acción, el texto reemplazado puede superponerse al resto de la línea; AdjustSpaceWidth - intenta ajustar los espacios entre palabras para mantener la longitud de la línea; WholeWordsHyphenation - intenta distribuir palabras entre líneas del párrafo para mantener el margen derecho del párrafo; ShiftRestOfLine - desplaza el resto de la línea según el cambio de longitud del texto, la longitud de la línea puede cambiar; El valor predeterminado es ShiftRestOfLine.

```cpp
enum class ReplaceAdjustment
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Ninguno | 0 | Sin acción, el texto reemplazado puede superponerse al resto de la línea. |
| AdjustSpaceWidth | 1 | Intenta ajustar los espacios entre palabras para mantener la longitud de la línea. |
| WholeWordsHyphenation | 2 | Intenta distribuir palabras entre las líneas del párrafo para mantener el margen derecho del párrafo. |
| IsFormFillingMode | 4 | Intenta distribuir las palabras en el espacio blanco disponible usando el ancho del párrafo. Si el texto se desborda, se ocultará. |
| ShiftRestOfLine | 8 | (Predeterminado) Desplaza el resto de la línea según la longitud cambiante del texto, la longitud de la línea puede cambiar. |

## Ver también

* Class [TextReplaceOptions](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
