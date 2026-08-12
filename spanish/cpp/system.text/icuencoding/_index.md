---
title: "Clase System::Text::ICUEncoding"
linktitle: "ICUEncoding"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Text::ICUEncoding. Implementación de codificación basada en ICU. SOLO USO INTERNO. Los objetos de esta clase solo deben ser asignados usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 2200
url: /es/cpp/system.text/icuencoding/
---
## ICUEncoding class


Implementación de codificación basada en ICU. SOLO USO INTERNO. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class ICUEncoding : public System::Text::Encoding
```

## Métodos

| Método | Descripción |
| --- | --- |
| [GetByteCount](./getbytecount/)(const char_t *, int) override | Obtiene el número de caracteres necesarios para codificar un búfer de caracteres. |
| virtual [GetByteCount](./getbytecount/)(ArrayPtr\<char_t\>, int, int) | RTTI. |
| virtual [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | RTTI. |
| [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | RTTI. |
| virtual [GetByteCount](./getbytecount/)(const String\&) | RTTI. |
| virtual [GetByteCount](./getbytecount/)(ArrayPtr\<char_t\>) | RTTI. |
| [GetBytes](./getbytes/)(const char_t *, int, uint8_t *, int) override | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| virtual [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| virtual [GetBytes](./getbytes/)(const String\&, int, int, ArrayPtr\<uint8_t\>, int) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| virtual [GetBytes](./getbytes/)(const String\&) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<char_t\>, int, int) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| virtual [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<char_t\>) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| [GetCharCount](./getcharcount/)(const uint8_t *, int) override | Obtiene el número de caracteres necesarios para decodificar un búfer de bytes. |
| virtual [GetCharCount](./getcharcount/)(ArrayPtr\<uint8_t\>, int, int) | Obtiene el número de caracteres necesarios para decodificar un búfer de bytes. |
| virtual [GetCharCount](./getcharcount/)(ArrayPtr\<uint8_t\>) | Obtiene el número de caracteres necesarios para decodificar un búfer de bytes. |
| [GetChars](./getchars/)(const uint8_t *, int, char_t *, int) override | Obtiene los caracteres resultantes de decodificar un búfer de bytes. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) | Obtiene los caracteres resultantes de decodificar un búfer de bytes. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>, int, int) | Obtiene los caracteres resultantes de decodificar un búfer de bytes. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>) | Obtiene los caracteres resultantes de decodificar un búfer de bytes. |
| [GetDecoder](./getdecoder/)() override | Obtenga un decodificador que reenvíe las solicitudes a este objeto. |
| [GetEncoder](./getencoder/)() override | Obtenga un codificador que reenvíe las solicitudes a este objeto. |
| [GetMaxByteCount](./getmaxbytecount/)(int) override | Obtenga la cantidad máxima de bytes necesarios para codificar un número especificado de caracteres. |
| [GetMaxCharCount](./getmaxcharcount/)(int) override | Obtenga la cantidad máxima de caracteres necesarios para decodificar un número especificado de bytes. |
| [GetPreamble](./getpreamble/)() override | Devuelve una secuencia de bytes que indica la codificación (p. ej. BOM). |
| [ICUEncoding](./icuencoding/)(const Details::EncodingInfoInternal *) | Constructor. |
| [operator==](./operator==/)(const ICUEncoding\&) const | Compara codificaciones usando páginas de códigos. |
## Campos

| Campo | Descripción |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Valor predeterminado de la página de códigos. |
## Ver también

* Class [Encoding](../encoding/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
