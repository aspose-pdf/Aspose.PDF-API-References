---
title: "System::Collections::Generic::IList class"
linktitle: "IList"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::IList-klass. Gränssnitt för en indexerad behållare av element. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 2600
url: /sv/cpp/system.collections.generic/ilist/
---
## IList class


Gränssnitt för en indexerad behållare av element. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
template<typename T>class IList : public System::Collections::Generic::ICollection<T>
```


| Parameter | Beskrivning |
| --- | --- |
| T | Elementtyp. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_IsFixedSize](./get_isfixedsize/)() | Kontrollerar om samlingen har fast storlek. |
| virtual [idx_get](./idx_get/)(int) const | Hämtar elementet på angivet index. |
| virtual [idx_set](./idx_set/)(int, T) | Sätter elementet på angivet index. |
| virtual [IndexOf](./indexof/)(const T\&) const | Hämtar index för första förekomsten av objektet i behållaren. |
| virtual [Insert](./insert/)(int, const T\&) | Infogar element på angiven position och förskjuter övriga element. |
| virtual [RemoveAt](./removeat/)(int) | Tar bort elementet på angivet index. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [BaseType](./basetype/) | RTTI-information. |
| [ThisType](./thistype/) | Denna typ. |
| [ValueType](./valuetype/) | Värdetyp. |

## Se även

* Class [ICollection](../icollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
