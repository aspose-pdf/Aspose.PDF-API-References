---
title: "System::DateTime::TryParseExact metod"
linktitle: "TryParseExact"
second_title: "Aspose.PDF för C++ API-referens"
description: "Hur man använder TryParseExact-metoden i System::DateTime-klassen i C++."
type: docs
weight: 7000
url: /sv/cpp/system/datetime/tryparseexact/
---
## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## Se även

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## Se även

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) method


Konverterar den angivna strängrepresentationen av ett datum- och tidsvärde till motsvarande [DateTime](../) objekt med hjälp av de angivna formaten, kultur‑specifik formatinformation och stil. Strängrepresentationens format måste exakt matcha ett eller flera av de angivna formaten.

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const String\& | Strängrepresentationen av ett datum‑ och tidsvärde att konvertera. |
| format | const ArrayPtr\<String\>\& | Arrayen av strängformat. |
| provider | const SharedPtr\<IFormatProvider\>\& | Objektet [IFormatProvider](../../iformatprovider/) som tillhandahåller kultur‑specifik formatinformation. |
| styles | Globalization::DateTimeStyles | En bitvis kombination av uppräkningens värden som ger ytterligare information om **s**, om stilelement som kan finnas i **s**, eller om konverteringen från **s** till ett [DateTime](../)‑objekt. |
| result | DateTime\& | Utdataargumentet som, om konverteringen lyckas, innehåller resultatet av konverteringen. |

### ReturnValue

Sant om konverteringen lyckas, annars - falskt.

## Se även

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## Se även

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## Se även

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## Se även

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) method


Konverterar den angivna strängrepresentationen av ett datum- och tidsvärde till motsvarande [DateTime](../)-objekt med hjälp av det angivna formatet, kultur‑specifik formatinformation och stil. Formatet för strängrepresentationen måste exakt matcha det angivna formatet.

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const String\& | Strängrepresentationen av ett datum‑ och tidsvärde att konvertera. |
| format | const String\& | Strängformatet. |
| provider | const SharedPtr\<IFormatProvider\>\& | Objektet [IFormatProvider](../../iformatprovider/) som tillhandahåller kultur‑specifik formatinformation. |
| styles | Globalization::DateTimeStyles | En bitvis kombination av uppräkningens värden som ger ytterligare information om **s**, om stilelement som kan finnas i **s**, eller om konverteringen från **s** till ett [DateTime](../)‑objekt. |
| result | DateTime\& | Utdataargumentet som, om konverteringen lyckas, innehåller resultatet av konverteringen. |

### ReturnValue

Sant om konverteringen lyckas, annars - falskt.

## Se även

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::TryParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## Se även

* Class [String](../../string/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
