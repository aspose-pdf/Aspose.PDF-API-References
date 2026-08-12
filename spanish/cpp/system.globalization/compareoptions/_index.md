---
title: "System::Globalization::CompareOptions enum"
linktitle: "CompareOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Globalization::CompareOptions enum. Opciones de comparación de cadenas en C++."
type: docs
weight: 3300
url: /es/cpp/system.globalization/compareoptions/
---
## CompareOptions enum


[String](../../system/string/) comparison options.

```cpp
enum class CompareOptions : int32_t
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Ninguno | 0 | Sin opciones especiales. |
| IgnoreCase | 1 | Ignorar mayúsculas y minúsculas. |
| IgnoreNonSpace | 2 | Ignorar caracteres combinantes sin espaciado, p. ej. diacríticos. |
| IgnoreSymbols | 4 | Incluir espacios en blanco, signos de puntuación, etc. |
| IgnoreKanaType | 8 | Ignorar tipo kana (japonés). |
| IgnoreWidth | 16 | Ignorar ancho de caracteres al comparar cadenas. |
| OrdinalIgnoreCase | 268435456 | Comparación ordinal con diferencia de mayúsculas/minúsculas ignorada. |
| StringSort | 536870912 | Utilizar algoritmo de ordenación de cadenas para comparar caracteres. |
| Ordinal | 1073741824 | Comparar códigos UTF directamente para la primera comparación. |

## Ver también

* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
