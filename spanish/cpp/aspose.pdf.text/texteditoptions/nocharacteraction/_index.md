---
title: "Aspose::Pdf::Text::TextEditOptions::NoCharacterAction enum"
linktitle: "NoCharacterAction"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Text::TextEditOptions::NoCharacterAction enum. Acción a realizar si la fuente no contiene el carácter requerido en C++."
type: docs
weight: 1900
url: /es/cpp/aspose.pdf.text/texteditoptions/nocharacteraction/
---
## NoCharacterAction enum


Acción a realizar si la fuente no contiene el carácter requerido.

```cpp
enum class NoCharacterAction
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| ThrowException | 0 | Lanzar excepción. |
| UseStandardFont | 1 | Reemplazar la fuente por una fuente estándar que contenga el carácter requerido. |
| ReplaceAnyway | 2 | Reemplazar el texto de todos modos sin sustitución de fuente. |
| ReplaceFonts | 3 | Reemplaza fuentes según sea necesario para garantizar que todos los caracteres del texto se puedan mostrar. El algoritmo de sustitución de fuentes sigue estos pasos: |
| UseCustomReplacementFont | 4 | Reemplazar la fuente por la fuente de reemplazo definida. |

## Ver también

* Class [TextEditOptions](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
