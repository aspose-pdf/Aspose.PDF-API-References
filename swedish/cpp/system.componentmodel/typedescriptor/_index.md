---
title: "System::ComponentModel::TypeDescriptor class"
linktitle: "TypeDescriptor"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::ComponentModel::TypeDescriptor class. Dummy‑klass för kod som använder TypeDescriptor så att den kan kompileras efter översättning. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller assert‑fel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 1500
url: /sv/cpp/system.componentmodel/typedescriptor/
---
## TypeDescriptor class


Dummy‑klass för kod som använder TypeDescriptor så att den kan kompileras efter översättning. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller assert‑fel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class TypeDescriptor : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [GetConverter](./getconverter/)(const TypeInfo\&) | RTTI-information. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.PDF for C++](../../)
