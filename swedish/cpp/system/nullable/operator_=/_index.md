---
title: "System::Nullable::operator<= metod"
linktitle: "operator<="
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Nullable::operator<= metod. Avgör om värdet som representeras av det aktuella objektet är mindre än eller lika med värdet som representeras av det angivna Nullable-objektet genom att tillämpa operator<=() på dessa värden i C++."
type: docs
weight: 1700
url: /sv/cpp/system/nullable/operator_=/
---
## Nullable::operator<=(const Nullable\<T1\>\&) const method


Avgör om värdet som representeras av det aktuella objektet är mindre än eller lika med värdet som representeras av det angivna [Nullable](../) objektet genom att tillämpa [operator<=()](./) på dessa värden.

```cpp
template<typename T1> bool System::Nullable<T>::operator<=(const Nullable<T1> &other) const
```


| Parameter | Beskrivning |
| --- | --- |
| T1 | Den underliggande typen av [Nullable](../) objektet att jämföra med |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | const Nullable\<T1\>\& | En konstant referens till [Nullable](../) objektet att jämföra med |

### ReturnValue

Sant om värdet som representeras av det aktuella objektet är mindre än eller lika med värdet som representeras av det angivna [Nullable](../) objektet, annars - falskt

## Se även

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator<=(const T1\&) const method


Avgör om värdet som representeras av det aktuella objektet är mindre än eller lika med det angivna värdet genom att tillämpa [operator<=()](./) på dessa värden.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<=(const T1 &other) const
```


| Parameter | Beskrivning |
| --- | --- |
| T1 | Typen av värdet att jämföra med |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| annat | const T1\& | En konstant referens till värdet att jämföra med |

### ReturnValue

Sant om värdet som representeras av det aktuella objektet är mindre än eller lika med det angivna värdet, annars - falskt

## Se även

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator<=(std::nullptr_t) const method


Returnerar alltid falskt.

```cpp
bool System::Nullable<T>::operator<=(std::nullptr_t) const
```

## Se även

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
---
title: System::Nullable::operator>= metod
länktitel: operator>=
second_title: Aspose.PDF för C++ API-referens
description: 'System::Nullable::operator>= metod. Avgör om värdet som representeras av det aktuella objektet är större än eller lika med värdet som representeras av det angivna Nullable-objektet genom att tillämpa operator>=() på dessa värden i C++.'
type: dokument
weight: 2100
url: /cpp/system/nullable/operator_=/
---
## Nullable::operator>=(const Nullable\<T1\>\&) const method


Bestämmer om värdet som representeras av det aktuella objektet är större än eller lika med värdet som representeras av det angivna [Nullable](../)-objektet genom att tillämpa [operator>=()](./) på dessa värden.

```cpp
template<typename T1> bool System::Nullable<T>::operator>=(const Nullable<T1> &other) const
```


| Parameter | Beskrivning |
| --- | --- |
| T1 | Den underliggande typen av [Nullable](../) objektet att jämföra med |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | const Nullable\<T1\>\& | En konstant referens till [Nullable](../) objektet att jämföra med |

### ReturnValue

Sant om värdet som representeras av det aktuella objektet är större än eller lika med värdet som representeras av det angivna [Nullable](../)-objektet, annars - falskt

## Se även

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator>=(const T1\&) const method


Bestämmer om värdet som representeras av det aktuella objektet är större än eller lika med värdet som representeras av det angivna objektet genom att tillämpa [operator>=()](./) på dessa värden.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>=(const T1 &other) const
```


| Parameter | Beskrivning |
| --- | --- |
| T1 | Den underliggande typen av värdet att jämföra värdet som representeras av det aktuella objektet med |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| annat | const T1\& | En konstant referens till ett objekt att jämföra det aktuella objektet med |

### ReturnValue

Sant om värdet som representeras av det aktuella objektet är större än eller lika med värdet som representeras av det angivna objektet, annars - falskt

## Se även

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator>=(std::nullptr_t) const method


Returnerar alltid falskt.

```cpp
bool System::Nullable<T>::operator>=(std::nullptr_t) const
```


### ReturnValue

Alltid - falskt

## Se även

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
---
title: System::Nullable::operator|= metod
linktitle: operator|=
second_title: Aspose.PDF för C++ API-referens
description: 'System::Nullable::operator|= metod. Tillämpa operator|=() på värdet som representeras av det aktuella objektet med det angivna värdet som ett högersidigt argument i C++.'
type: dokument
weight: 2200
url: /cpp/system/nullable/operator_=/
---
## Nullable::operator|= method


Tillämpa [operator|=()](./) på värdet som representeras av det aktuella objektet med det angivna värdet som ett högersidigt argument.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator|=(bool other)
```


| Parameter | Beskrivning |
| --- | --- |
| T1 | Mallparametern för att få SFINAE att fungera. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| annat | bool | Ett booleskt värde som används som ett högersidigt värde för [operator | =()](./) som tillämpas på värdet som representeras av det aktuella objektet. |

### ReturnValue

En referens till sig själv.

## Se även

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
