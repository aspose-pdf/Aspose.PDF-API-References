---
title: "System::DateTimeOffset::TryParseExact metod"
linktitle: "TryParseExact"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::DateTimeOffset::TryParseExact metod. Försöker konvertera den angivna strängen till ett DateTimeOffset-objekt med hjälp av de angivna formaten, formatleverantören och formateringsstilen i C++."
type: docs
weight: 5800
url: /sv/cpp/system/datetimeoffset/tryparseexact/
---
## DateTimeOffset::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) method


Försöker konvertera den angivna strängen till [DateTimeOffset](../)-objekt med hjälp av de angivna formaten, formatleverantören och formateringsstilen.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const String\& | [String](../../string/) att konvertera. |
| format | const ArrayPtr\<String\>\& | Arrayer av formatsträngar. |
| leverantör | const SharedPtr\<IFormatProvider\>\& | Formatleverantör. |
| stilar | Globalization::DateTimeStyles | Datum- och tidsformateringsstilar. |
| result | DateTimeOffset\& | [DateTimeOffset](../) som är ekvivalent med **input**. |

### ReturnValue

Sant om **input** konverterades framgångsrikt, annars - falskt.

## Se även

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTimeOffset](../)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTimeOffset::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) method


Försöker konvertera den angivna strängen till ett [DateTimeOffset](../)-objekt med hjälp av det angivna formatet, formatleverantören och formateringsstilen.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const String\& | [String](../../string/) att konvertera. |
| format | const String\& | Formatsträng. |
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
