---
title: "Clase System::Text::ICUEncoder"
linktitle: "ICUEncoder"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Text::ICUEncoder. Codificador que usa ICU para la codificación. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject() function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 2100
url: /es/cpp/system.text/icuencoder/
---
## ICUEncoder class


[Encoder](../encoder/) that uses ICU for encoding. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ICUEncoder : public System::Text::Encoder
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Convert](./convert/)(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) | Convierte caracteres a bytes. |
| virtual [Convert](./convert/)(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) | Convierte caracteres a bytes. |
| virtual [GetByteCount](./getbytecount/)(ArrayPtr\<char_t\>, int, int, bool) | Obtiene el número de bytes necesarios para codificar un búfer. |
| virtual [GetByteCount](./getbytecount/)(const char_t *, int, bool) | Obtiene el número de bytes necesarios para codificar un búfer. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) | Obtiene los bytes que resultan de codificar un búfer. |
| virtual [GetBytes](./getbytes/)(const char_t *, int, uint8_t *, int, bool) | Obtiene los bytes que resultan de codificar un búfer. |
| [ICUEncoder](./icuencoder/)(ICUEncoding *) | Constructor. |
| virtual [Reset](./reset/)() | Establece las variables internas al estado inicial. |
| [~ICUEncoder](./~icuencoder/)() | Destructor. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Base](./base/) | [Base](./base/) tipo. |
## Ver también

* Class [Encoder](../encoder/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
