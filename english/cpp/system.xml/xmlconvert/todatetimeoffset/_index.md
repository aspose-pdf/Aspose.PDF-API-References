---
title: System::Xml::XmlConvert::ToDateTimeOffset method
linktitle: ToDateTimeOffset
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlConvert::ToDateTimeOffset method. Converts the supplied String to a DateTimeOffset equivalent in C++.'
type: docs
weight: 1500
url: /cpp/system.xml/xmlconvert/todatetimeoffset/
---
## XmlConvert::ToDateTimeOffset(const String\&) method


Converts the supplied [String](../../../system/string/) to a [DateTimeOffset](../../../system/datetimeoffset/) equivalent.

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s)
```


| Parameter | Type | Description |
| --- | --- | --- |
| s | const String\& | The string to convert. The string must conform to a subset of the W3C Recommendation for the XML dateTime type. For more information, see the [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) section of the XML [Schema](../../../system.xml.schema/) specification. |

### ReturnValue

The [DateTimeOffset](../../../system/datetimeoffset/) equivalent of the supplied string.

## See Also

* Class [DateTimeOffset](../../../system/datetimeoffset/)
* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlConvert::ToDateTimeOffset(const String\&, const ArrayPtr\<String\>\&) method


Converts the supplied [String](../../../system/string/) to a [DateTimeOffset](../../../system/datetimeoffset/) equivalent.

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const ArrayPtr<String> &formats)
```


| Parameter | Type | Description |
| --- | --- | --- |
| s | const String\& | The string to convert. |
| formats | const ArrayPtr\<String\>\& | An array of formats from which **s** can be converted. Each format in **formats** can be any subset of the W3C Recommendation for the XML dateTime type. For more information, see the [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) section of the XML [Schema](../../../system.xml.schema/) specification. The string **s** is validated against one of these formats. |

### ReturnValue

The [DateTimeOffset](../../../system/datetimeoffset/) equivalent of the supplied string.

## See Also

* Class [DateTimeOffset](../../../system/datetimeoffset/)
* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlConvert::ToDateTimeOffset(const String\&, const String\&) method


Converts the supplied [String](../../../system/string/) to a [DateTimeOffset](../../../system/datetimeoffset/) equivalent.

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const String &format)
```


| Parameter | Type | Description |
| --- | --- | --- |
| s | const String\& | The string to convert. |
| format | const String\& | The format from which **s** is converted. The format parameter can be any subset of the W3C Recommendation for the XML dateTime type. For more information, see the [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) section of the XML [Schema](../../../system.xml.schema/) specification. The string **s** is validated against this format. |

### ReturnValue

The [DateTimeOffset](../../../system/datetimeoffset/) equivalent of the supplied string.

## See Also

* Class [DateTimeOffset](../../../system/datetimeoffset/)
* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
