---
title: "System::Nullable::operator!= metod"
linktitle: "operator!="
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Nullable::operator!= metod. Avgör om värdet som representeras av det aktuella objektet inte är lika med värdet som representeras av det angivna Nullable-objektet i C++."
type: docs
weight: 1000
url: /sv/cpp/system/nullable/operator!=/
---
## Nullable::operator!=(const Nullable\<T1\>\&) const method


Avgör om värdet som representeras av det aktuella objektet inte är lika med värdet som representeras av det angivna [Nullable](../) objektet.

```cpp
template<typename T1> bool System::Nullable<T>::operator!=(const Nullable<T1> &other) const
```


| Parameter | Beskrivning |
| --- | --- |
| T1 | Den underliggande typen av [Nullable](../) objektet att jämföra med |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | const Nullable\<T1\>\& | En konstant referens till [Nullable](../) objektet att jämföra med |

### ReturnValue

Sant om värdet som representeras av det aktuella objektet inte är lika med värdet som representeras av det angivna [Nullable](../) objektet, annars - falskt

## Se även

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator!=(const T1\&) const method


Avgör om värdet som representeras av det aktuella objektet inte är lika med det angivna värdet.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator!=(const T1 &other) const
```


| Parameter | Beskrivning |
| --- | --- |
| T1 | Typen av värdet att jämföra med |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| annat | const T1\& | En konstant referens till värdet att jämföra med |

### ReturnValue

Sant om värdet som representeras av det aktuella objektet inte är lika med det angivna värdet, annars - falskt

## Se även

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator!=(std::nullptr_t) const method


Avgör om värdet som representeras av det aktuella objektet inte är null.

```cpp
bool System::Nullable<T>::operator!=(std::nullptr_t) const
```


### ReturnValue

Sant om värdet som representeras av det aktuella objektet inte är null, annars - falskt

## Se även

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
