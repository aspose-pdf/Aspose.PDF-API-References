---
title: "Clase System::Xml::XmlConvert"
linktitle: "XmlConvert"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::XmlConvert. Codifica y decodifica nombres XML, y proporciona métodos para convertir entre tipos en tiempo de ejecución y tipos del lenguaje de definición de esquemas XML (XSD). Al convertir tipos de datos, los valores devueltos son independientes de la configuración regional en C++."
type: docs
weight: 1200
url: /es/cpp/system.xml/xmlconvert/
---
## XmlConvert class


Codifica y decodifica nombres XML, y proporciona métodos para convertir entre tipos en tiempo de ejecución y tipos del lenguaje de definición de [Esquema](../../system.xml.schema/) XML (XSD). Al convertir tipos de datos, los valores devueltos son independientes de la configuración regional.

```cpp
class XmlConvert : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [DecodeName](./decodename/)(const String\&) | Decodifica un nombre. Este método realiza la operación inversa de los métodos XmlConvert::EncodeName(String) y XmlConvert::EncodeLocalName(String). |
| static [EncodeLocalName](./encodelocalname/)(const String\&) | Convierte el nombre a un nombre local XML válido. |
| static [EncodeName](./encodename/)(const String\&) | Convierte el nombre a un nombre XML válido. |
| static [EncodeNmToken](./encodenmtoken/)(const String\&) | Verifica que el nombre sea válido según la especificación XML. |
| static [IsNCNameChar](./isncnamechar/)(char16_t) | Comprueba si el carácter proporcionado es un tipo de carácter válido sin dos puntos. |
| static [IsPublicIdChar](./ispublicidchar/)(char16_t) | Devuelve la instancia del carácter proporcionado si el carácter en el argumento es un carácter de identificación pública válido, de lo contrario **nullptr**. |
| static [IsStartNCNameChar](./isstartncnamechar/)(char16_t) | Comprueba si el carácter proporcionado es un tipo de carácter de inicio de nombre válido. |
| static [IsWhitespaceChar](./iswhitespacechar/)(char16_t) | Comprueba si el carácter proporcionado es un carácter de espacio en blanco XML válido. |
| static [IsXmlChar](./isxmlchar/)(char16_t) | Comprueba si el carácter proporcionado es un carácter XML válido. |
| static [IsXmlSurrogatePair](./isxmlsurrogatepair/)(char16_t, char16_t) | Comprueba si el par sustituto de caracteres proporcionado es un carácter XML válido. |
| static [ToBoolean](./toboolean/)(String) | Convierte el [String](../../system/string/) a su equivalente [Boolean](../../system/boolean/). |
| static [ToByte](./tobyte/)(const String\&) | Convierte el [String](../../system/string/) a su equivalente [Byte](../../system/byte/). |
| static [ToChar](./tochar/)(const String\&) | Convierte el [String](../../system/string/) a su equivalente [Char](../../system/char/). |
| static [ToDateTime](./todatetime/)(const String\&) | Convierte el [String](../../system/string/) a su equivalente [DateTime](../../system/datetime/). |
| static [ToDateTime](./todatetime/)(const String\&, const String\&) | Convierte el [String](../../system/string/) a su equivalente [DateTime](../../system/datetime/). |
| static [ToDateTime](./todatetime/)(const String\&, const ArrayPtr\<String\>\&) | Convierte el [String](../../system/string/) a su equivalente [DateTime](../../system/datetime/). |
| static [ToDateTime](./todatetime/)(const String\&, XmlDateTimeSerializationMode) | Convierte el [String](../../system/string/) a un [DateTime](../../system/datetime/) usando el [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/) especificado. |
| static [ToDateTimeOffset](./todatetimeoffset/)(const String\&) | Convierte el [String](../../system/string/) suministrado a su equivalente [DateTimeOffset](../../system/datetimeoffset/). |
| static [ToDateTimeOffset](./todatetimeoffset/)(const String\&, const String\&) | Convierte el [String](../../system/string/) suministrado a su equivalente [DateTimeOffset](../../system/datetimeoffset/). |
| static [ToDateTimeOffset](./todatetimeoffset/)(const String\&, const ArrayPtr\<String\>\&) | Convierte el [String](../../system/string/) suministrado a su equivalente [DateTimeOffset](../../system/datetimeoffset/). |
| static [ToDecimal](./todecimal/)(const String\&) | Convierte el [String](../../system/string/) a su equivalente [Decimal](../../system/decimal/). |
| static [ToDouble](./todouble/)(String) | Convierte el [String](../../system/string/) a su equivalente [Double](../../system/double/). |
| static [ToGuid](./toguid/)(const String\&) | Convierte el [String](../../system/string/) a su equivalente [Guid](../../system/guid/). |
| static [ToInt16](./toint16/)(const String\&) | Convierte el [String](../../system/string/) a un equivalente [Int16](../../system/int16/). |
| static [ToInt32](./toint32/)(const String\&) | Convierte el [String](../../system/string/) a un equivalente [Int32](../../system/int32/). |
| static [ToInt64](./toint64/)(const String\&) | Convierte el [String](../../system/string/) a un equivalente [Int64](../../system/int64/). |
| static [ToSByte](./tosbyte/)(const String\&) | Convierte el [String](../../system/string/) a un equivalente [SByte](../../system/sbyte/). |
| static [ToSingle](./tosingle/)(String) | Convierte el [String](../../system/string/) a un equivalente [Single](../../system/single/). |
| static [ToString](./tostring/)(bool) | Convierte el [Boolean](../../system/boolean/) a una [String](../../system/string/). |
| static [ToString](./tostring/)(char16_t) | Convierte el [Char](../../system/char/) a una [String](../../system/string/). |
| static [ToString](./tostring/)(Decimal) | Convierte el [Decimal](../../system/decimal/) a una [String](../../system/string/). |
| static [ToString](./tostring/)(int8_t) | Convierte el [SByte](../../system/sbyte/) a una [String](../../system/string/). |
| static [ToString](./tostring/)(int16_t) | Convierte el [Int16](../../system/int16/) a una [String](../../system/string/). |
| static [ToString](./tostring/)(int32_t) | Convierte el [Int32](../../system/int32/) a una [String](../../system/string/). |
| static [ToString](./tostring/)(int64_t) | Convierte el [Int64](../../system/int64/) a una [String](../../system/string/). |
| static [ToString](./tostring/)(uint8_t) | Convierte el [Byte](../../system/byte/) a una [String](../../system/string/). |
| static [ToString](./tostring/)(uint16_t) | Convierte el [UInt16](../../system/uint16/) a una [String](../../system/string/). |
| static [ToString](./tostring/)(uint32_t) | Convierte el [UInt32](../../system/uint32/) a una [String](../../system/string/). |
| static [ToString](./tostring/)(uint64_t) | Convierte el [UInt64](../../system/uint64/) a una [String](../../system/string/). |
| static [ToString](./tostring/)(float) | Convierte el [Single](../../system/single/) a una [String](../../system/string/). |
| static [ToString](./tostring/)(double) | Convierte el [Double](../../system/double/) a una [String](../../system/string/). |
| static [ToString](./tostring/)(TimeSpan) | Convierte el [TimeSpan](../../system/timespan/) a una [String](../../system/string/). |
| static [ToString](./tostring/)(DateTime) | Convierte el [DateTime](../../system/datetime/) a una [String](../../system/string/). |
| static [ToString](./tostring/)(DateTime, const String\&) | Convierte el [DateTime](../../system/datetime/) a una [String](../../system/string/). |
| static [ToString](./tostring/)(DateTime, XmlDateTimeSerializationMode) | Convierte el [DateTime](../../system/datetime/) a una [String](../../system/string/) usando el [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/) especificado. |
| static [ToString](./tostring/)(DateTimeOffset) | Convierte el [DateTimeOffset](../../system/datetimeoffset/) suministrado a una [String](../../system/string/). |
| static [ToString](./tostring/)(DateTimeOffset, const String\&) | Convierte el [DateTimeOffset](../../system/datetimeoffset/) suministrado a una [String](../../system/string/) en el formato especificado. |
| static [ToString](./tostring/)(Guid) | Convierte el [Guid](../../system/guid/) a una [String](../../system/string/). |
| static [ToTimeSpan](./totimespan/)(const String\&) | Convierte el [String](../../system/string/) a un equivalente [TimeSpan](../../system/timespan/). |
| static [ToUInt16](./touint16/)(const String\&) | Convierte el [String](../../system/string/) a su equivalente [UInt16](../../system/uint16/). |
| static [ToUInt32](./touint32/)(const String\&) | Convierte el [String](../../system/string/) a su equivalente [UInt32](../../system/uint32/). |
| static [ToUInt64](./touint64/)(const String\&) | Convierte el [String](../../system/string/) a su equivalente [UInt64](../../system/uint64/). |
| static [VerifyName](./verifyname/)(const String\&) | Verifica que el nombre sea un nombre válido según la recomendación del Lenguaje de Marcado Extendido W3C. |
| static [VerifyNCName](./verifyncname/)(const String\&) | Verifica que el nombre sea un **NCName** válido según la recomendación del Lenguaje de Marcado Extendido W3C. Un **NCName** es un nombre que no puede contener dos puntos. |
| static [VerifyNMTOKEN](./verifynmtoken/)(const String\&) | Verifica que la cadena sea un NMTOKEN válido según la recomendación del XML [Schema](../../system.xml.schema/) Parte 2: Tipos de datos de W3C. |
| static [VerifyPublicId](./verifypublicid/)(const String\&) | Devuelve la instancia de cadena pasada si todos los caracteres del argumento de cadena son caracteres de identificación pública válidos. |
| static [VerifyTOKEN](./verifytoken/)(const String\&) | Verifica que la cadena sea un token válido según la recomendación del XML [Schema](../../system.xml.schema/) Parte 2: Tipos de datos de W3C. |
| static [VerifyWhitespace](./verifywhitespace/)(const String\&) | Devuelve la instancia de cadena pasada si todos los caracteres del argumento de cadena son caracteres de espacio en blanco válidos. |
| static [VerifyXmlChars](./verifyxmlchars/)(const String\&) | Devuelve la cadena pasada si todos los caracteres y los pares sustitutos en el argumento de cadena son caracteres XML válidos; de lo contrario, se lanza una [XmlException](../xmlexception/) con información sobre el primer carácter inválido encontrado. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
