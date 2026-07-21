---
title: "Clase System::Text::UTF7Encoding"
linktitle: "UTF7Encoding"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Text::UTF7Encoding. Codificación UTF-7. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject() function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 2700
url: /es/cpp/system.text/utf7encoding/
---
## UTF7Encoding class


Codificación UTF-7. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/) function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class UTF7Encoding : public System::Text::Encoding
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Clone](./clone/)() override | Clona el objeto de codificación. |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Compara con el objeto. |
| [GetByteCount](./getbytecount/)(const char_t *, int) override | Obtiene el número de caracteres necesarios para codificar un búfer de caracteres. |
| virtual [GetByteCount](./getbytecount/)(ArrayPtr\<char_t\>, int, int) | Obtiene el número de caracteres necesarios para codificar un búfer de caracteres. |
| virtual [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | Obtiene el número de caracteres necesarios para codificar un búfer de caracteres. |
| [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Obtiene el número de caracteres necesarios para codificar un búfer de caracteres. |
| virtual [GetByteCount](./getbytecount/)(const String\&) | Obtiene el número de caracteres necesarios para codificar una cadena. |
| virtual [GetByteCount](./getbytecount/)(ArrayPtr\<char_t\>) | Obtiene el número de caracteres necesarios para codificar un búfer de caracteres. |
| [GetBytes](./getbytes/)(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) override | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| [GetBytes](./getbytes/)(const char_t *, int, uint8_t *, int) override | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| [GetBytes](./getbytes/)(const String\&, int, int, ArrayPtr\<uint8_t\>, int) override | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| virtual [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| virtual [GetBytes](./getbytes/)(const String\&) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<char_t\>, int, int) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| virtual [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<char_t\>) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| [GetCharCount](./getcharcount/)(ArrayPtr\<uint8_t\>, int, int) override | Obtiene el número de caracteres necesarios para decodificar un búfer de bytes. |
| [GetCharCount](./getcharcount/)(const uint8_t *, int) override | Obtiene el número de caracteres necesarios para decodificar un búfer de bytes. |
| virtual [GetCharCount](./getcharcount/)(ArrayPtr\<uint8_t\>) | Obtiene el número de caracteres necesarios para decodificar un búfer de bytes. |
| [GetChars](./getchars/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) override | Obtiene los caracteres resultantes de decodificar un búfer de bytes. |
| [GetChars](./getchars/)(const uint8_t *, int, char_t *, int) override | Obtiene los caracteres resultantes de decodificar un búfer de bytes. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>, int, int) | Obtiene los caracteres resultantes de decodificar un búfer de bytes. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>) | Obtiene los caracteres resultantes de decodificar un búfer de bytes. |
| [GetDecoder](./getdecoder/)() override | Obtenga un decodificador que reenvíe las solicitudes a este objeto. |
| [GetEncoder](./getencoder/)() override | Obtenga un codificador que reenvíe las solicitudes a este objeto. |
| [GetHashCode](./gethashcode/)() const override | Obtiene el código hash de la codificación. |
| [GetMaxByteCount](./getmaxbytecount/)(int) override | Obtenga la cantidad máxima de bytes necesarios para codificar un número especificado de caracteres. |
| [GetMaxCharCount](./getmaxcharcount/)(int) override | Obtenga la cantidad máxima de caracteres necesarios para decodificar un número especificado de bytes. |
| [GetString](./getstring/)(ArrayPtr\<uint8_t\>, int, int) override | Decodifica un búfer de bytes en una cadena. |
| virtual [GetString](./getstring/)(uint8_t *, int) | Decodifica un búfer de bytes en una cadena. |
| [GetString](./getstring/)(const ReadOnlySpan\<uint8_t\>\&) | Decodifica un búfer de bytes en una cadena. |
| virtual [GetString](./getstring/)(ArrayPtr\<uint8_t\>) | Decodifica un búfer de bytes en una cadena. |
| virtual [GetString](./getstring/)(const System::Details::ArrayView\<uint8_t\>\&) | Decodifica un búfer de bytes en una cadena. |
| [GetString](./getstring/)(System::Details::StackArray\<uint8_t, N\>\&) | Decodifica un búfer de bytes en una cadena. |
| virtual [GetString](./getstring/)(const System::Details::ArrayView\<uint8_t\>\&, int, int) | Decodifica un búfer de bytes en una cadena. |
| [GetString](./getstring/)(System::Details::StackArray\<uint8_t, N\>, int, int) | Decodifica un búfer de bytes en una cadena. |
| [operator==](./operator==/)(const UTF7Encoding\&) const | Compara los parámetros de codificaciones. |
| [UTF7Encoding](./utf7encoding/)() | Constructor. |
| [UTF7Encoding](./utf7encoding/)(bool) | Constructor. |
## Campos

| Campo | Descripción |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Valor predeterminado de la página de códigos. |
| static constexpr [UTF7_CODE_PAGE](./utf7_code_page/) | Número mágico usado por [Windows](../../system.windows/) para el identificador de página de códigos UTF-7. |
## Ver también

* Class [Encoding](../encoding/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
