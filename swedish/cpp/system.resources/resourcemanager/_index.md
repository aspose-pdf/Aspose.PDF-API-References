---
title: "System::Resources::ResourceManager‑klass"
linktitle: "ResourceManager"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Resources::ResourceManager‑klass. Tillhandahåller ett API för att hantera resurser. Inte implementerad. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 100
url: /sv/cpp/system.resources/resourcemanager/
---
## ResourceManager class


Tillhandahåller ett API för att hantera resurser. Inte implementerad. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class ResourceManager : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [GetObject__](./getobject__/)(String) | Hämtar objekt från resurs. Namnet är inte GetObject() för att hantera GetObjectA‑definieringsproblemet. |
| virtual [GetObject__](./getobject__/)(String, SharedPtr\<System::Globalization::CultureInfo\>) | Hämtar objekt från resurs. Namnet är inte GetObject() för att hantera GetObjectA‑definieringsproblemet. |
| virtual [GetString](./getstring/)(String) | Hämtar strängresurs. |
| virtual [GetString](./getstring/)(String, SharedPtr\<System::Globalization::CultureInfo\>) | Hämtar strängresurs. |
| [ResourceManager](./resourcemanager/)(const String\&, const SharedPtr\<Reflection::Assembly\>\&) | RTTI-information. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Resources](../)
* Library [Aspose.PDF for C++](../../)
