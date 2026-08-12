---
title: "System::Text::RegularExpressions::Regex::Match método"
linktitle: "Match"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Text::RegularExpressions::Regex::Match método. Coincide la expresión regular con la cadena en C++."
type: docs
weight: 600
url: /es/cpp/system.text.regularexpressions/regex/match/
---
## Regex::Match(const String\&) method


Coincide la expresión regular contra una cadena.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const String\& | Cadena objetivo. |

### ReturnValue

[Match](../../match/) value containing match status and submatches.

## Ver también

* Typedef [MatchPtr](../../matchptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Match(const String\&, int, int) method


Coincide la expresión regular contra una cadena.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, int startat, int length=0)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const String\& | Cadena objetivo. |
| startat | int | Índice inicial. |
| longitud | int | Número de caracteres a examinar (0 para examinar toda la cadena). |

### ReturnValue

[Match](../../match/) value containing match status and submatches.

## Ver también

* Typedef [MatchPtr](../../matchptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Match(const String\&, const String\&, RegexOptions, TimeSpan, int, int) method


Coincide cadena y patrón.

```cpp
static MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
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

Primera coincidencia encontrada.

## Ver también

* Typedef [MatchPtr](../../matchptr/)
* Class [String](../../../system/string/)
* Enum [RegexOptions](../../regexoptions/)
* Class [TimeSpan](../../../system/timespan/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
