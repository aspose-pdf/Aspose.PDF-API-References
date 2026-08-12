---
title: "System::Collections::Generic::SimpleEnumerator klass"
linktitle: "SimpleEnumerator"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::SimpleEnumerator-klass. Iteratorklass för enkla behållare som håller element direkt med hjälp av rbegin() och rend() funktioner. Objekt av denna klass bör endast allokeras med System::MakeObject() funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 3900
url: /sv/cpp/system.collections.generic/simpleenumerator/
---
## SimpleEnumerator class


Iteratorklass för enkla behållare som håller element direkt med hjälp av rbegin() och rend() funktioner. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
template<typename Container,typename Element>class SimpleEnumerator : public System::Collections::Generic::BaseEnumerator<Container, typename Container::value_type>
```


| Parameter | Beskrivning |
| --- | --- |
| Behållare | Behållartyp att iterera igenom. |
| Element | Elementtyp. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CloneIterator](./cloneiterator/)() const override | Klonar aktuell iterator. |
| [get_Current](./get_current/)() const override | Hämtar det 'aktuella' elementet. |
| [SimpleEnumerator](./simpleenumerator/)(Object::ptr, Container\&) | Skapar enkel iterator. |

## Se även

* Class [BaseEnumerator](../baseenumerator/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
