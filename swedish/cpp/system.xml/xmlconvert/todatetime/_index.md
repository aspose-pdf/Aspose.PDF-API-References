---
title: "System::Xml::XmlConvert::ToDateTime‑metod"
linktitle: "ToDateTime"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlConvert::ToDateTime‑metod. Konverterar String till en DateTime‑ekvivalent i C++."
type: docs
weight: 1400
url: /sv/cpp/system.xml/xmlconvert/todatetime/
---
## XmlConvert::ToDateTime(const String\&) method


Konverterar [String](../../../system/string/) till en [DateTime](../../../system/datetime/)‑ekvivalent.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const String\& | Strängen att konvertera. |

### ReturnValue

En [DateTime](../../../system/datetime/)‑ekvivalent av strängen.

## Se även

* Class [DateTime](../../../system/datetime/)
* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlConvert::ToDateTime(const String\&, const ArrayPtr\<String\>\&) method


Konverterar [String](../../../system/string/) till en [DateTime](../../../system/datetime/)‑ekvivalent.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const ArrayPtr<String> &formats)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const String\& | Strängen att konvertera. |
| formats | const ArrayPtr\<String\>\& | En array som innehåller formatstrukturer att tillämpa på den konverterade [DateTime](../../../system/datetime/). Giltiga format inkluderar "yyyy-MM-ddTHH:mm:sszzzzzz" och dess delmängder. |

### ReturnValue

En [DateTime](../../../system/datetime/)‑ekvivalent av strängen.

## Se även

* Class [DateTime](../../../system/datetime/)
* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlConvert::ToDateTime(const String\&, const String\&) method


Konverterar [String](../../../system/string/) till en [DateTime](../../../system/datetime/)‑ekvivalent.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const String &format)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const String\& | Strängen att konvertera. |
| format | const String\& | Formatstrukturen att tillämpa på den konverterade [DateTime](../../../system/datetime/). Giltiga format inkluderar "yyyy-MM-ddTHH:mm:sszzzzzz" och dess delmängder. Strängen valideras mot detta format. |

### ReturnValue

En [DateTime](../../../system/datetime/)‑ekvivalent av strängen.

## Se även

* Class [DateTime](../../../system/datetime/)
* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlConvert::ToDateTime(const String\&, XmlDateTimeSerializationMode) method


Konverterar [String](../../../system/string/) till en [DateTime](../../../system/datetime/) med den angivna [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, XmlDateTimeSerializationMode dateTimeOption)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const String\& | Värdet [String](../../../system/string/) att konvertera. |
| dateTimeOption | XmlDateTimeSerializationMode | Ett av uppräkningsvärdena som anger om datumet ska konverteras till lokal tid eller bevaras som Coordinated Universal Time (UTC), om det är ett UTC‑datum. |

### ReturnValue

En [DateTime](../../../system/datetime/) motsvarighet till [String](../../../system/string/).

## Se även

* Class [DateTime](../../../system/datetime/)
* Class [String](../../../system/string/)
* Enum [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
