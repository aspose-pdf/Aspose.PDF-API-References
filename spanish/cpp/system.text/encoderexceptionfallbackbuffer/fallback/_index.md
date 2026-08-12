---
title: "System::Text::EncoderExceptionFallbackBuffer::Fallback método"
linktitle: "Fallback"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Text::EncoderExceptionFallbackBuffer::Fallback método. Maneja fallos de codificación en C++."
type: docs
weight: 200
url: /es/cpp/system.text/encoderexceptionfallbackbuffer/fallback/
---
## EncoderExceptionFallbackBuffer::Fallback(char_t, int) method


Maneja fallos de codificación.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknown, int index) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| charUnknown | char_t | Caracteres desconocidos; ignorados. |
| índice | int | Desplazamiento de caracteres desconocidos; ignorado. |

### ReturnValue

Nunca devuelve realmente, lanza una excepción en su lugar.

## Ver también

* Class [EncoderExceptionFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## EncoderExceptionFallbackBuffer::Fallback(char_t, char_t, int) method


Maneja fallos de codificación.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| charUnknownHigh | char_t | Parte alta del par sustituto que provocó el error. |
| charUnknownLow | char_t | Parte baja del par sustituto que provocó el error. |
| índice | int | Desplazamiento de carácter desconocido; ignorado. |

### ReturnValue

Nunca devuelve realmente, lanza una excepción en su lugar.

## Ver también

* Class [EncoderExceptionFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
