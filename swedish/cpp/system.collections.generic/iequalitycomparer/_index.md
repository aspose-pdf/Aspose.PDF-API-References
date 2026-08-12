---
title: "System::Collections::Generic::IEqualityComparer klass"
linktitle: "IEqualityComparer"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::IEqualityComparer klass. Gränssnitt som tillhandahåller möjlighet att jämföra två objekt för likhet. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 2400
url: /sv/cpp/system.collections.generic/iequalitycomparer/
---
## IEqualityComparer class


Gränssnitt som tillhandahåller möjlighet att jämföra två objekt för likhet. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
template<typename T>class IEqualityComparer : public virtual System::Object
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typ som jämförs. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Equals](./equals/)(T, T) const | RTTI-information. |
| virtual [GetHashCode](./gethashcode/)(T) const | Hämtar hash‑kod för ett objekt. |

## Se även

* Class [Object](../../system/object/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
