---
title: "System::Collections::Generic::BaseEnumerator-klass"
linktitle: "BaseEnumerator"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::BaseEnumerator-klass. Enumeratordefinition för att omsluta STL-stilade typer för C#-stilad användning. Gör inga påståenden om behållarens struktur förutom att en sekventiell iterator finns. Använder funktionerna begin() och end(). Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 600
url: /sv/cpp/system.collections.generic/baseenumerator/
---
## BaseEnumerator class


[Enumerator](../baseset/) definition to wrap STL-styled types for C#-styled usage. Makes no assertions on container structure except for existance of sequental iterator. Uses begin() and end() functions. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename Container,typename Element>class BaseEnumerator : public System::Collections::Generic::IEnumerator<Element>
```


| Parameter | Beskrivning |
| --- | --- |
| Behållare | STL-stilad behållartyp. |
| Element | Elementtyp. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [BaseEnumerator](./baseenumerator/)(const Object::ptr\&, Container\&) | Initierar iterator. |
| [IsValid](./isvalid/)() const | Kontrollerar om [MoveNext()](./movenext/) anropades och slutet inte nåddes. |
| [MoveNext](./movenext/)() override | Enumerator-stil inkrement. |
| [Reset](./reset/)() override | Återställer enumerator för att möjliggöra återupprepning av element. |

## Se även

* Class [IEnumerator](../ienumerator/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
