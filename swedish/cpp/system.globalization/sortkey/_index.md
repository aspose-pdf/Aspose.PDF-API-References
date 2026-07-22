---
title: "System::Globalization::SortKey klass"
linktitle: "SortKey"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Globalization::SortKey klass. Mappning av en sträng till dess sortnyckel. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 2200
url: /sv/cpp/system.globalization/sortkey/
---
## SortKey class


Mappning av en sträng till dess sortnyckel. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class SortKey : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [Compare](./compare/)(const SortKeyPtr\&, const SortKeyPtr\&) | Jämför två sortnycklar. |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Kontrollerar om det angivna objektet är lika med det aktuella [SortKey](./)‑objektet. |
| virtual [get_KeyData](./get_keydata/)() | Hämtar byte‑array som representerar det aktuella objektet. |
| virtual [get_OriginalString](./get_originalstring/)() | Hämtar den ursprungliga strängen som användes för att skapa detta objekt. |
| [GetHashCode](./gethashcode/)() const override | Hämtar hash‑kod för det aktuella [SortKey](./)‑objektet. |
| [operator=](./operator=/)(const SortKey\&) |  |
| [SortKey](./sortkey/)(const SortKey\&) |  |
| [ToString](./tostring/)() const override | Konverterar det aktuella objektet till dess strängrepresentation. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
