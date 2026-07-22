---
title: "System::Nullable::operator+ metod"
linktitle: "operator+"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Nullable::operator+ metod. Summerar nullable‑värden i C++."
type: docs
weight: 1200
url: /sv/cpp/system/nullable/operator+/
---
## Nullable::operator+(const Nullable\<T1\>\&) const method


Adderar nullable‑värden.

```cpp
template<typename T1> System::Nullable<decltype(get_Value()+other.get_Value())> System::Nullable<T>::operator+(const Nullable<T1> &other) const
```


| Parameter | Beskrivning |
| --- | --- |
| T1 | Typ av höger operand. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| annat | const Nullable\<T1\>\& | värde att lägga till. |

### ReturnValue

Summeringsresultat.

## Se även

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator+(const T1\&) const method


Adderar nullable‑ och icke‑nullable‑värden.

```cpp
template<typename T1,typename> Nullable<decltype(get_Value()+other)> System::Nullable<T>::operator+(const T1 &other) const
```


| Parameter | Beskrivning |
| --- | --- |
| T1 | Typ av höger operand. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| annat | const T1\& | värde att lägga till. |

### ReturnValue

Summeringsresultat.

## Se även

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator+(std::nullptr_t) const method


Returnerar en standardkonstruktad instans av klassen Nullable<T>.

```cpp
Nullable<T> System::Nullable<T>::operator+(std::nullptr_t) const
```

## Se även

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
