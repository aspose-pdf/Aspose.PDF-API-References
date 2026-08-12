---
title: "Método System::Text::DecoderFallbackBuffer::Fallback"
linktitle: "Fallback"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Text::DecoderFallbackBuffer::Fallback. Implementa el procedimiento real de reserva en C++."
type: docs
weight: 100
url: /es/cpp/system.text/decoderfallbackbuffer/fallback/
---
## DecoderFallbackBuffer::Fallback method


Implementa el procedimiento de reserva real.

```cpp
virtual bool System::Text::DecoderFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytesUnknown | ArrayPtr\<uint8_t\> | [Array](../../../system/array/) de bytes incluyendo el que el decodificador no puede decodificar. |
| index | int | [Index](../../../system/index/) del byte que provocó el error. |

### ReturnValue

Verdadero si el búfer procesa bytes desconocidos, falso si los ignora.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [DecoderFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
