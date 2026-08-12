---
title: "Clase System::Text::Decoder"
linktitle: "Decoder"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Text::Decoder. Encapsula la decodificación de una secuencia de bytes en una secuencia de caracteres. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject() function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 200
url: /es/cpp/system.text/decoder/
---
## Decoder class


Encapsula la decodificación de una secuencia de bytes en una secuencia de caracteres. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/) function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class Decoder : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Convert](./convert/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) | Convierte bytes a caracteres. |
| virtual [Convert](./convert/)(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) | Convierte bytes a caracteres. |
| [get_Fallback](./get_fallback/)() const | Obtiene la reserva de manejo de errores. |
| [get_FallbackBuffer](./get_fallbackbuffer/)() const | Obtiene el búfer de reserva. |
| virtual [GetCharCount](./getcharcount/)(ArrayPtr\<uint8_t\>, int, int) | Obtiene el número de caracteres necesarios para decodificar un búfer. |
| virtual [GetCharCount](./getcharcount/)(ArrayPtr\<uint8_t\>, int, int, bool) | Obtiene el número de caracteres necesarios para decodificar un búfer. |
| virtual [GetCharCount](./getcharcount/)(const uint8_t *, int, bool) | Obtiene el número de caracteres necesarios para decodificar un búfer. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) | Obtiene los caracteres que resultan de decodificar un búfer. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) | Obtiene los caracteres que resultan de decodificar un búfer. |
| virtual [GetChars](./getchars/)(const uint8_t *, int, char_t *, int, bool) | Obtiene los caracteres que resultan de decodificar un búfer. |
| virtual [Reset](./reset/)() | Limpia el estado interno del decodificador. |
| [set_Fallback](./set_fallback/)(const DecoderFallbackPtr\&) | Establece la reserva de manejo de errores. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
