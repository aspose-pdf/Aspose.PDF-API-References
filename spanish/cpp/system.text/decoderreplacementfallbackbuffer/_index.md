---
title: "System::Text::DecoderReplacementFallbackBuffer clase"
linktitle: "DecoderReplacementFallbackBuffer"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Text::DecoderReplacementFallbackBuffer clase. Búfer para reemplazar la estrategia de reserva de decodificación en C++."
type: docs
weight: 800
url: /es/cpp/system.text/decoderreplacementfallbackbuffer/
---
## DecoderReplacementFallbackBuffer class


[Buffer](../../system/buffer/) for replacing decoding fallback strategy.

```cpp
class DecoderReplacementFallbackBuffer : public System::Text::DecoderFallbackBuffer
```

## Métodos

| Método | Descripción |
| --- | --- |
| [DecoderReplacementFallbackBuffer](./decoderreplacementfallbackbuffer/)(const DecoderReplacementFallbackPtr\&) | Constructor. |
| [Fallback](./fallback/)(ArrayPtr\<uint8_t\>, int) override | Maneja fallos de decodificación. |
| [get_Remaining](./get_remaining/)() const override | Obtiene el número de caracteres restantes en el búfer. |
| [GetNextChar](./getnextchar/)() override | Obtiene el siguiente carácter disponible. |
| [MovePrevious](./moveprevious/)() override | Se mueve al carácter anterior. |
| [Reset](./reset/)() override | Restablece el búfer al estado inicial (antes de la llamada a [Fallback()](./fallback/)). |
## Ver también

* Class [DecoderFallbackBuffer](../decoderfallbackbuffer/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
