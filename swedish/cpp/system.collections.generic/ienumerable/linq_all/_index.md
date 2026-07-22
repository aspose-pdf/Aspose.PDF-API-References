---
title: "System::Collections::Generic::IEnumerable::LINQ_All metod"
linktitle: "LINQ_All"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::IEnumerable::LINQ_All metod. Avgör om alla element i en sekvens uppfyller ett villkor i C++."
type: docs
weight: 700
url: /sv/cpp/system.collections.generic/ienumerable/linq_all/
---
## IEnumerable::LINQ_All method


Bestämmer om alla element i en sekvens uppfyller ett villkor.

```cpp
bool System::Collections::Generic::IEnumerable<T>::LINQ_All(std::function<bool(T)> predicate)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| predikat | std::function\<bool(T)> | En funktion för att testa varje element mot ett villkor. |

### ReturnValue

Sant om varje element i källsekvensen klarar testet i det angivna predikatet, eller om sekvensen är tom; annars falskt.

## Se även

* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
