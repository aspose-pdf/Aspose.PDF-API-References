---
title: "System::DateTimeOffset::ParseExact method"
linktitle: "ParseExact"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::DateTimeOffset::ParseExact method. Konverterar den angivna strängen till ett DateTimeOffset-objekt med hjälp av de angivna formaten, formatleverantören och formateringsstilen i C++."
type: docs
weight: 5600
url: /sv/cpp/system/datetimeoffset/parseexact/
---
## DateTimeOffset::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) method


Konverterar den angivna strängen till ett [DateTimeOffset](../)-objekt med hjälp av de angivna formaten, formatleverantören och formateringsstilen.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const String\& | [String](../../string/) att konvertera. |
| formats | const ArrayPtr\<String\>\& | [Array](../../array/) av formatsträngar. |
| leverantör | const SharedPtr\<IFormatProvider\>\& | Formatleverantör. |
| stilar | Globalization::DateTimeStyles | Datum- och tidsformateringsstilar. |

### ReturnValue

[DateTimeOffset](../) that is equivalent to the **input**.

## Se även

* Class [DateTimeOffset](../)
* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DateTimeOffset::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) method


Konverterar den angivna strängen till ett [DateTimeOffset](../)-objekt med hjälp av det angivna formatet, formatleverantören och formateringsstilen.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const String\& | [String](../../string/) att konvertera. |
| format | const String\& | Formatsträng. |
| leverantör | const SharedPtr\<IFormatProvider\>\& | Formatleverantör. |
| stilar | Globalization::DateTimeStyles | Datum- och tidsformateringsstilar. |

### ReturnValue

[DateTimeOffset](../) that is equivalent to the **input**.

## Se även

* Class [DateTimeOffset](../)
* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
