---
title: "System::Attribute klass"
linktitle: "Attribute"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Attribute‑klass. En bas-klass för anpassade attribut. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körningsfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 500
url: /sv/cpp/system/attribute/
---
## Attribute class


En bas-klass för anpassade attribut. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körningsfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class Attribute : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [GetCustomAttribute](./getcustomattribute/)(const TypeInfo\&, const TypeInfo\&) | Returnerar ett anpassat attribut av en angiven typ som tillämpas på den angivna typen. |
| static [GetCustomAttributes](./getcustomattributes/)(const TypeInfo\&) | Returnerar alla anpassade attribut som tillämpas på den angivna typen. |
## Se även

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
