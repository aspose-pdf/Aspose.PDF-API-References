---
title: "System::DateTime::ParseExact metod"
linktitle: "ParseExact"
second_title: "Aspose.PDF för C++ API-referens"
description: "Hur man använder ParseExact‑metoden i System::DateTime‑klassen i C++."
type: docs
weight: 6700
url: /sv/cpp/system/datetime/parseexact/
---
## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles)
```

## Se även

* Class [DateTime](../)
* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles)
```

## Se även

* Class [DateTime](../)
* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) method


Konverterar den angivna strängrepresentationen av ett datum‑ och tidsvärde till motsvarande [DateTime](../)‑objekt med hjälp av de angivna formaten, kultur‑specifik formatinformation och stil. Strängrepresentationens format måste exakt matcha ett eller flera av de angivna formaten. Kastar ett undantag om konverteringen misslyckas.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const String\& | Strängrepresentationen av ett datum‑ och tidsvärde att konvertera. |
| format | const ArrayPtr\<String\>\& | Arrayen av strängformat. |
| provider | const SharedPtr\<IFormatProvider\>\& | Objektet [IFormatProvider](../../iformatprovider/) som tillhandahåller kultur‑specifik formatinformation. |
| styles | Globalization::DateTimeStyles | En bitvis kombination av uppräkningens värden som ger ytterligare information om **s**, om stilelement som kan finnas i **s**, eller om konverteringen från **s** till ett [DateTime](../)‑objekt. |

### ReturnValue

En ny instans av [DateTime](../) klass som representerar datum‑ och tidsvärdet som motsvarar det som den angivna strängen representerar.

## Se även

* Class [DateTime](../)
* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles)
```

## Se även

* Class [DateTime](../)
* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## Se även

* Class [DateTime](../)
* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## Se även

* Class [DateTime](../)
* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) method


Konverterar den angivna strängrepresentationen av ett datum‑ och tidsvärde till motsvarande [DateTime](../)‑objekt med hjälp av det angivna formatet och kultur‑specifik formatinformation. Strängrepresentationens format måste exakt matcha det angivna formatet. Kastar ett undantag om konverteringen misslyckas.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const String\& | Strängrepresentationen av ett datum‑ och tidsvärde att konvertera. |
| format | const String\& | Strängformatet. |
| provider | const SharedPtr\<IFormatProvider\>\& | Objektet [IFormatProvider](../../iformatprovider/) som tillhandahåller kultur‑specifik formatinformation. |
| styles | Globalization::DateTimeStyles | En bitvis kombination av uppräkningens värden som ger ytterligare information om **s**, om stilelement som kan finnas i **s**, eller om konverteringen från **s** till ett [DateTime](../)‑objekt. |

### ReturnValue

En ny instans av [DateTime](../) klass som representerar datum‑ och tidsvärdet som motsvarar det som den angivna strängen representerar.

## Se även

* Class [DateTime](../)
* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::ParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## Se även

* Class [DateTime](../)
* Class [String](../../string/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
