---
title: "System::Int32::TryParse metod"
linktitle: "TryParse"
second_title: "Aspose.PDF för C++ API-referens"
description: "Hur man använder TryParse‑metoden i System::Int32‑klassen i C++."
type: docs
weight: 200
url: /sv/cpp/system/int32/tryparse/
---
## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int32_t\&) method




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int32_t &result)
```

## Se även

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [Int32](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int32_t\&) method




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int32_t &result)
```

## Se även

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Int32](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int32_t\&) method


Konverterar den angivna strängen som innehåller talets textrepresentation till motsvarande 32-bitars signerade heltal med den angivna formateringsinformationen och talstil.

```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int32_t &result)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | const String\& | Strängen att konvertera. |
| stilar | Globalization::NumberStyles | En bitvis kombination av värden i NumberStyles‑enumerationen som specificerar den tillåtna stilen för ett tal i strängrepresentation. |
| leverantör | const SharedPtr\<IFormatProvider\>\& | En pekare till ett objekt som innehåller information om strängformat. |
| result | int32_t\& | Referensen till en 32‑bitars signerad heltalsvariabel där konverteringsresultatet placeras. |

### ReturnValue

Sant om konverteringen lyckades, annars - falskt.

## Se även

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Int32](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Int32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int32_t\&) method




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int32_t &result)
```

## Se även

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Class [Int32](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Int32::TryParse(const String\&, int32_t\&) method


Konverterar den angivna strängen som innehåller talets textrepresentation till motsvarande 32-bitars signerade heltal.

```cpp
static bool System::Int32::TryParse(const String &value, int32_t &result)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | const String\& | Strängen att konvertera. |
| result | int32_t\& | Referensen till en 32‑bitars signerad heltalsvariabel där konverteringsresultatet placeras. |

### ReturnValue

Sant om konverteringen lyckades, annars - falskt.

## Se även

* Class [String](../../string/)
* Class [Int32](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
