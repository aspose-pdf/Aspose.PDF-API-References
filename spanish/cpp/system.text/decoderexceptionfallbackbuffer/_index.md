---
title: "Clase System::Text::DecoderExceptionFallbackBuffer"
linktitle: "DecoderExceptionFallbackBuffer"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Text::DecoderExceptionFallbackBuffer. Búfer para la estrategia de reserva de decodificación que lanza excepciones. No almacena nada realmente, pero lanza una excepción en su lugar. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 400
url: /es/cpp/system.text/decoderexceptionfallbackbuffer/
---
## DecoderExceptionFallbackBuffer class


[Buffer](../../system/buffer/) for exception-throwing decoding fallback strategy. Doesn't store anything actually, but throws instead. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DecoderExceptionFallbackBuffer : public System::Text::DecoderFallbackBuffer
```

## Métodos

| Método | Descripción |
| --- | --- |
| [DecoderExceptionFallbackBuffer](./decoderexceptionfallbackbuffer/)() | Constructor. |
| [Fallback](./fallback/)(ArrayPtr\<uint8_t\>, int) override | Maneja fallos de decodificación. |
| [get_Remaining](./get_remaining/)() const override | Obtiene el número de caracteres restantes. |
| [GetNextChar](./getnextchar/)() override | Obtiene el siguiente carácter disponible. |
| [MovePrevious](./moveprevious/)() override | Se mueve al carácter anterior. |
## Ver también

* Class [DecoderFallbackBuffer](../decoderfallbackbuffer/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
