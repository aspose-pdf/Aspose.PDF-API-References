---
title: "Método System::Text::RegularExpressions::Regex::Matches"
linktitle: "Coincidencias"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Text::RegularExpressions::Regex::Matches. Obtiene todas las coincidencias de la expresión regular en la cadena dada mediante coincidencias repetidas en C++."
type: docs
weight: 700
url: /es/cpp/system.text.regularexpressions/regex/matches/
---
## Regex::Matches(const String\&, int) method


Obtiene todas las coincidencias de la expresión regular en una cadena dada mediante coincidencias repetidas.

```cpp
MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, int startat=0)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const String\& | Cadena de entrada. |
| startat | int | [Index](../../../system/index/) para comenzar la coincidencia en. |

### ReturnValue

Colección de todas las coincidencias encontradas.

## Ver también

* Typedef [MatchCollectionPtr](../../matchcollectionptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Matches(const String\&, const String\&, RegexOptions, TimeSpan, int, int) method


Obtiene todas las coincidencias entre la cadena y el patrón.

```cpp
static MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const String\& | Cadena de entrada. |
| patrón | const String\& | Patrón de expresión regular. |
| opciones | RegexOptions | Opciones de coincidencia. |
| matchTimeout | TimeSpan | Tiempo de espera. |
| startat | int | [Match](../../match/) posición inicial. |
| longitud | int | Número de caracteres a examinar (0 deshabilita el límite). |

### ReturnValue

Todas las coincidencias encontradas mediante coincidencias repetidas.

## Ver también

* Typedef [MatchCollectionPtr](../../matchcollectionptr/)
* Class [String](../../../system/string/)
* Enum [RegexOptions](../../regexoptions/)
* Class [TimeSpan](../../../system/timespan/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
