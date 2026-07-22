---
title: "System::TimeSpan::TryParseExact metod"
linktitle: "TryParseExact"
second_title: "Aspose.PDF för C++ API-referens"
description: "Hur man använder TryParseExact‑metoden i System::TimeSpan‑klassen i C++."
type: docs
weight: 4500
url: /sv/cpp/system/timespan/tryparseexact/
---
## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## Se även

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## Se även

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## Se även

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## Se även

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles, TimeSpan\&) method


Konverterar en sträng till motsvarande [TimeSpan](../)-objekt med de angivna formaten, formatleverantören och stilarna, och returnerar konverteringsresultatet.

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles, TimeSpan &result)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const String\& | Indata-sträng. |
| formats | const ArrayPtr\<String\>\& | [Array](../../array/) av formatsträngar. |
| leverantör | const SharedPtr\<IFormatProvider\>\& | Formatleverantör som tillhandahåller kultur‑specifik formateringsinformation. |
| stilar | Globalization::TimeSpanStyles | Definierar element som kan finnas i inmatningssträngen. |
| result | TimeSpan\& | Tidsintervall som motsvarar strängen. |

### ReturnValue

Sant om strängen konverterades framgångsrikt; annars falskt.

## Se även

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) method


Konverterar en sträng till motsvarande [TimeSpan](../)-objekt med de angivna formaten och formatleverantören, och returnerar konverteringsresultatet.

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const String\& | Indata-sträng. |
| formats | const ArrayPtr\<String\>\& | [Array](../../array/) av formatsträngar. |
| leverantör | const SharedPtr\<IFormatProvider\>\& | Formatleverantör som tillhandahåller kultur‑specifik formateringsinformation. |
| result | TimeSpan\& | Tidsintervall som motsvarar strängen. |

### ReturnValue

Sant om strängen konverterades framgångsrikt; annars falskt.

## Se även

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::TimeSpanStyles, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## Se även

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, std::nullptr_t, TimeSpan &result)
```

## Se även

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## Se även

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## Se även

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## Se även

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## Se även

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles, TimeSpan\&) method


Konverterar en sträng till motsvarande [TimeSpan](../)-objekt med det angivna formatet, formatleverantören och stilarna, och returnerar konverteringsresultatet.

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles, TimeSpan &result)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const String\& | Indata-sträng. |
| format | const String\& | Standard‑ eller anpassad formatsträng. |
| leverantör | const SharedPtr\<IFormatProvider\>\& | Formatleverantör som tillhandahåller kultur‑specifik formateringsinformation. |
| stilar | Globalization::TimeSpanStyles | Definierar element som kan finnas i inmatningssträngen. |
| result | TimeSpan\& | Tidsintervall som motsvarar strängen. |

### ReturnValue

Sant om strängen konverterades framgångsrikt; annars falskt.

## Se även

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) method


Konverterar en sträng till motsvarande [TimeSpan](../)-objekt med det angivna formatet och formatleverantören, och returnerar konverteringsresultatet.

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const String\& | Indata-sträng. |
| format | const String\& | Standard‑ eller anpassad formatsträng. |
| leverantör | const SharedPtr\<IFormatProvider\>\& | Formatleverantör som tillhandahåller kultur‑specifik formateringsinformation. |
| result | TimeSpan\& | Tidsintervall som motsvarar strängen. |

### ReturnValue

Sant om strängen konverterades framgångsrikt; annars falskt.

## Se även

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::TryParseExact(const String\&, const String\&, std::nullptr_t, Globalization::TimeSpanStyles, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, std::nullptr_t, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## Se även

* Class [String](../../string/)
* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## TimeSpan::TryParseExact(const String\&, const String\&, std::nullptr_t, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, std::nullptr_t, TimeSpan &result)
```

## Se även

* Class [String](../../string/)
* Class [TimeSpan](../)
* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
