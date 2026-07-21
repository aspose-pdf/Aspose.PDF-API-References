---
title: "System::Text::DecoderFallbackBuffer clase"
linktitle: "DecoderFallbackBuffer"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Text::DecoderFallbackBuffer. Proporciona un búfer para la implementación de reserva. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 600
url: /es/cpp/system.text/decoderfallbackbuffer/
---
## DecoderFallbackBuffer class


Proporciona un búfer para la implementación de reserva. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y utilice dicho puntero para pasarlo a funciones como argumento.

```cpp
class DecoderFallbackBuffer : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Fallback](./fallback/)(ArrayPtr\<uint8_t\>, int) | Implementa el procedimiento de reserva real. |
| virtual [get_Remaining](./get_remaining/)() const | Obtiene el recuento restante de caracteres a procesar. |
| virtual [GetNextChar](./getnextchar/)() | Extrae el siguiente carácter del búfer de reserva. |
| virtual [MovePrevious](./moveprevious/)() | Mueve la posición del búfer un paso atrás si es posible. |
| virtual [Reset](./reset/)() | Restablece el búfer al estado inicial. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
