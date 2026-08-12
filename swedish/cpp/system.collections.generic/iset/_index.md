---
title: "System::Collections::Generic::ISet-klass"
linktitle: "ISet"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::ISet-klass. Gränssnitt för en samling som innehåller en mängd unika element. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 2700
url: /sv/cpp/system.collections.generic/iset/
---
## ISet class


Gränssnitt för en samling som innehåller en mängd unika element. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
template<typename T>class ISet : public System::Collections::Generic::ICollection<T>
```


| Parameter | Beskrivning |
| --- | --- |
| T | Elementtyp. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [ExceptWith](./exceptwith/)(IEnumerablePtr) | Tar bort en grupp av element. |
| virtual [IntersectWith](./intersectwith/)(IEnumerablePtr) | Tar bort element som inte finns i en annan behållare. |
| virtual [IsProperSubsetOf](./ispropersubsetof/)(IEnumerablePtr) | Kontrollerar om den aktuella mängden är en strikt delmängd av en annan behållare. |
| virtual [IsProperSupersetOf](./ispropersupersetof/)(IEnumerablePtr) | Kontrollerar om den aktuella mängden är en strikt övermängd av en annan behållare. |
| virtual [IsSubsetOf](./issubsetof/)(IEnumerablePtr) | Kontrollerar om den aktuella mängden är en delmängd av en annan behållare. |
| virtual [IsSupersetOf](./issupersetof/)(IEnumerablePtr) | Kontrollerar om den aktuella mängden är en övermängd av en annan behållare. |
| virtual [Overlaps](./overlaps/)(IEnumerablePtr) | Kontrollerar om mängden överlappar med en annan behållare. |
| virtual [SetEquals](./setequals/)(IEnumerablePtr) | Kontrollerar om mängden och behållaren innehåller samma element. |
| virtual [SymmetricExceptWith](./symmetricexceptwith/)(IEnumerablePtr) | Beräknar symmetrisk undantag av två behållare. Tar bort alla element som finns i båda behållarna, men lägger samtidigt till alla element som finns i **other**, men inte i den aktuella mängden. |
| virtual [UnionWith](./unionwith/)(IEnumerablePtr) | Lägger till element från den angivna samlingen som ännu inte finns i den aktuella mängden. |
| virtual [~ISet](./~iset/)() | Destruktor. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [IEnumerablePtr](./ienumerableptr/) | RTTI-information. |

## Se även

* Class [ICollection](../icollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
