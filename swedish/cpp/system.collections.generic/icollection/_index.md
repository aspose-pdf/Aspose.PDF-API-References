---
title: "System::Collections::Generic::ICollection-klass"
linktitle: "ICollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::ICollection-klass. Gränssnitt för en samling av element. Objekt av denna klass bör endast allokeras med System::MakeObject() funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 1900
url: /sv/cpp/system.collections.generic/icollection/
---
## ICollection class


Gränssnitt för en samling av element. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
template<typename T>class ICollection : public virtual System::Collections::Generic::IEnumerable<T>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Add](./add/)(const T\&) | Lägger till ett element i samlingen. |
| virtual [Clear](./clear/)() | Tar bort alla element från samlingen. |
| virtual [Contains](./contains/)(const T\&) const | Kontrollerar om ett element finns i samlingen. |
| virtual [CopyTo](./copyto/)(System::ArrayPtr\<T\>, int) | Kopierar alla samlingselement till befintliga array‑element. |
| virtual [get_Count](./get_count/)() const | Hämtar antalet element i samlingen. |
| virtual [get_IsReadOnly](./get_isreadonly/)() const | Kontrollerar om samlingen är skrivskyddad. |
| [get_SyncRoot](./get_syncroot/)() const | Hämtar objektet som samlingen synkroniseras genom. |
| [ICollection](./icollection/)() | Standardkonstruktor. |
| [ICollection](./icollection/)(const ICollection\&) | Kopieringskonstruktor. |
| [ICollection](./icollection/)(ICollection\&&) | Flyttkonstruktor. |
| [operator=](./operator=/)(ICollection\&&) | Flyttilldelningsoperator. |
| [operator=](./operator=/)(const ICollection\&) | Flyttilldelningsoperator. |
| virtual [Remove](./remove/)(const T\&) | Tar bort ett element från samlingen. |
| virtual [~ICollection](./~icollection/)() | Destruktor. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [ThisType](./thistype/) | Namn på samlingstyp. |
| [ValueType](./valuetype/) | RTTI-information. |

## Se även

* Class [IEnumerable](../ienumerable/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
