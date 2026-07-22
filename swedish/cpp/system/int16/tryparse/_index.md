---
title: "System::Int16::TryParse-metod"
linktitle: "TryParse"
second_title: "Aspose.PDF för C++ API-referens"
description: "Hur man använder TryParse-metoden i System::Int16-klassen i C++."
type: docs
weight: 200
url: /sv/cpp/system/int16/tryparse/
---
## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int16_t\&) method




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int16_t &result)
```

## Se även

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [Int16](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int16_t\&) method




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int16_t &result)
```

## Se även

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Int16](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int16_t\&) method


Konverterar den angivna strängen som innehåller talets strängrepresentation till motsvarande 16-bitars signerade heltal med hjälp av den angivna formateringsinformationen och talstilen.

```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int16_t &result)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | const String\& | Strängen att konvertera. |
| stilar | Globalization::NumberStyles | En bitvis kombination av värden i NumberStyles‑enumerationen som specificerar den tillåtna stilen för ett tal i strängrepresentation. |
| leverantör | const SharedPtr\<IFormatProvider\>\& | En pekare till ett objekt som innehåller information om strängformat. |
| result | int16_t\& | Referensen till en 16-bitars signerad heltalsvariabel där resultatet av konverteringen placeras. |

### ReturnValue

Sant om konverteringen lyckades, annars - falskt.

## Se även

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Int16](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Int16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int16_t\&) method




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int16_t &result)
```

## Se även

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Class [Int16](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Int16::TryParse(const String\&, int16_t\&) method


Konverterar den angivna strängen som innehåller talets strängrepresentation till motsvarande 16-bitars signerade heltal.

```cpp
static bool System::Int16::TryParse(const String &value, int16_t &result)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | const String\& | Strängen att konvertera. |
| result | int16_t\& | Referensen till en 16-bitars signerad heltalsvariabel där resultatet av konverteringen placeras. |

### ReturnValue

Sant om konverteringen lyckades, annars - falskt.

## Se även

* Class [String](../../string/)
* Class [Int16](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
