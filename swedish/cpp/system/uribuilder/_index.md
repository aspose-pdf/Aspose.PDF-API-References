---
title: "System::UriBuilder-klass"
linktitle: "UriBuilder"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::UriBuilder-klass. Tillhandahåller metoder för att konstruera och modifiera universella resurstillståndsidentifierare (URI:er). Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 7100
url: /sv/cpp/system/uribuilder/
---
## UriBuilder class


Tillhandahåller metoder för att konstruera och modifiera universella resurstillståndsidentifierare (URI:er). Objekt av denna klass bör endast allokeras med [System::MakeObject()](../makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class UriBuilder : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Scheme](./get_scheme/)() const | Returnerar schemat för den URI som skapats av det aktuella objektet. |
| [get_Uri](./get_uri/)() const | Returnerar [Uri](../uri/)-objektet som skapats av det aktuella objektet. |
| [set_Port](./set_port/)(int) | Ställer in portnumret för URI:n. |
| [set_Scheme](./set_scheme/)(const String\&) | Ställer in schemat för den URI som skapats av det aktuella objektet till det angivna värdet. |
| [ToString](./tostring/)() const override | Returnerar strängrepresentationen av den URI som skapats av det aktuella objektet. |
| [UriBuilder](./uribuilder/)(const String\&) | Skapar ett [UriBuilder](./)-objekt som representerar den angivna URI:n. |
| [UriBuilder](./uribuilder/)(const SharedPtr\<Uri\>\&) | Skapar ett [UriBuilder](./)-objekt som representerar den angivna URI:n. |
## Se även

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
