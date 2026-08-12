---
title: "System::Collections::Generic::List::LastIndexOf metod"
linktitle: "LastIndexOf"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::List::LastIndexOf metod. Söker efter det angivna objektet och returnerar det nollbaserade indexet för den sista förekomsten i hela listan i C++."
type: docs
weight: 3400
url: /sv/cpp/system.collections.generic/list/lastindexof/
---
## List::LastIndexOf(const T\&) const method


Söker efter det angivna objektet och returnerar det nollbaserade indexet för den sista förekomsten i hela listan.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| objekt | const T\& | Objektet att hitta i listan |

### ReturnValue

Det nollbaserade indexet för den sista förekomsten av objektet i hela [List](../), om det hittas; annars -1.

## Se även

* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## List::LastIndexOf(const T\&, int32_t) const method


Söker efter det angivna objektet och returnerar det nollbaserade indexet för den sista förekomsten inom intervallet av element i [List](../) som sträcker sig från det första elementet till det angivna indexet.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| objekt | const T\& | Objektet att hitta i listan |
| index | int32_t | Det nollbaserade startindexet för den bakåtsökning. |

### ReturnValue

Det nollbaserade indexet för den sista förekomsten av objektet inom intervallet av element i [List](../) som sträcker sig från det första elementet till index, om det hittas; annars -1.

## Se även

* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## List::LastIndexOf(const T\&, int32_t, int32_t) const method


Söker efter det angivna objektet och returnerar det nollbaserade indexet för den sista förekomsten inom intervallet av element i [List](../) som innehåller det angivna antalet element och slutar vid det angivna indexet.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index, int32_t count) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | const T\& | Objektet att hitta i [List](../) |
| index | int32_t | Det nollbaserade startindexet för den bakåtsökning. |
| count | int32_t | Antalet element i sektionen som ska sökas. |

### ReturnValue

Det nollbaserade indexet för den sista förekomsten av objektet inom intervallet av element i [List](../) som innehåller count antal element och slutar vid index, om det hittas; annars -1.

## Se även

* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
