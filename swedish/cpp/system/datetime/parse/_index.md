---
title: "System::DateTime::Parse metod"
linktitle: "Analysera"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::DateTime::Parse metod. Konverterar den angivna strängrepresentationen av ett datum- och tidsvärde till motsvarande DateTime-objekt i C++."
type: docs
weight: 6600
url: /sv/cpp/system/datetime/parse/
---
## DateTime::Parse(const String\&) method


Konverterar den angivna strängrepresentationen av ett datum- och tidsvärde till motsvarande [DateTime](../)-objekt.

```cpp
static DateTime System::DateTime::Parse(const String &s)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const String\& | Strängrepresentationen av ett datum‑ och tidsvärde att konvertera. |

### ReturnValue

En ny instans av [DateTime](../) klass som representerar datum‑ och tidsvärdet som motsvarar det som den angivna strängen representerar.

## Se även

* Class [DateTime](../)
* Class [String](../../string/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
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
## DateTime::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
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
## DateTime::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) method


Konverterar den angivna strängrepresentationen av ett datum- och tidsvärde till motsvarande [DateTime](../)-objekt med kultur‑specifik formatinformation.

```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const String\& | Strängrepresentationen av ett datum‑ och tidsvärde att konvertera. |
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
## DateTime::Parse(const String\&, std::nullptr_t, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::Parse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## Se även

* Class [DateTime](../)
* Class [String](../../string/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
