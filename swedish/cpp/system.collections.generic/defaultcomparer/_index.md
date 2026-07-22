---
title: "System::Collections::Generic::DefaultComparer klass"
linktitle: "DefaultComparer"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::DefaultComparer klass. Standardjämförelseklass. Använder operator < och operator == för att jämföra värden. Objekt av denna klass bör endast allokeras med funktionen System::MakeObject(). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 1000
url: /sv/cpp/system.collections.generic/defaultcomparer/
---
## DefaultComparer class


Standardjämförelseklass. Använder operator < och operator == för att jämföra värden. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
template<class T,typename>class DefaultComparer : public System::Collections::Generic::IComparer<T>
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typ som jämförs. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Compare](./compare/)(typename ThisType::args_type, typename ThisType::args_type) const override | RTTI-information. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [BaseType](./basetype/) | Implementerat gränssnitt. |
| [ThisType](./thistype/) | Aktuell typ. |

## Se även

* Class [IComparer](../icomparer/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
