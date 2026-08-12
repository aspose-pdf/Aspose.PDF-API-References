---
title: "System::Xml::XmlConvert::ToDateTime método"
linktitle: "ToDateTime"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlConvert::ToDateTime método. Convierte el String a un equivalente DateTime en C++."
type: docs
weight: 1400
url: /es/cpp/system.xml/xmlconvert/todatetime/
---
## XmlConvert::ToDateTime(const String\&) method


Convierte el [String](../../../system/string/) a un equivalente [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | const String\& | La cadena a convertir. |

### ReturnValue

Un equivalente [DateTime](../../../system/datetime/) de la cadena.

## Ver también

* Class [DateTime](../../../system/datetime/)
* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlConvert::ToDateTime(const String\&, const ArrayPtr\<String\>\&) method


Convierte el [String](../../../system/string/) a un equivalente [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const ArrayPtr<String> &formats)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | const String\& | La cadena a convertir. |
| formats | const ArrayPtr\<String\>\& | Una matriz que contiene las estructuras de formato para aplicar al [DateTime](../../../system/datetime/) convertido. Los formatos válidos incluyen "yyyy-MM-ddTHH:mm:sszzzzzz" y sus subconjuntos. |

### ReturnValue

Un equivalente [DateTime](../../../system/datetime/) de la cadena.

## Ver también

* Class [DateTime](../../../system/datetime/)
* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlConvert::ToDateTime(const String\&, const String\&) method


Convierte el [String](../../../system/string/) a un equivalente [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const String &format)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | const String\& | La cadena a convertir. |
| format | const String\& | La estructura de formato a aplicar al [DateTime](../../../system/datetime/) convertido. Los formatos válidos incluyen "yyyy-MM-ddTHH:mm:sszzzzzz" y sus subconjuntos. La cadena se valida contra este formato. |

### ReturnValue

Un equivalente [DateTime](../../../system/datetime/) de la cadena.

## Ver también

* Class [DateTime](../../../system/datetime/)
* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlConvert::ToDateTime(const String\&, XmlDateTimeSerializationMode) method


Convierte el [String](../../../system/string/) a un [DateTime](../../../system/datetime/) usando el [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/) especificado.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, XmlDateTimeSerializationMode dateTimeOption)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | const String\& | El valor [String](../../../system/string/) a convertir. |
| dateTimeOption | XmlDateTimeSerializationMode | Uno de los valores de enumeración que especifican si la fecha debe convertirse a hora local o preservarse como Tiempo Universal Coordinado (UTC), si es una fecha UTC. |

### ReturnValue

Un equivalente de [DateTime](../../../system/datetime/) al [String](../../../system/string/).

## Ver también

* Class [DateTime](../../../system/datetime/)
* Class [String](../../../system/string/)
* Enum [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
