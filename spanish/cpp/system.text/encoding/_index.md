---
title: "System::Text::Encoding class"
linktitle: "Codificación"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Text::Encoding class. Servicios de codificación en C++."
type: docs
weight: 1600
url: /es/cpp/system.text/encoding/
---
## Encoding class


[Encoding](./) services.

```cpp
class Encoding : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Clone](./clone/)() | Clona el objeto de codificación. |
| static [Convert](./convert/)(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&) | Convierte bytes entre dos codificaciones. |
| static [Convert](./convert/)(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&, int, int) | Convierte bytes entre dos codificaciones. |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Compara codificaciones. |
| static [get_ASCII](./get_ascii/)() | Obtiene la codificación ASCII. |
| static [get_BigEndianUnicode](./get_bigendianunicode/)() | Obtiene el objeto de codificación Unicode big-endian estándar. |
| static [get_BigEndianUTF32](./get_bigendianutf32/)() | Obtiene el objeto de codificación UTF-32 big-endian estándar. |
| virtual [get_BodyName](./get_bodyname/)() | Obtiene el nombre de codificación compatible con el cuerpo del agente de correo. |
| virtual [get_CodePage](./get_codepage/)() | Obtiene el ID de página de códigos [Windows](../../system.windows/). |
| [get_DecoderFallback](./get_decoderfallback/)() const | Obtiene la reserva del decodificador. |
| static [get_Default](./get_default/)() | Obtiene la codificación predeterminada. |
| [get_EncoderFallback](./get_encoderfallback/)() const | Obtiene la reserva del codificador. |
| virtual [get_EncodingName](./get_encodingname/)() | Obtiene el nombre legible de la codificación. |
| virtual [get_HeaderName](./get_headername/)() | Obtiene el nombre de codificación compatible con el encabezado del agente de correo. |
| virtual [get_IsBrowserDisplay](./get_isbrowserdisplay/)() | Comprueba si la codificación puede usarse en el navegador para mostrar contenido. |
| virtual [get_IsBrowserSave](./get_isbrowsersave/)() | Comprueba si la codificación puede usarse en el navegador para guardar contenido. |
| virtual [get_IsMailNewsDisplay](./get_ismailnewsdisplay/)() | Comprueba si la codificación puede usarse en el cliente de correo para mostrar contenido. |
| virtual [get_IsMailNewsSave](./get_ismailnewssave/)() | Comprueba si la codificación puede usarse en el cliente de correo para guardar el contenido. |
| [get_IsReadOnly](./get_isreadonly/)() | Comprueba si la codificación es de solo lectura. |
| virtual [get_IsSingleByte](./get_issinglebyte/)() | Comprueba si la codificación es de un solo byte. |
| static [get_Latin1](./get_latin1/)() | Obtiene la codificación Latin1. SOLO USO INTERNO. |
| static [get_Unicode](./get_unicode/)() | Obtiene el objeto de codificación Unicode estándar. |
| static [get_UTF32](./get_utf32/)() |  |
| static [get_UTF7](./get_utf7/)() | Obtiene el objeto de codificación UTF-7 estándar. |
| static [get_UTF8](./get_utf8/)() | Obtiene el objeto de codificación UTF-8 estándar. |
| static [get_UTF8Unmarked](./get_utf8unmarked/)() | Solo interno, para ser usado por las bibliotecas de clases: sin marcar y sin validación de entrada. |
| virtual [get_WebName](./get_webname/)() | Obtiene el nombre de codificación compatible con IANA. |
| virtual [get_WindowsCodePage](./get_windowscodepage/)() | Obtiene el ID de página de códigos [Windows](../../system.windows/). |
| virtual [GetByteCount](./getbytecount/)(ArrayPtr\<char_t\>, int, int) | Obtiene el número de caracteres necesarios para codificar un búfer de caracteres. |
| virtual [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | Obtiene el número de caracteres necesarios para codificar un búfer de caracteres. |
| [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Obtiene el número de caracteres necesarios para codificar un búfer de caracteres. |
| virtual [GetByteCount](./getbytecount/)(const String\&) | Obtiene el número de caracteres necesarios para codificar una cadena. |
| virtual [GetByteCount](./getbytecount/)(ArrayPtr\<char_t\>) | Obtiene el número de caracteres necesarios para codificar un búfer de caracteres. |
| virtual [GetByteCount](./getbytecount/)(const char_t *, int) | Obtiene el número de caracteres necesarios para codificar un búfer de caracteres. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| virtual [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| virtual [GetBytes](./getbytes/)(const String\&, int, int, ArrayPtr\<uint8_t\>, int) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| virtual [GetBytes](./getbytes/)(const String\&) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<char_t\>, int, int) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| virtual [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<char_t\>) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| virtual [GetBytes](./getbytes/)(const char_t *, int, uint8_t *, int) | Obtiene los bytes resultantes de codificar un búfer de caracteres. |
| virtual [GetCharCount](./getcharcount/)(ArrayPtr\<uint8_t\>, int, int) | Obtiene el número de caracteres necesarios para decodificar un búfer de bytes. |
| virtual [GetCharCount](./getcharcount/)(ArrayPtr\<uint8_t\>) | Obtiene el número de caracteres necesarios para decodificar un búfer de bytes. |
| virtual [GetCharCount](./getcharcount/)(const uint8_t *, int) | Obtiene el número de caracteres necesarios para decodificar un búfer de bytes. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) | Obtiene los caracteres resultantes de decodificar un búfer de bytes. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>, int, int) | Obtiene los caracteres resultantes de decodificar un búfer de bytes. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>) | Obtiene los caracteres resultantes de decodificar un búfer de bytes. |
| virtual [GetChars](./getchars/)(const uint8_t *, int, char_t *, int) | Obtiene los caracteres resultantes de decodificar un búfer de bytes. |
| virtual [GetDecoder](./getdecoder/)() | Obtenga un decodificador que reenvíe las solicitudes a este objeto. |
| virtual [GetEncoder](./getencoder/)() | Obtenga un codificador que reenvíe las solicitudes a este objeto. |
| static [GetEncoding](./getencoding/)(const String\&) | Obtiene la codificación por nombre. |
| static [GetEncoding](./getencoding/)(int) | Obtiene la codificación por página de códigos. |
| static [GetEncoding](./getencoding/)(int, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) | Obtiene la codificación por página de códigos. |
| static [GetEncoding](./getencoding/)(const String\&, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) | Obtiene la codificación por nombre. |
| static [GetEncodings](./getencodings/)() | Obtiene la lista de codificaciones conocidas. |
| [GetHashCode](./gethashcode/)() const override | Genera un hash de la codificación. |
| virtual [GetMaxByteCount](./getmaxbytecount/)(int) | Obtenga la cantidad máxima de bytes necesarios para codificar un número especificado de caracteres. |
| virtual [GetMaxCharCount](./getmaxcharcount/)(int) | Obtenga la cantidad máxima de caracteres necesarios para decodificar un número especificado de bytes. |
| virtual [GetPreamble](./getpreamble/)() | Devuelve una secuencia de bytes que indica la codificación (p. ej. BOM). |
| virtual [GetString](./getstring/)(uint8_t *, int) | Decodifica un búfer de bytes en una cadena. |
| [GetString](./getstring/)(const ReadOnlySpan\<uint8_t\>\&) | Decodifica un búfer de bytes en una cadena. |
| virtual [GetString](./getstring/)(ArrayPtr\<uint8_t\>) | Decodifica un búfer de bytes en una cadena. |
| virtual [GetString](./getstring/)(const System::Details::ArrayView\<uint8_t\>\&) | Decodifica un búfer de bytes en una cadena. |
| [GetString](./getstring/)(System::Details::StackArray\<uint8_t, N\>\&) | Decodifica un búfer de bytes en una cadena. |
| virtual [GetString](./getstring/)(ArrayPtr\<uint8_t\>, int, int) | Decodifica un búfer de bytes en una cadena. |
| virtual [GetString](./getstring/)(const System::Details::ArrayView\<uint8_t\>\&, int, int) | Decodifica un búfer de bytes en una cadena. |
| [GetString](./getstring/)(System::Details::StackArray\<uint8_t, N\>, int, int) | Decodifica un búfer de bytes en una cadena. |
| [set_DecoderFallback](./set_decoderfallback/)(const DecoderFallbackPtr\&) | Establece la alternativa del decodificador. |
| [set_EncoderFallback](./set_encoderfallback/)(const EncoderFallbackPtr\&) | Establece la alternativa del codificador. |
## Campos

| Campo | Descripción |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](./default_code_page/) | Valor predeterminado de la página de códigos. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | RTTI. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
