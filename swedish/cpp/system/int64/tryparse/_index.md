---
title: "System::Int64::TryParse metod"
linktitle: "TryParse"
second_title: "Aspose.PDF för C++ API-referens"
description: "Hur man använder TryParse‑metoden i System::Int64‑klassen i C++."
type: docs
weight: 200
url: /sv/cpp/system/int64/tryparse/
---
## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int64_t\&) method




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int64_t &result)
```

## Se även

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [Int64](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int64_t\&) method




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int64_t &result)
```

## Se även

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Int64](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int64_t\&) method


Konverterar den angivna strängen som innehåller talets textrepresentation till motsvarande 64-bitars signerade heltal med hjälp av den angivna formateringsinformationen och talstilen.

```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int64_t &result)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | const String\& | Strängen att konvertera. |
| stilar | Globalization::NumberStyles | En bitvis kombination av värden i NumberStyles‑enumerationen som specificerar den tillåtna stilen för ett tal i strängrepresentation. |
| leverantör | const SharedPtr\<IFormatProvider\>\& | En pekare till ett objekt som innehåller information om strängformat. |
| result | int64_t\& | Referensen till en 64‑bitssignerad heltalsvariabel där konverteringsresultatet placeras. |

### ReturnValue

Sant om konverteringen lyckades, annars - falskt.

## Se även

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Int64](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Int64::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int64_t\&) method




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int64_t &result)
```

## Se även

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Class [Int64](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Int64::TryParse(const String\&, int64_t\&) method


Konverterar den angivna strängen som innehåller talets strängrepresentation till motsvarande 64‑bit signed integer.

```cpp
static bool System::Int64::TryParse(const String &value, int64_t &result)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | const String\& | Strängen att konvertera. |
| result | int64_t\& | Referensen till en 64‑bitssignerad heltalsvariabel där konverteringsresultatet placeras. |

### ReturnValue

Sant om konverteringen lyckades, annars - falskt.

## Se även

* Class [String](../../string/)
* Class [Int64](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
