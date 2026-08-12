---
title: "Clase System::Char"
linktitle: "Char"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Char. Proporciona métodos para la manipulación de caracteres representados como unidades de código UTF-16. Este es un tipo estático sin servicios de instancia. Nunca deberías crear instancias de él por ningún medio en C++."
type: docs
weight: 1300
url: /es/cpp/system/char/
---
## Char class


Proporciona métodos para la manipulación de caracteres representados como unidades de código UTF-16. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio.

```cpp
class Char
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [ConvertFromUtf32](./convertfromutf32/)(uint32_t) | Convierte una unidad de código UTF-32 en una instancia de la clase [System::String](../string/). |
| static [ConvertToUtf32](./converttoutf32/)(char_t, char_t) | Convierte el par sustituto UTF-16 especificado en una unidad de código UTF-32. |
| static [ConvertToUtf32](./converttoutf32/)(const String\&, int) | Convierte el valor de un carácter codificado en UTF-16 o un par sustituto en una posición especificada de una cadena en una unidad de código UTF-32. |
| static [GetNumericValue](./getnumericvalue/)(char_t) | Convierte el carácter UTF-16 especificado en un valor numérico de punto flotante de doble precisión. |
| static [GetUnicodeCategory](./getunicodecategory/)(char_t) | Devuelve un valor que representa la categoría Unicode del carácter especificado. |
| static [IsAsciiWhiteSpace](./isasciiwhitespace/)(char_t) | Determina si el carácter especificado está clasificado como un carácter de espacio en blanco ASCII. |
| static [IsControl](./iscontrol/)(const char_t *, int) | Determina si el carácter en el índice especificado del búfer de caracteres especificado está clasificado como un carácter de control Unicode. |
| static [IsControl](./iscontrol/)(char_t) | Determina si el carácter especificado está clasificado como un carácter de control Unicode. |
| static [IsDigit](./isdigit/)(const char_t *, int) | Determina si el carácter en el índice especificado del búfer de caracteres especificado está clasificado como un dígito decimal. |
| static [IsDigit](./isdigit/)(const String\&, const int32_t) | Determina si el carácter en el índice especificado de la cadena especificada está clasificado como un dígito decimal. |
| static [IsDigit](./isdigit/)(char_t) | Determina si el carácter especificado está clasificado como un dígito decimal. |
| static [IsHighSurrogate](./ishighsurrogate/)(const String\&, int) | Determina si el carácter en el índice especificado de la cadena especificada es una unidad de código sustituto alto UTF-16. |
| static [IsHighSurrogate](./ishighsurrogate/)(const char_t *, int) | Determina si el carácter en el índice especificado del búfer de caracteres especificado es un sustituto alto. |
| static [IsHighSurrogate](./ishighsurrogate/)(char_t) | Determina si el carácter especificado es un sustituto alto. |
| static [IsLetter](./isletter/)(const char_t *, int) | Determina si el carácter en el índice especificado del búfer de caracteres especificado está clasificado como una letra Unicode. |
| static [IsLetter](./isletter/)(char_t) | Determina si el carácter especificado está clasificado como una letra Unicode. |
| static [IsLetterOrDigit](./isletterordigit/)(const char_t *, int) | Determina si el carácter en el índice especificado del búfer de caracteres especificado está clasificado como una letra Unicode o un dígito decimal. |
| static [IsLetterOrDigit](./isletterordigit/)(char_t) | Determina si el carácter especificado está clasificado como letra Unicode o como dígito decimal. |
| static [IsLower](./islower/)(const char_t *, int) | Determina si el carácter en el índice especificado del búfer de caracteres especificado está clasificado como una letra minúscula. |
| static [IsLower](./islower/)(char_t) | Determina si el carácter especificado está clasificado como una letra minúscula. |
| static [IsLower](./islower/)(const String\&, int) | Determina si el carácter en el índice especificado de la cadena especificada está clasificado como una letra minúscula. |
| static [IsLowSurrogate](./islowsurrogate/)(const char_t *, int) | Determina si el carácter en el índice especificado del búfer de caracteres especificado es un surrogado bajo. |
| static [IsLowSurrogate](./islowsurrogate/)(char_t) | Determina si el carácter especificado es un surrogado bajo. |
| static [IsNumber](./isnumber/)(const char_t *, int) | Determina si el carácter en el índice especificado del búfer de caracteres especificado está clasificado como un número. |
| static [IsNumber](./isnumber/)(char_t) | Determina si el carácter especificado está clasificado como un número. |
| static [IsPunctuation](./ispunctuation/)(const char_t *, int) | Determina si el carácter en el índice especificado del búfer de caracteres especificado está clasificado como un carácter de puntuación. |
| static [IsPunctuation](./ispunctuation/)(char_t) | Determina si el carácter especificado está clasificado como un carácter de puntuación. |
| static [IsSeparator](./isseparator/)(const char_t *, int) | Determina si el carácter en el índice especificado del búfer de caracteres especificado está clasificado como un carácter separador. |
| static [IsSeparator](./isseparator/)(char_t) | Determina si el carácter especificado está clasificado como un carácter separador. |
| static [IsSurrogate](./issurrogate/)(char_t) | Determina si el carácter especificado es una unidad de código sustituto UTF-16. |
| static [IsSurrogate](./issurrogate/)(const String\&, int) | Determina si el carácter en el índice especificado de la cadena especificada es una unidad de código sustituto UTF-16. |
| static [IsSurrogatePair](./issurrogatepair/)(char_t, char_t) | Determina si los dos caracteres especificados forman un par sustituto UTF-16. |
| static [IsSurrogatePair](./issurrogatepair/)(const String\&, int) | Determina si dos caracteres consecutivos en el búfer de caracteres especificado forman un par sustituto. |
| static [IsSymbol](./issymbol/)(const char_t *, int) | Determina si el carácter en el índice especificado del búfer de caracteres especificado está clasificado como un carácter símbolo. |
| static [IsSymbol](./issymbol/)(char_t) | Determina si el carácter especificado está clasificado como un carácter símbolo. |
| static [IsUpper](./isupper/)(const String\&, int) | Determina si el carácter en el índice especificado de la cadena especificada está clasificado como una letra mayúscula. |
| static [IsUpper](./isupper/)(const char_t *, int) | Determina si el carácter en el índice especificado del búfer de caracteres especificado está clasificado como una letra mayúscula. |
| static [IsUpper](./isupper/)(char_t) | Determina si el carácter especificado está clasificado como una letra mayúscula. |
| static [IsWhiteSpace](./iswhitespace/)(const char_t *, int) | Determina si el carácter en el índice especificado del búfer de caracteres especificado está clasificado como un carácter de espacio en blanco. |
| static [IsWhiteSpace](./iswhitespace/)(char_t) | Determina si el carácter especificado está clasificado como un carácter de espacio en blanco. |
| static [IsWhiteSpace](./iswhitespace/)(const String\&, int) | Determina si el carácter en el índice especificado de la cadena especificada está clasificado como un carácter de espacio en blanco. |
| static [Parse](./parse/)(const String\&) | Convierte el primer y único carácter de la cadena especificada a un valor char_t. |
| static [ToLower](./tolower/)(char_t) | Convierte el carácter especificado a minúsculas. |
| static [ToLower](./tolower/)(char_t, const SharedPtr\<Globalization::CultureInfo\>\&) | Convierte el carácter especificado a minúsculas. |
| static [ToLowerInvariant](./tolowerinvariant/)(char_t) | Convierte el carácter especificado a minúsculas. |
| static [ToUpper](./toupper/)(char_t) | Convierte el carácter especificado a mayúsculas. |
| static [ToUpper](./toupper/)(char_t, const SharedPtr\<Globalization::CultureInfo\>\&) | Convierte el carácter especificado a mayúsculas. |
| static [ToUpperInvariant](./toupperinvariant/)(char_t) | Convierte el carácter especificado a mayúsculas. |
| static [TryParse](./tryparse/)(const System::String\&, char_t\&) | Intenta convertir una cadena que consiste en un solo carácter a un carácter UTF-16. La función tiene éxito solo cuando la cadena de entrada no es nula y tiene una longitud de exactamente un carácter. |
## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
