---
title: "System::Text::RegularExpressions::Regex::Replace método"
linktitle: "Reemplazar"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Text::RegularExpressions::Regex::Replace método. Reemplaza todas las coincidencias de la expresión regular en la cadena con la cadena de reemplazo en C++."
type: docs
weight: 800
url: /es/cpp/system.text.regularexpressions/regex/replace/
---
## Regex::Replace(const String\&, const char_t *) method


Reemplaza todas las coincidencias de la expresión regular en la cadena con la cadena de reemplazo.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *replacement)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const String\& | Cadena de entrada. |
| reemplazo | const char_t * | Cadena de reemplazo. |

### ReturnValue

Cadena de entrada con todas las coincidencias de la expresión regular reemplazadas por la cadena de reemplazo.

## Ver también

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const MatchEvaluator\&) method


Reemplaza todas las coincidencias en la cadena con cadenas de reemplazo generadas por el delegado.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const String\& | Cadena de entrada. |
| evaluador | const MatchEvaluator\& | Delegado para generar cadenas de reemplazo basadas en coincidencias. |

### ReturnValue

Cadenas de entrada con todas las coincidencias reemplazadas.

## Ver también

* Class [String](../../../system/string/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const MatchEvaluator\&, int) method


Reemplaza todas las coincidencias en la cadena con cadenas de reemplazo generadas por el delegado.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const String\& | Cadena de entrada. |
| evaluador | const MatchEvaluator\& | Delegado para generar cadenas de reemplazo basadas en coincidencias. |
| count | int | Límite del número de reemplazos. |

### ReturnValue

Cadenas de entrada con todas las coincidencias reemplazadas.

## Ver también

* Class [String](../../../system/string/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const MatchEvaluator\&, int, int) method


Reemplaza todas las coincidencias en la cadena con cadenas de reemplazo generadas por el delegado.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count, int startat)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const String\& | Cadena de entrada. |
| evaluador | const MatchEvaluator\& | Delegado para generar cadenas de reemplazo basadas en coincidencias. |
| count | int | Límite del número de reemplazos. |
| startat | int | [Index](../../../system/index/) en la cadena de entrada donde comenzar el reemplazo. |

### ReturnValue

Cadenas de entrada con todas las coincidencias reemplazadas.

## Ver también

* Class [String](../../../system/string/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const String\&) method


Reemplaza todas las coincidencias de la expresión regular en la cadena con la cadena de reemplazo.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const String\& | Cadena de entrada. |
| reemplazo | const String\& | Cadena de reemplazo. |

### ReturnValue

Cadena de entrada con todas las coincidencias de la expresión regular reemplazadas por la cadena de reemplazo.

## Ver también

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const String\&, int) method


Reemplaza subcadenas en la cadena. No implementado.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count)
```

## Ver también

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const String\&, int, int) method


Reemplaza subcadenas en la cadena. No implementado.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count, int startat)
```

## Ver también

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const char_t *, const char_t *) method


Reemplaza todas las coincidencias de la expresión regular en la cadena con la cadena de reemplazo.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *pattern, const char_t *replacement)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const String\& | Cadena de entrada. |
| pattern | const char_t * | [Regex](../) patrón. |
| reemplazo | const char_t * | Cadena de reemplazo. |

### ReturnValue

Cadena de entrada con todas las coincidencias de la expresión regular reemplazadas por la cadena de reemplazo.

## Ver también

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const String\&, const char_t *) method


Reemplaza todas las coincidencias de la expresión regular en la cadena con la cadena de reemplazo.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const char_t *replacement)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const String\& | Cadena de entrada. |
| pattern | const String\& | [Regex](../) patrón. |
| reemplazo | const char_t * | Cadena de reemplazo. |

### ReturnValue

Cadena de entrada con todas las coincidencias de la expresión regular reemplazadas por la cadena de reemplazo.

## Ver también

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&) method


Reemplaza coincidencias de la expresión regular.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const String\& | Cadena de entrada. |
| patrón | const String\& | Patrón de expresión regular. |
| evaluador | const MatchEvaluator\& | Delegado para generar la cadena de reemplazo para cada coincidencia. |

### ReturnValue

[String](../../../system/string/) with all matches replaced.

## Ver también

* Class [String](../../../system/string/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&, RegexOptions) method


Reemplaza todas las coincidencias en la cadena con cadenas de reemplazo generadas por el delegado (función estática).

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator, RegexOptions options)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const String\& | Cadena de entrada. |
| pattern | const String\& | [Regex](../) patrón. |
| evaluador | const MatchEvaluator\& | Delegado para generar cadenas de reemplazo basadas en coincidencias. |
| options | RegexOptions | [Regex](../) opciones. |

### ReturnValue

Cadenas de entrada con todas las coincidencias reemplazadas.

## Ver también

* Class [String](../../../system/string/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Enum [RegexOptions](../../regexoptions/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const String\&, const String\&) method


Reemplaza coincidencias de la expresión regular.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const String\& | Cadena de entrada. |
| patrón | const String\& | Patrón de expresión regular. |
| reemplazo | const String\& | Cadena de reemplazo. |

### ReturnValue

[String](../../../system/string/) with all matches replaced.

## Ver también

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Replace(const String\&, const String\&, const String\&, RegexOptions) method


Reemplaza todas las coincidencias de la expresión regular en la cadena con la cadena de reemplazo.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement, RegexOptions options)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const String\& | Cadena de entrada. |
| pattern | const String\& | [Regex](../) patrón. |
| reemplazo | const String\& | Cadena de reemplazo. |
| options | RegexOptions | [Regex](../) opciones. |

### ReturnValue

Cadena de entrada con todas las coincidencias de la expresión regular reemplazadas por la cadena de reemplazo.

## Ver también

* Class [String](../../../system/string/)
* Enum [RegexOptions](../../regexoptions/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
