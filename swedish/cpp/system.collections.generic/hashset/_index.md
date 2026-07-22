---
title: "System::Collections::Generic::HashSet klass"
linktitle: "HashSet"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::HashSet klass. Framåtriktad deklaration av HashSet‑klassen i C++."
type: docs
weight: 1700
url: /sv/cpp/system.collections.generic/hashset/
---
## HashSet class


Framåtriktad deklaration av [HashSet](./) klass.

```cpp
template<typename T>class HashSet : public System::Collections::Generic::BaseSet<T, std::unordered_set<T, EqualityComparerHashAdapter<T>, EqualityComparerAdapter<T>, System::Details::CollectionHelpers::ContainerPointerMode<T>::allocator_type>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [HashSet](./hashset/)() | RTTI-information. |
| [HashSet](./hashset/)(int) | Skapar en tom mängd med angiven kapacitet. |
| [HashSet](./hashset/)(const SharedPtr\<IEqualityComparer\<T\>\>\&) | Skapar en tom mängd som använder den angivna likhetsjämförelsen. |
| [HashSet](./hashset/)(const SharedPtr\<IEnumerable\<T\>\>\&) | Skapar en hashset baserad på uppräkningsbara värden. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [BaseType](./basetype/) | Bastyp. |
| [ThisPtr](./thisptr/) | Pekartyp. |
| [ThisType](./thistype/) | Självtyp. |
## Anmärkningar


Mängdimplementation baserad på hashning. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [BaseSet](../baseset/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
