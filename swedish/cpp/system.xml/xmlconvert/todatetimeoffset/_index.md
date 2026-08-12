---
title: "System::Xml::XmlConvert::ToDateTimeOffset metod"
linktitle: "ToDateTimeOffset"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlConvert::ToDateTimeOffset metod. Konverterar den angivna String till en DateTimeOffset‑ekvivalent i C++."
type: docs
weight: 1500
url: /sv/cpp/system.xml/xmlconvert/todatetimeoffset/
---
## XmlConvert::ToDateTimeOffset(const String\&) method


Konverterar den angivna [String](../../../system/string/) till en [DateTimeOffset](../../../system/datetimeoffset/) ekvivalent.

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const String\& | Strängen att konvertera. Strängen måste följa en delmängd av W3C-rekommendationen för XML dateTime-typen. För mer information, se avsnittet [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) i XML [Schema](../../../system.xml.schema/) specifikationen. |

### ReturnValue

Den [DateTimeOffset](../../../system/datetimeoffset/) motsvarigheten till den angivna strängen.

## Se även

* Class [DateTimeOffset](../../../system/datetimeoffset/)
* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlConvert::ToDateTimeOffset(const String\&, const ArrayPtr\<String\>\&) method


Konverterar den angivna [String](../../../system/string/) till en [DateTimeOffset](../../../system/datetimeoffset/) ekvivalent.

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const ArrayPtr<String> &formats)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const String\& | Strängen att konvertera. |
| formats | const ArrayPtr\<String\>\& | En matris av format som **s** kan konverteras från. Varje format i **formats** kan vara en valfri delmängd av W3C-rekommendationen för XML dateTime-typen. För mer information, se avsnittet [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) i XML [Schema](../../../system.xml.schema/) specifikationen. Strängen **s** valideras mot ett av dessa format. |

### ReturnValue

Den [DateTimeOffset](../../../system/datetimeoffset/) motsvarigheten till den angivna strängen.

## Se även

* Class [DateTimeOffset](../../../system/datetimeoffset/)
* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlConvert::ToDateTimeOffset(const String\&, const String\&) method


Konverterar den angivna [String](../../../system/string/) till en [DateTimeOffset](../../../system/datetimeoffset/) ekvivalent.

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const String &format)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const String\& | Strängen att konvertera. |
| format | const String\& | Formatet som **s** konverteras från. Formatparametern kan vara en valfri delmängd av W3C-rekommendationen för XML dateTime-typen. För mer information, se avsnittet [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) i XML [Schema](../../../system.xml.schema/) specifikationen. Strängen **s** valideras mot detta format. |

### ReturnValue

Den [DateTimeOffset](../../../system/datetimeoffset/) motsvarigheten till den angivna strängen.

## Se även

* Class [DateTimeOffset](../../../system/datetimeoffset/)
* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
