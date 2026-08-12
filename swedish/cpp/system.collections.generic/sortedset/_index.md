---
title: "System::Collections::Generic::SortedSet-klass"
linktitle: "SortedSet"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::SortedSet-klass. Framåtriktad deklaration av SortedSet-klass i C++."
type: docs
weight: 4400
url: /sv/cpp/system.collections.generic/sortedset/
---
## SortedSet class


Framåtriktad deklaration av klassen [SortedSet](./).

```cpp
template<typename T>class SortedSet : public System::Collections::Generic::BaseSet<T, std::set<T, ComparerAdapter<T>, System::Details::CollectionHelpers::ContainerPointerMode<T>::allocator_type>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Max](./get_max/)() const | Hämtar det maximala värdet i [SortedSet](./). |
| [SortedSet](./sortedset/)() | RTTI-information. |
| [SortedSet](./sortedset/)(int) | Skapar en tom mängd med angiven kapacitet. |
| [SortedSet](./sortedset/)(const SharedPtr\<IComparer\<T\>\>\&) | Skapar en tom mängd som använder den angivna likhetsjämförelsen. |
| [SortedSet](./sortedset/)(const SharedPtr\<IEnumerable\<T\>\>\&) | Skapar [SortedSet](./) baserat på enumererbara värden. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [BaseType](./basetype/) | Vas-typ. |
| [ThisPtr](./thisptr/) | Pekartyp. |
| [ThisType](./thistype/) | Självtyp. |
## Anmärkningar


Implementering av en mängd ordnade objekt. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [BaseSet](../baseset/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
