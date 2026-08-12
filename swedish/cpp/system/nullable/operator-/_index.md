---
title: "System::Nullable::operator- metod"
linktitle: "operator-"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Nullable::operator- metod. Subtraherar nullable‑värden i C++."
type: docs
weight: 1400
url: /sv/cpp/system/nullable/operator-/
---
## Nullable::operator-(const Nullable\<T1\>\&) const method


Subtraherar nullable‑värden.

```cpp
template<typename T1> System::Nullable<decltype(get_Value() - other.get_Value())> System::Nullable<T>::operator-(const Nullable<T1> &other) const
```


| Parameter | Beskrivning |
| --- | --- |
| T1 | Typ av höger operand. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| annat | const Nullable\<T1\>\& | värde att subtrahera. |

### ReturnValue

Subtraktionsresultat.

## Se även

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator-(const T1\&) const method


Subtraherar nullable‑ och icke‑nullable‑värden.

```cpp
template<typename T1,typename> Nullable<decltype(get_Value() - other)> System::Nullable<T>::operator-(const T1 &other) const
```


| Parameter | Beskrivning |
| --- | --- |
| T1 | Typ av höger operand. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| annat | const T1\& | värde att subtrahera. |

### ReturnValue

Subtraktionsresultat.

## Se även

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator-(T1) const method


Subtraherar nullable‑ och null‑pekande värden.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-(T1) const
```


| Parameter | Beskrivning |
| --- | --- |
| T1 | Höger operandtyp, bör vara nullptr_t. |

### ReturnValue

Tomt [Nullable](../)‑objekt.

## Se även

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
