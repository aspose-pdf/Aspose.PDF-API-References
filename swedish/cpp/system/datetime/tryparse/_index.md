---
title: "System::DateTime::TryParse metod"
linktitle: "TryParse"
second_title: "Aspose.PDF för C++ API-referens"
description: "Hur man använder TryParse‑metoden i System::DateTime‑klassen i C++."
type: docs
weight: 6900
url: /sv/cpp/system/datetime/tryparse/
---
## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
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
## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
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
## DateTime::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) method


Konverterar den angivna strängrepresentationen av ett datum‑ och tidsvärde till motsvarande [DateTime](../)‑objekt med hjälp av den angivna kulturspecifika formatinformationen och stil.

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const String\& | Strängrepresentationen av ett datum‑ och tidsvärde att konvertera. |
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
## DateTime::TryParse(const String\&, DateTime\&) method


Konverterar den angivna strängrepresentationen av ett datum- och tidsvärde till motsvarande [DateTime](../)-objekt.

```cpp
static bool System::DateTime::TryParse(const String &s, DateTime &result)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const String\& | Strängrepresentationen av ett datum‑ och tidsvärde att konvertera. |
| result | DateTime\& | Utdataargumentet som, om konverteringen lyckas, innehåller resultatet av konverteringen. |

### ReturnValue

Sant om konverteringen lyckas, annars - falskt.

## Se även

* Class [String](../../string/)
* Class [DateTime](../)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTime::TryParse(const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## Se även

* Class [String](../../string/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTime](../)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
