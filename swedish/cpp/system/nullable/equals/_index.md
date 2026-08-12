---
title: "System::Nullable::Equals metod"
linktitle: "Equals"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Nullable::Equals metod. Bestämmer om värdet som det aktuella objektet representerar är lika med värdet som det specificerade Nullable‑objektet representerar i C++."
type: docs
weight: 200
url: /sv/cpp/system/nullable/equals/
---
## Nullable::Equals method


Bestämmer om värdet som representeras av det aktuella objektet är lika med värdet som representeras av det angivna [Nullable](../)-objektet.

```cpp
template<typename T1> std::enable_if<IsNullable<T1>::value, bool>::type System::Nullable<T>::Equals(const T1 &other) const
```


| Parameter | Beskrivning |
| --- | --- |
| T1 | Den underliggande typen av [Nullable](../) objektet att jämföra med |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | const T1\& | En konstant referens till [Nullable](../) objektet att jämföra med |

### ReturnValue

Sant om värdet som representeras av det aktuella objektet är lika med värdet som representeras av det angivna [Nullable](../)-objektet, annars - falskt

## Se även

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
