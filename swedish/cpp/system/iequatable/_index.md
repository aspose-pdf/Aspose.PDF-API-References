---
title: "System::IEquatable-klass"
linktitle: "IEquatable"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IEquatable-klass. Definierar en metod som bestämmer likheten mellan två objekt. Objekt av denna klass bör endast allokeras med funktionen System::MakeObject(). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 3800
url: /sv/cpp/system/iequatable/
---
## IEquatable class


Definierar en metod som bestämmer likheten mellan två objekt. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
template<typename T>class IEquatable : public virtual System::Object
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typen av de jämförda objekten |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Equals](./equals/)(T) | Bestämmer om de aktuella och angivna objekten är lika. |

## Se även

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
