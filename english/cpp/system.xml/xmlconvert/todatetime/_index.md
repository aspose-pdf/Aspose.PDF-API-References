---
title: System::Xml::XmlConvert::ToDateTime method
linktitle: ToDateTime
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlConvert::ToDateTime method. Converts the String to a DateTime equivalent in C++.'
type: docs
weight: 1400
url: /cpp/system.xml/xmlconvert/todatetime/
---
## XmlConvert::ToDateTime(const String\&) method


Converts the [String](../../../system/string/) to a [DateTime](../../../system/datetime/) equivalent.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s)
```


| Parameter | Type | Description |
| --- | --- | --- |
| s | const String\& | The string to convert. |

### ReturnValue

A [DateTime](../../../system/datetime/) equivalent of the string.

## See Also

* Class [DateTime](../../../system/datetime/)
* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlConvert::ToDateTime(const String\&, const ArrayPtr\<String\>\&) method


Converts the [String](../../../system/string/) to a [DateTime](../../../system/datetime/) equivalent.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const ArrayPtr<String> &formats)
```


| Parameter | Type | Description |
| --- | --- | --- |
| s | const String\& | The string to convert. |
| formats | const ArrayPtr\<String\>\& | An array containing the format structures to apply to the converted [DateTime](../../../system/datetime/). Valid formats include "yyyy-MM-ddTHH:mm:sszzzzzz" and its subsets. |

### ReturnValue

A [DateTime](../../../system/datetime/) equivalent of the string.

## See Also

* Class [DateTime](../../../system/datetime/)
* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlConvert::ToDateTime(const String\&, const String\&) method


Converts the [String](../../../system/string/) to a [DateTime](../../../system/datetime/) equivalent.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const String &format)
```


| Parameter | Type | Description |
| --- | --- | --- |
| s | const String\& | The string to convert. |
| format | const String\& | The format structure to apply to the converted [DateTime](../../../system/datetime/). Valid formats include "yyyy-MM-ddTHH:mm:sszzzzzz" and its subsets. The string is validated against this format. |

### ReturnValue

A [DateTime](../../../system/datetime/) equivalent of the string.

## See Also

* Class [DateTime](../../../system/datetime/)
* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlConvert::ToDateTime(const String\&, XmlDateTimeSerializationMode) method


Converts the [String](../../../system/string/) to a [DateTime](../../../system/datetime/) using the [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/) specified.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, XmlDateTimeSerializationMode dateTimeOption)
```


| Parameter | Type | Description |
| --- | --- | --- |
| s | const String\& | The [String](../../../system/string/) value to convert. |
| dateTimeOption | XmlDateTimeSerializationMode | One of the enumeration values that specify whether the date should be converted to local time or preserved as Coordinated Universal Time (UTC), if it is a UTC date. |

### ReturnValue

A [DateTime](../../../system/datetime/) equivalent of the [String](../../../system/string/).

## See Also

* Class [DateTime](../../../system/datetime/)
* Class [String](../../../system/string/)
* Enum [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
