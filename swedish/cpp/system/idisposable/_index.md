---
title: "System::IDisposable class"
linktitle: "IDisposable"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IDisposable class. Definierar en metod som frigör resurser som ägs av det aktuella objektet. Objekt av denna klass bör endast allokeras med funktionen System::MakeObject(). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid in denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 3700
url: /sv/cpp/system/idisposable/
---
## IDisposable class


Definierar en metod som frigör resurser som ägs av det aktuella objektet. Objekt av den här klassen bör endast allokeras med hjälp av funktionen [System::MakeObject()](../makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att resultera i körfel och/eller assertion-fel. Omslut alltid denna klass i en [System::SmartPtr](../smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class IDisposable : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Dispose](./dispose/)() | Gör ingenting. |
## Se även

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
