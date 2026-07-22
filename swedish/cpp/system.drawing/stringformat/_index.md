---
title: "System::Drawing::StringFormat klass"
linktitle: "StringFormat"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::StringFormat klass. Inkapslar information om textlayout, displaymanipulationer och OpenType-funktioner. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 2500
url: /sv/cpp/system.drawing/stringformat/
---
## StringFormat class


Inkapslar information om textlayout, displaymanipulationer och OpenType-funktioner. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class StringFormat : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clone](./clone/)() | Returnerar en exakt kopia av det aktuella objektet. |
| [get_Alignment](./get_alignment/)() const | Returnerar ett värde som indikerar horisontell justering av strängen. |
| [get_DigitSubstitutionLanguage](./get_digitsubstitutionlanguage/)() const | Returnerar ett värde som anger språket som används när lokala siffror ersätts med västerländska siffror. |
| [get_DigitSubstitutionMethod](./get_digitsubstitutionmethod/)() const | Returnerar metod för siffrors substitution. |
| [get_FormatFlags](./get_formatflags/)() const | Returnerar en bitvis kombination av [StringFormatFlags](../stringformatflags/) som specificerar strängformatet som representeras av det aktuella objektet. |
| static [get_GenericDefault](./get_genericdefault/)() | Returnerar ett [StringFormat](./)‑objekt som representerar ett generiskt standardformat. |
| static [get_GenericTypographic](./get_generictypographic/)() | Returnerar ett [StringFormat](./)‑objekt som representerar ett generiskt typografiskt format. |
| [get_HotkeyPrefix](./get_hotkeyprefix/)() const | Returnerar värdet som indikerar hur snabbtangentsprefixet visas. |
| [get_LineAlignment](./get_linealignment/)() const | Returnerar ett värde som indikerar vertikal justering av strängen. |
| [get_Trimming](./get_trimming/)() const | Returnerar ett värde som indikerar hur strängen trimmas. |
| [GetCharacterRangesCount](./getcharacterrangescount/)() const | Hämtar storleken på [CharacterRange](../characterrange/)‑arrayen. |
| [GetTabStops](./gettabstops/)(float\&) const | Returnerar tabbstopp för det aktuella [StringFormat](./)‑objektet. |
| [set_Alignment](./set_alignment/)(StringAlignment) | Ställer in horisontell justering av strängen. |
| [set_FormatFlags](./set_formatflags/)(StringFormatFlags) | Ställer in flaggorna för strängformatet. |
| [set_HotkeyPrefix](./set_hotkeyprefix/)(Text::HotkeyPrefix) | Ställer in värdet som specificerar hur snabbtangentsprefixet ska visas. |
| [set_LineAlignment](./set_linealignment/)(StringAlignment) | Ställer in vertikal justering av strängen. |
| [set_Trimming](./set_trimming/)(StringTrimming) | Ställer in ett värde som specificerar hur strängen trimmas. |
| [SetDigitSubstitution](./setdigitsubstitution/)(int32_t, StringDigitSubstitute) | Ställer in språk och metod för sifferersättning. |
| [SetMeasurableCharacterRanges](./setmeasurablecharacterranges/)(const ArrayPtr\<CharacterRange\>\&) | Ställer in en array av [CharacterRange](../characterrange/)-objekt som representerar teckenintervallen som mäts av ett anrop till metoden MeasureCharacterRanges(). |
| [SetTabStops](./settabstops/)(float, const ArrayPtr\<float\>\&) | Ställer in tabbstopp för det aktuella [StringFormat](./)-objektet. |
| [StringFormat](./stringformat/)() | Skapar en ny instans av klassen [StringFormat](./). |
| [StringFormat](./stringformat/)(StringFormatFlags, int32_t) | Skapar en ny instans av klassen [StringFormat](./) med de angivna formatflaggan och språket. |
| [StringFormat](./stringformat/)(const SharedPtr\<StringFormat\>\&) | Kopieringskonstruktor. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
