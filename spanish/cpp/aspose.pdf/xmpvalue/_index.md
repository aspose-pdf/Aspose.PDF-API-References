---
title: "Aspose::Pdf::XmpValue class"
linktitle: "XmpValue"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::XmpValue class. Representa el valor XMP en C++."
type: docs
weight: 20900
url: /es/cpp/aspose.pdf/xmpvalue/
---
## XmpValue class


Representa el valor XMP.

```cpp
class XmpValue : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_IsArray](./get_isarray/)() | Devuelve true si [XmpValue](./) es una matriz. |
| [get_IsDateTime](./get_isdatetime/)() const | Devuelve true si el valor es DateTime. |
| [get_IsDouble](./get_isdouble/)() const | Devuelve true si el valor es de punto flotante. |
| [get_IsField](./get_isfield/)() | Devuelve true si [XmpValue](./) es un campo. |
| [get_IsInteger](./get_isinteger/)() const | Devuelve true si el valor es entero. |
| [get_IsNamedValue](./get_isnamedvalue/)() const | Devuelve true si [XmpValue](./) es un valor nombrado. |
| [get_IsNamedValues](./get_isnamedvalues/)() | Devuelve true si [XmpValue](./) representa valores nombrados. |
| [get_IsRaw](./get_israw/)() | El valor no es compatible/desconocido y se proporciona código XML sin procesar. |
| [get_IsString](./get_isstring/)() | Devuelve true si el valor es una cadena. |
| [get_IsStructure](./get_isstructure/)() | Devuelve true si [XmpValue](./) representa una estructura. |
| static [to_KeyValuePair](./to_keyvaluepair/)(const System::SharedPtr\<XmpValue\>\&) | Convierte [XmpValue](./) a un valor nombrado. |
| static [to_KeyValuePairArray](./to_keyvaluepairarray/)(const System::SharedPtr\<XmpValue\>\&) | Convierte XmlValue a un valor de colección nombrada. |
| static [to_ObjectArray](./to_objectarray/)(const System::SharedPtr\<XmpValue\>\&) | Convierte [XmpValue](./) en una matriz. |
| static [to_String](./to_string/)(const System::SharedPtr\<XmpValue\>\&) | Convierte [XmpValue](./) en una cadena. |
| static [to_XmpValue](./to_xmpvalue/)(const System::String\&) | Convierte una cadena a [XmpValue](./). |
| static [to_XmpValue](./to_xmpvalue/)(int32_t) | Convierte un entero en [XmpValue](./). |
| static [to_XmpValue](./to_xmpvalue/)(double) | Convierte un double en [XmpValue](./). |
| static [to_XmpValue](./to_xmpvalue/)(System::DateTime) | Convierte un DateTime en [XmpValue](./). |
| static [to_XmpValue](./to_xmpvalue/)(const System::ArrayPtr\<System::SharedPtr\<System::Object\>\>\&) | Convierte una matriz a [XmpValue](./). |
| static [to_XmpValueArray](./to_xmpvaluearray/)(const System::SharedPtr\<XmpValue\>\&) | Convierte [XmpValue](./) a una matriz. |
| [ToArray](./toarray/)() | Devuelve una matriz. |
| [ToDateTime](./todatetime/)() | Convierte a DateTime. |
| [ToDictionary](./todictionary/)() | Devuelve un diccionario que contiene valores nombrados. |
| [ToDouble](./todouble/)() | Convierte a double. |
| [ToField](./tofield/)() | Devuelve el valor XMP como campo XMP. |
| [ToInteger](./tointeger/)() | Convierte a entero. |
| [ToNamedValue](./tonamedvalue/)() | Devuelve el valor XMP como valor nombrado. |
| [ToNamedValues](./tonamedvalues/)() | Devuelve el valor XMP como colección de valores nombrados. |
| [ToRaw](./toraw/)() | Código XML sin procesar para valores desconocidos/no compatibles. |
| [ToString](./tostring/)(const System::SharedPtr\<System::IFormatProvider\>\&) | Devuelve la representación en cadena. |
| [ToString](./tostring/)() const override | Devuelve la representación en cadena de [XmpValue](./). |
| [ToStringValue](./tostringvalue/)() | Convierte a cadena. |
| [ToStructure](./tostructure/)() | Devuelve el valor XMP como estructura (conjunto de campos). |
| [XmpValue](./xmpvalue/)(const System::String\&) | Constructor para valor de cadena. |
| [XmpValue](./xmpvalue/)(int32_t) | Constructor para valor entero. |
| [XmpValue](./xmpvalue/)(double) | Constructor para valor de punto flotante. |
| [XmpValue](./xmpvalue/)(System::DateTime) | Constructor para valor de fecha y hora. |
| [XmpValue](./xmpvalue/)(const System::ArrayPtr\<System::SharedPtr\<XmpValue\>\>\&) | Constructor para valor de matriz. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
