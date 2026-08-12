---
title: "System::Collections::Generic::_KeyList klass"
linktitle: "_KeyList"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::_KeyList klass. Implementerar en lista över nycklar i en dictionary. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 200
url: /sv/cpp/system.collections.generic/_keylist/
---
## _KeyList class


Implementerar en lista över nycklar i en dictionary. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
template<typename Dict>class _KeyList : public System::Collections::Generic::_KeyCollection<Dict>
```


| Parameter | Beskrivning |
| --- | --- |
| Dict | [Dictionary](../dictionary/) typ. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [_KeyList](./_keylist/)(const typename Dict::Ptr\&) | Initierar en samling som refererar till den angivna dictionaryn. |
| [Contains](./contains/)(const TKey\&) const override | Kontrollerar om den angivna nyckeln finns i samlingen. |
| [idx_get](./idx_get/)(int) const override | Hämtar nyckeln på den angivna positionen. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [TKey](./tkey/) | Nyckeltyp. |

## Se även

* Class [_KeyCollection](../_keycollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
