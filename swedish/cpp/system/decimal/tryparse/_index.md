---
title: "System::Decimal::TryParse metod"
linktitle: "TryParse"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Decimal::TryParse metod. Konverterar den angivna strängen som innehåller en strängrepresentation av ett tal till motsvarande Decimal‑värde i C++."
type: docs
weight: 5800
url: /sv/cpp/system/decimal/tryparse/
---
## Decimal::TryParse(const String\&, Decimal\&) method


Konverterar den angivna strängen som innehåller en strängrepresentation av ett tal till motsvarande [Decimal](../)-värde.

```cpp
static bool System::Decimal::TryParse(const String &value, Decimal &result)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | const String\& | Strängen att konvertera |
| result | Decimal\& | Referensen till en [Decimal](../)-variabel där resultatet av konverteringen placeras |

### ReturnValue

Sant om konverteringen lyckades, annars - falskt

## Se även

* Class [String](../../string/)
* Class [Decimal](../)
* Class [Decimal](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Decimal::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, Decimal\&) method


Konverterar den angivna strängen som innehåller en strängrepresentation av ett tal till motsvarande [Decimal](../)-värde med den medföljande formateringsinformationen och talstilen.

```cpp
static bool System::Decimal::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, Decimal &result)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | const String\& | Strängen att konvertera |
| stilar | Globalization::NumberStyles | En bitvis kombination av värden i NumberStyles-uppräkningen som specificerar den tillåtna stilen för en strängrepresentation av ett tal |
| leverantör | const SharedPtr\<IFormatProvider\>\& | En pekare till ett objekt som innehåller strängformatinformationen |
| result | Decimal\\& | Ett utdataargument; innehåller resultatet av konverteringen |

### ReturnValue

Sant om konverteringen lyckades, annars - falskt

## Se även

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Decimal](../)
* Class [Decimal](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
