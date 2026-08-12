---
title: "System::Globalization::SortVersion klass"
linktitle: "SortVersion"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Globalization::SortVersion-klass. Tillhandahåller information om Unicode-version som används för att jämföra och sortera strängar. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 2300
url: /sv/cpp/system.globalization/sortversion/
---
## SortVersion class


Tillhandahåller information om Unicode-version som används för att jämföra och sortera strängar. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class SortVersion : public System::IEquatable<SharedPtr<SortVersion>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Equals](./equals/)(SharedPtr\<SortVersion\>) override | Kontrollerar om den aktuella [SortVersion](./)-instansen är lika med ett specificerat [SortVersion](./)-objekt. |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Kontrollerar om den aktuella [SortVersion](./)-instansen är lika med ett specificerat [SortVersion](./)-objekt. |
| [get_FullVersion](./get_fullversion/)() | Hämtar fullständigt versionsnummer. |
| [get_SortId](./get_sortid/)() | Hämtar unik identifierare för detta objekt. |
| [GetHashCode](./gethashcode/)() const override | Hämtar hashkod för det aktuella objektet. |
| [operator!=](./operator!=/)(const SortVersion\&) | Kontrollerar om den aktuella [SortVersion](./)-instansen inte är lika med ett specificerat [SortVersion](./)-objekt. |
| [operator=](./operator=/)(const SortVersion\&) |  |
| [operator==](./operator==/)(const SortVersion\&) | Kontrollerar om den aktuella [SortVersion](./)-instansen är lika med ett specificerat [SortVersion](./)-objekt. |
| [SortVersion](./sortversion/)(int, const Guid\&) | RTTI-information. |
| [SortVersion](./sortversion/)(const SortVersion\&) |  |
## Se även

* Class [IEquatable](../../system/iequatable/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
