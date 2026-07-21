---
title: "System::Char::IsHighSurrogate método"
linktitle: "IsHighSurrogate"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Char::IsHighSurrogate método. Determina si el carácter especificado es un high surrogate en C++."
type: docs
weight: 800
url: /es/cpp/system/char/ishighsurrogate/
---
## Char::IsHighSurrogate(char_t) method


Determina si el carácter especificado es un sustituto alto.

```cpp
static bool System::Char::IsHighSurrogate(char_t c)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| c | char_t | El carácter a probar |

### ReturnValue

True si el carácter especificado es un high surrogate, de lo contrario - false

## Ver también

* Class [Char](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Char::IsHighSurrogate(const char_t *, int) method


Determina si el carácter en el índice especificado del búfer de caracteres especificado es un sustituto alto.

```cpp
static bool System::Char::IsHighSurrogate(const char_t *str, int idx)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const char_t * | Puntero al comienzo del buffer de caracteres |
| idx | int | Un índice basado en cero en el buffer especificado del carácter a probar |

### ReturnValue

True si el carácter en el índice especificado es un high surrogate, de lo contrario - false

## Ver también

* Class [Char](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Char::IsHighSurrogate(const String\&, int) method


Determina si el carácter en el índice especificado de la cadena especificada es una unidad de código sustituto alto UTF-16.

```cpp
static bool System::Char::IsHighSurrogate(const String &s, int index)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | const String\& | Una cadena |
| índice | int | El índice en la cadena especificada del carácter a probar |

### ReturnValue

True si el carácter en el índice especificado es una unidad de código UTF-16 high surrogate, de lo contrario - false

## Ver también

* Class [String](../../string/)
* Class [Char](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
