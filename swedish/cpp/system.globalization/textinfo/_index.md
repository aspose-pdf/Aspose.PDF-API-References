---
title: "System::Globalization::TextInfo class"
linktitle: "TextInfo"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Globalization::TextInfo class. Definierar lokalspecifika textegenskaper. Sättningsoperationer är endast aktiverade på objekt som inte är skrivskyddade. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 2800
url: /sv/cpp/system.globalization/textinfo/
---
## TextInfo class


Definierar lokalspecifika textegenskaper. Sättningsoperationer är endast aktiverade på objekt som inte är skrivskyddade. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class TextInfo : public System::ICloneable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clone](./clone/)() override | RTTI-information. |
| [Equals](./equals/)(SharedPtr\<Object\>) override |  |
| virtual [get_ANSICodePage](./get_ansicodepage/)() const | Hämtar ANSI-kodtabell. |
| [get_CultureName](./get_culturename/)() const | Hämtar kulturnamn. |
| virtual [get_EBCDICCodePage](./get_ebcdiccodepage/)() const | Hämtar EBCDIC-kodtabell. |
| [get_IsReadOnly](./get_isreadonly/)() const | Kontrollerar om formatet är skrivskyddat. |
| [get_IsRightToLeft](./get_isrighttoleft/)() const | Kontrollerar om texten är skriven från vänster till höger. |
| [get_LCID](./get_lcid/)() const | Hämtar lokal-ID. |
| virtual [get_ListSeparator](./get_listseparator/)() const | Hämtar listseparator. |
| virtual [get_MacCodePage](./get_maccodepage/)() const | Hämtar Macintosh-kodtabell. |
| virtual [get_OEMCodePage](./get_oemcodepage/)() const | Hämtar OEM-kodtabell. |
| [GetHashCode](./gethashcode/)() const override | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/) metod. Möjliggör hashning av anpassade objekt. |
| [operator=](./operator=/)(const TextInfo\&) |  |
| static [ReadOnly](./readonly/)(const TextInfoPtr\&) | Hämtar en skrivskyddad version av kultur. |
| virtual [set_ListSeparator](./set_listseparator/)(String) | Ställer in listseparator. |
| [TextInfo](./textinfo/)(const TextInfo\&) | RTTI-information. |
| virtual [ToLower](./tolower/)(char_t) const | Konverterar tecken till gemener. |
| virtual [ToLower](./tolower/)(String) const | Konverterar sträng till gemener. |
| [ToString](./tostring/)() const override | Analog till C#-metoden [Object.ToString()](../../system/object/tostring/). Gör det möjligt att konvertera anpassade objekt till sträng. |
| [ToTitleCase](./totitlecase/)(String) const | Konverterar sträng till titelformat (förutom akronymer som redan är i versaler). |
| virtual [ToUpper](./toupper/)(char_t) const | Konverterar tecken till versaler. |
| virtual [ToUpper](./toupper/)(String) const | Konverterar sträng till versaler. |
## Se även

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
