---
title: "Clase System::Text::EncoderExceptionFallbackBuffer"
linktitle: "EncoderExceptionFallbackBuffer"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Text::EncoderExceptionFallbackBuffer. Búfer para la estrategia de reserva de codificación que lanza excepciones. No almacena nada realmente, pero lanza una excepción en su lugar. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1100
url: /es/cpp/system.text/encoderexceptionfallbackbuffer/
---
## EncoderExceptionFallbackBuffer class


[Buffer](../../system/buffer/) for exception-throwing encoding fallback strategy. Doesn't store anything actually, but throws instead. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class EncoderExceptionFallbackBuffer : public System::Text::EncoderFallbackBuffer
```

## Métodos

| Método | Descripción |
| --- | --- |
| [EncoderExceptionFallbackBuffer](./encoderexceptionfallbackbuffer/)() | Constructor. |
| [Fallback](./fallback/)(char_t, int) override | Maneja fallos de codificación. |
| [Fallback](./fallback/)(char_t, char_t, int) override | Maneja fallos de codificación. |
| [get_Remaining](./get_remaining/)() const override | Obtiene el número de caracteres restantes. |
| [GetNextChar](./getnextchar/)() override | Obtiene el siguiente carácter disponible. |
| [MovePrevious](./moveprevious/)() override | Se mueve al carácter anterior. |
## Ver también

* Class [EncoderFallbackBuffer](../encoderfallbackbuffer/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
