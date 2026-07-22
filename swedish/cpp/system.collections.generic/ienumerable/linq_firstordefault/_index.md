---
title: "System::Collections::Generic::IEnumerable::LINQ_FirstOrDefault metod"
linktitle: "LINQ_FirstOrDefault"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::IEnumerable::LINQ_FirstOrDefault metod. Returnerar det första elementet i en sekvens, eller ett standardvärde om sekvensen är tom i C++."
type: docs
weight: 1700
url: /sv/cpp/system.collections.generic/ienumerable/linq_firstordefault/
---
## IEnumerable::LINQ_FirstOrDefault() method


Returnerar det första elementet i en sekvens, eller ett standardvärde om sekvensen är tom.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault()
```


### ReturnValue

Första elementet i sekvensen eller standardkonstrukt värde om sekvensen är tom.

## Se även

* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_FirstOrDefault(std::function\<bool(T)>) method


Returnerar det första elementet i sekvensen som uppfyller ett villkor eller ett standardvärde om inget sådant element hittas.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault(std::function<bool(T)> predicate)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| predikat | std::function\<bool(T)> | En funktion för att testa varje element mot ett villkor. |

### ReturnValue

default(T) om källan är tom eller om inget element klarar testet som specificeras av predikatet; annars det första elementet i källan som klarar testet som specificeras av predikatet.

## Se även

* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
