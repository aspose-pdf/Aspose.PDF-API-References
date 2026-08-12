---
title: "System::Text::EncoderReplacementFallbackBuffer clase"
linktitle: "EncoderReplacementFallbackBuffer"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Text::EncoderReplacementFallbackBuffer. Búfer para reemplazar la estrategia de reserva de codificación. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject() function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1500
url: /es/cpp/system.text/encoderreplacementfallbackbuffer/
---
## EncoderReplacementFallbackBuffer class


[Buffer](../../system/buffer/) for replacing encoding fallback strategy. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class EncoderReplacementFallbackBuffer : public System::Text::EncoderFallbackBuffer
```

## Métodos

| Método | Descripción |
| --- | --- |
| [EncoderReplacementFallbackBuffer](./encoderreplacementfallbackbuffer/)(const EncoderReplacementFallbackPtr\&) | Constructor. |
| [Fallback](./fallback/)(char_t, int) override | Maneja fallos de codificación. |
| [Fallback](./fallback/)(char_t, char_t, int) override | Maneja fallos de codificación. |
| [get_Remaining](./get_remaining/)() const override | Obtiene el número de caracteres restantes en el búfer. |
| [GetNextChar](./getnextchar/)() override | Obtiene el siguiente carácter disponible. |
| [MovePrevious](./moveprevious/)() override | Se mueve al carácter anterior. |
| [Reset](./reset/)() override | Restablece el búfer al estado inicial (antes de la llamada a [Fallback()](./fallback/)). |
## Ver también

* Class [EncoderFallbackBuffer](../encoderfallbackbuffer/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
