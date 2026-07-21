---
title: "Método System::Text::EncoderFallbackBuffer::Fallback"
linktitle: "Fallback"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Text::EncoderFallbackBuffer::Fallback. Implementa el procedimiento de reserva real en C++."
type: docs
weight: 100
url: /es/cpp/system.text/encoderfallbackbuffer/fallback/
---
## EncoderFallbackBuffer::Fallback(char_t, int) method


Implementa el procedimiento de reserva real.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknown, int index)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| charUnknown | char_t | El codificador de caracteres no puede codificar. |
| index | int | [Index](../../../system/index/) del carácter que provocó el error. |

### ReturnValue

True si el búfer procesa caracteres desconocidos, false si los ignora.

## Ver también

* Class [EncoderFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## EncoderFallbackBuffer::Fallback(char_t, char_t, int) method


Implementa el procedimiento de reserva real.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| charUnknownHigh | char_t | Parte alta del par sustituto que provocó el error. |
| charUnknownLow | char_t | Parte baja del par sustituto que provocó el error. |
| index | int | [Index](../../../system/index/) del carácter que provocó el error. |

### ReturnValue

True si el búfer procesa caracteres desconocidos, false si los ignora.

## Ver también

* Class [EncoderFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
