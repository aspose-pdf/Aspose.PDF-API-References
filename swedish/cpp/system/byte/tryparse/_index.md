---
title: "System::Byte::TryParse-metoden"
linktitle: "TryParse"
second_title: "Aspose.PDF för C++ API-referens"
description: "Hur man använder TryParse‑metoden i System::Byte‑klassen i C++."
type: docs
weight: 200
url: /sv/cpp/system/byte/tryparse/
---
## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint8_t\&) method




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint8_t &result)
```

## Se även

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [Byte](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint8_t\&) method




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint8_t &result)
```

## Se även

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Byte](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint8_t\&) method


Konverterar den angivna strängen som innehåller en strängrepresentation av ett tal till motsvarande 8‑bit‑osignerade heltal med hjälp av den angivna formateringsinformationen och talstilen.

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint8_t &result)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | const String\& | Strängen att konvertera. |
| stilar | Globalization::NumberStyles | En bitvis kombination av värden i NumberStyles‑enumerationen som specificerar den tillåtna stilen för ett tal i strängrepresentation. |
| leverantör | const SharedPtr\<IFormatProvider\>\& | En pekare till ett objekt som innehåller information om strängformat. |
| result | uint8_t\& | Referensen till en 8‑bitars osignerad heltalsvariabel där resultatet av konverteringen placeras. |

### ReturnValue

Sant om konverteringen lyckades, annars - falskt.

## Se även

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Byte](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Byte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint8_t\&) method




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint8_t &result)
```

## Se även

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Class [Byte](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Byte::TryParse(const String\&, uint8_t\&) method


Konverterar den angivna strängen som innehåller en strängrepresentation av ett tal till motsvarande 8‑bit‑osignerade heltal.

```cpp
static bool System::Byte::TryParse(const String &value, uint8_t &result)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | const String\& | Strängen att konvertera. |
| result | uint8_t\& | Referensen till en 8‑bitars osignerad heltalsvariabel där resultatet av konverteringen placeras. |

### ReturnValue

Sant om konverteringen lyckades, annars - falskt.

## Se även

* Class [String](../../string/)
* Class [Byte](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
