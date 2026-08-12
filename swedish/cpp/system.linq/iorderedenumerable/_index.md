---
title: "System::Linq::IOrderedEnumerable-klass"
linktitle: "IOrderedEnumerable"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Linq::IOrderedEnumerable-klass. Representerar en sorterad sekvens i C++."
type: docs
weight: 300
url: /sv/cpp/system.linq/iorderedenumerable/
---
## IOrderedEnumerable class


Representerar en sorterad sekvens.

```cpp
template<typename T>class IOrderedEnumerable : public System::Collections::Generic::IEnumerable<T>
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typen av elementen i sekvensen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [GetEnumerator](./getenumerator/)() override | Hämtar enumerator. |
| [IOrderedEnumerable](./iorderedenumerable/)(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T\>\>\&, const Comparator\&) |  |
| [LINQ_ThenBy](./linq_thenby/)(const Func\<T, Key\>\&) | Utför en efterföljande sortering av elementen i en sekvens i stigande ordning enligt en nyckel. |
| [LINQ_ThenBy](./linq_thenby/)(const Func\<Source, Key\>\&) |  |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Comparator](./comparator/) | RTTI-information. |

## Se även

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Linq](../)
* Library [Aspose.PDF for C++](../../)
