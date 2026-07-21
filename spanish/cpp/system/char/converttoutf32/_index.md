---
title: "Método System::Char::ConvertToUtf32"
linktitle: "ConvertToUtf32"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Char::ConvertToUtf32. Convierte el par sustituto UTF-16 especificado en una unidad de código UTF-32 en C++."
type: docs
weight: 200
url: /es/cpp/system/char/converttoutf32/
---
## Char::ConvertToUtf32(char_t, char_t) method


Convierte el par sustituto UTF-16 especificado en una unidad de código UTF-32.

```cpp
static int System::Char::ConvertToUtf32(char_t highSurrogate, char_t lowSurrogate)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| highSurrogate | char_t | El sustituto alto del par sustituto UTF-16 a convertir |
| lowSurrogate | char_t | El sustituto bajo del par sustituto UTF-16 a convertir |

### ReturnValue

Una unidad de código UTF-32 resultante de la conversión

## Ver también

* Class [Char](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Char::ConvertToUtf32(const String\&, int) method


Convierte el valor de un carácter codificado en UTF-16 o un par sustituto en una posición especificada de una cadena en una unidad de código UTF-32.

```cpp
static int System::Char::ConvertToUtf32(const String &s, int index)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | const String\& | Una cadena que contiene un carácter o un par sustituto |
| índice | int | La posición de índice del carácter o del par sustituto en la cadena especificada |

### ReturnValue

Una unidad de código UTF-32 resultante de la conversión

## Ver también

* Class [String](../../string/)
* Class [Char](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
