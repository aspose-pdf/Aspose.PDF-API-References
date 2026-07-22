---
title: "System::IFormatProvider-klass"
linktitle: "IFormatProvider"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IFormatProvider-klass. Definierar en metod som tillhandahåller formateringsinformation. Objekt av denna klass bör endast allokeras med hjälp av System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 3900
url: /sv/cpp/system/iformatprovider/
---
## IFormatProvider class


Definierar en metod som tillhandahåller formateringsinformation. Objekt av denna klass bör endast allokeras med hjälp av [System::MakeObject()](../makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class IFormatProvider : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [GetFormat](./getformat/)(const TypeInfo\&) | Returnerar ett objekt som tillhandahåller formateringstjänster för den angivna typen. |
## Se även

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
