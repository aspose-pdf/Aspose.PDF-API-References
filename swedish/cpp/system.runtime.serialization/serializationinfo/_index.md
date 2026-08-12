---
title: "System::Runtime::Serialization::SerializationInfo klass"
linktitle: "SerializationInfo"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Runtime::Serialization::SerializationInfo klass. Innehåller en uppsättning namngivna fält som representerar ett serialiserat objekt. Inte implementerad. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 400
url: /sv/cpp/system.runtime.serialization/serializationinfo/
---
## SerializationInfo class


Innehåller en uppsättning namngivna fält som representerar ett serialiserat objekt. Inte implementerad. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class SerializationInfo : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AddValue](./addvalue/)(const System::String\&, float) | Lägger in ett float‑värde. Inte implementerad. |
| [AddValue](./addvalue/)(const System::String\&, short) | Lägger in ett short‑värde. Inte implementerad. |
| [AddValue](./addvalue/)(const System::String\&, bool) | Lägger in ett boolean‑värde. Inte implementerad. |
| [AddValue](./addvalue/)(const System::String\&, const System::SharedPtr\<System::Object\>\&) | Lägger in ett objektvärde. Inte implementerad. |
| [AddValue](./addvalue/)(const System::String\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) | Lägger in ett objektvärde med specificerad typ. Inte implementerad. |
| [GetValue](./getvalue/)(const System::String\&, const System::TypeInfo\&) | Hämtar ett värde från [SerializationInfo](./)-lagret. Inte implementerad. |
| [SerializationInfo](./serializationinfo/)(const System::TypeInfo\&, const System::SharedPtr\<IFormatterConverter\>\&) | RTTI-information. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Runtime::Serialization](../)
* Library [Aspose.PDF for C++](../../)
