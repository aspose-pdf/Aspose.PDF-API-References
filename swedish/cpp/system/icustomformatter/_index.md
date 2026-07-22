---
title: "System::ICustomFormatter‑klass"
linktitle: "ICustomFormatter"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::ICustomFormatter‑klass. Definierar en metod som utför anpassad formatering av en strängrepresentation av ett värde som representeras av det angivna objektet. Objekt av den här klassen bör endast allokeras med hjälp av funktionen System::MakeObject(). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assertion-fel. Omslut alltid denna klass i en System::SmartPtr pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 3600
url: /sv/cpp/system/icustomformatter/
---
## ICustomFormatter class


Definierar en metod som utför anpassad formatering av en strängrepresentation av ett värde som representeras av det angivna objektet. Objekt av den här klassen bör endast allokeras med hjälp av funktionen [System::MakeObject()](../makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assertion-fel. Omslut alltid denna klass i en [System::SmartPtr](../smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class ICustomFormatter : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Format](./format/)(System::String, System::SharedPtr\<System::Object\>, System::SharedPtr\<System::IFormatProvider\>) | Returnerar en strängrepresentation av ett värde som representeras av det aktuella objektet med det angivna formatet. |
## Se även

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
