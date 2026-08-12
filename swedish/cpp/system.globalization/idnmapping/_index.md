---
title: "System::Globalization::IdnMapping class"
linktitle: "IdnMapping"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Globalization::IdnMapping-klass. IdnMapping används för att mappa namn till Punycode. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assert-fel. Wrappa alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 1300
url: /sv/cpp/system.globalization/idnmapping/
---
## IdnMapping class


[IdnMapping](./) used to map names to Punycode. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class IdnMapping : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Jämför två [IdnMapping](./)-objekt. |
| [get_AllowUnassigned](./get_allowunassigned/)() const | Hämtar flagga som indikerar om odefinierade kodpunkter används i operationer. |
| [get_UseStd3AsciiRules](./get_usestd3asciirules/)() const | Hämtar flagga som indikerar om standardnamngivningskonventioner används i operationer. |
| [GetAscii](./getascii/)(const String\&) const | [Convert](../../system/convert/) unicode-domännamn till motsvarande ascii. |
| [GetAscii](./getascii/)(const String\&, int) const | [Convert](../../system/convert/) unicode-domännamn till motsvarande ascii. |
| [GetAscii](./getascii/)(const String\&, int, int) const | [Convert](../../system/convert/) unicode-domännamn till motsvarande ascii. |
| [GetHashCode](./gethashcode/)() const override | Hämtar hashkod för aktuellt [IdnMapping](./)-objekt. |
| [GetUnicode](./getunicode/)(const String\&) const | [Convert](../../system/convert/) ascii-domännamn till motsvarande unicode. |
| [GetUnicode](./getunicode/)(const String\&, int) const | [Convert](../../system/convert/) ascii-domännamn till motsvarande unicode. |
| [GetUnicode](./getunicode/)(const String\&, int, int) const | [Convert](../../system/convert/) ascii-domännamn till motsvarande unicode. |
| [IdnMapping](./idnmapping/)() | RTTI-information. |
| [IdnMapping](./idnmapping/)(const IdnMapping\&) |  |
| [operator=](./operator=/)(const IdnMapping\&) |  |
| [set_AllowUnassigned](./set_allowunassigned/)(bool) | Ställer in flagga som indikerar om odefinierade kodpunkter används i operationer. |
| [set_UseStd3AsciiRules](./set_usestd3asciirules/)(bool) | Ställer in flagga som indikerar om standardnamngivningskonventioner används i operationer. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
