---
title: "System::Text::ICUDecoder clase"
linktitle: "ICUDecoder"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Text::ICUDecoder. Decodificador que usa ICU para decodificar. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 2000
url: /es/cpp/system.text/icudecoder/
---
## ICUDecoder class


[Decoder](../decoder/) that uses ICU for decoding. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ICUDecoder : public System::Text::Decoder
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Convert](./convert/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) | Convierte bytes a caracteres. |
| virtual [Convert](./convert/)(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) | Convierte bytes a caracteres. |
| virtual [GetCharCount](./getcharcount/)(ArrayPtr\<uint8_t\>, int, int) | Obtiene el número de caracteres necesarios para decodificar un búfer. |
| virtual [GetCharCount](./getcharcount/)(ArrayPtr\<uint8_t\>, int, int, bool) | Obtiene el número de caracteres necesarios para decodificar un búfer. |
| virtual [GetCharCount](./getcharcount/)(const uint8_t *, int, bool) | Obtiene el número de caracteres necesarios para decodificar un búfer. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) | Obtiene los caracteres que resultan de decodificar un búfer. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) | Obtiene los caracteres que resultan de decodificar un búfer. |
| virtual [GetChars](./getchars/)(const uint8_t *, int, char_t *, int, bool) | Obtiene los caracteres que resultan de decodificar un búfer. |
| [ICUDecoder](./icudecoder/)(ICUEncoding *) | Constructor. |
| virtual [Reset](./reset/)() | Establece las variables internas al estado inicial. |
| virtual [~ICUDecoder](./~icudecoder/)() | Destructor. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Base](./base/) | [Base](./base/) tipo. |
## Ver también

* Class [Decoder](../decoder/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
