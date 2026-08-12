---
title: "Método System::Text::DecoderReplacementFallbackBuffer::Fallback"
linktitle: "Fallback"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Text::DecoderReplacementFallbackBuffer::Fallback. Maneja la falla de decodificación en C++."
type: docs
weight: 200
url: /es/cpp/system.text/decoderreplacementfallbackbuffer/fallback/
---
## DecoderReplacementFallbackBuffer::Fallback method


Maneja fallos de decodificación.

```cpp
virtual bool System::Text::DecoderReplacementFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytesUnknown | ArrayPtr\<uint8_t\> | [Array](../../../system/array/) de bytes desconocidos; ignorado. |
| índice | int | Desplazamiento de bytes desconocidos; ignorado. |

### ReturnValue

True si se proporciona una cadena de reemplazo y no está vacía, false en caso contrario.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [DecoderReplacementFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
