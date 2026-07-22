---
title: "System::IComparable-klass"
linktitle: "IComparable"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IComparable-klass. Definierar en metod som jämför två objekt. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 3400
url: /sv/cpp/system/icomparable/
---
## IComparable class


Definierar en metod som jämför två objekt. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
template<typename T>class IComparable : public virtual System::Object
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typen av de objekt som det aktuella objektet jämförs med |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [CompareTo](./compareto/)(T) | Jämför det aktuella objektet med det angivna objektet. |

## Se även

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
