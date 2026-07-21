---
title: "Clase System::Text::Encoder"
linktitle: "Encoder"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Text::Encoder. Encapsula la secuencia de caracteres de codificación en una secuencia de bytes. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 900
url: /es/cpp/system.text/encoder/
---
## Encoder class


Encapsula la secuencia de caracteres de codificación en una secuencia de bytes. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class Encoder : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Convert](./convert/)(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) | Convierte caracteres a bytes. |
| virtual [Convert](./convert/)(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) | Convierte caracteres a bytes. |
| [get_Fallback](./get_fallback/)() const | Obtiene la reserva de manejo de errores. |
| [get_FallbackBuffer](./get_fallbackbuffer/)() const | Obtiene el búfer de reserva. |
| virtual [GetByteCount](./getbytecount/)(ArrayPtr\<char_t\>, int, int, bool) | Obtiene el número de bytes necesarios para codificar un búfer. |
| virtual [GetByteCount](./getbytecount/)(const char_t *, int, bool) | Obtiene el número de bytes necesarios para codificar un búfer. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) | Obtiene los bytes que resultan de codificar un búfer. |
| virtual [GetBytes](./getbytes/)(const char_t *, int, uint8_t *, int, bool) | Obtiene los bytes que resultan de codificar un búfer. |
| virtual [Reset](./reset/)() | Limpia el estado interno del codificador. |
| [set_Fallback](./set_fallback/)(const EncoderFallbackPtr\&) | Establece la reserva de manejo de errores. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
