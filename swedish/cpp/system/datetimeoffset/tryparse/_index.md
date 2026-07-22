---
title: "System::DateTimeOffset::TryParse metod"
linktitle: "TryParse"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::DateTimeOffset::TryParse metod. Försöker konvertera den angivna strängen till DateTimeOffset‑objektet med den angivna formatleverantören och formateringsstilen i C++."
type: docs
weight: 5700
url: /sv/cpp/system/datetimeoffset/tryparse/
---
## DateTimeOffset::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) method


Försöker konvertera den angivna strängen till [DateTimeOffset](../)-objektet med den angivna formatleverantören och formateringsstilen.

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const String\& | [String](../../string/) att konvertera. |
| leverantör | const SharedPtr\<IFormatProvider\>\& | Formatleverantör. |
| stilar | Globalization::DateTimeStyles | Datum- och tidsformateringsstilar. |
| result | DateTimeOffset\& | [DateTimeOffset](../) som är ekvivalent med **input**. |

### ReturnValue

Sant om **input** konverterades framgångsrikt, annars - falskt.

## Se även

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTimeOffset](../)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTimeOffset::TryParse(const String\&, DateTimeOffset\&) method


Försöker konvertera den angivna strängen till [DateTimeOffset](../)-objektet.

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, DateTimeOffset &result)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const String\& | [String](../../string/) att konvertera. |
| result | DateTimeOffset\& | [DateTimeOffset](../) som är ekvivalent med **input**. |

### ReturnValue

Sant om **input** konverterades framgångsrikt, annars - falskt.

## Se även

* Class [String](../../string/)
* Class [DateTimeOffset](../)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
