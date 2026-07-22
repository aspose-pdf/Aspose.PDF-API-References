---
title: "System::Collections::Generic::ReverseEnumerator-klass"
linktitle: "ReverseEnumerator"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::ReverseEnumerator-klass. Enumerator som itererar baklänges genom behållaren. Objekt av denna klass bör endast allokeras med funktionen System::MakeObject(). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 3800
url: /sv/cpp/system.collections.generic/reverseenumerator/
---
## ReverseEnumerator class


[Enumerator](../baseset/) that reverse-iterates through container. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename Container,typename Element>class ReverseEnumerator : public System::Collections::Generic::IEnumerator<typename Container::value_type>
```


| Parameter | Beskrivning |
| --- | --- |
| Behållare | Behållare att iterera igenom. |
| Element | Elementtyp. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Current](./get_current/)() const override | Hämtar det 'aktuella' elementet. |
| [IsValid](./isvalid/)() const | Kontrollerar om [MoveNext()](./movenext/) anropades och slutet inte nåddes. |
| [MoveNext](./movenext/)() override | Enumerator-stil inkrement. |
| [Reset](./reset/)() override | Återställer enumerator för att möjliggöra återupprepning av element. |
| [ReverseEnumerator](./reverseenumerator/)(const Object::ptr\&, Container\&) | Initierar iterator. |
| virtual [~ReverseEnumerator](./~reverseenumerator/)() | Destruktor. |

## Se även

* Class [IEnumerator](../ienumerator/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
