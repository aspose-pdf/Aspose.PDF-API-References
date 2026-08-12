---
title: "System::Nullable::operator= metod"
linktitle: "operator="
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Nullable::operator= metod. Ersätter objektets för närvarande representerade värde med det angivna i C++."
type: docs
weight: 1800
url: /sv/cpp/system/nullable/operator=/
---
## Nullable::operator=(const Nullable\<T1\>\&) method


Ersätter objektets för närvarande representerade värde med det angivna.

```cpp
template<typename T1> Nullable<T> & System::Nullable<T>::operator=(const Nullable<T1> &x)
```


| Parameter | Beskrivning |
| --- | --- |
| Den | typ av det nya värdet som ska representeras av det aktuella objektet |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | const Nullable\<T1\>\& | Det nya värdet som ska representeras av det aktuella objektet |

### ReturnValue

En referens till sig själv

## Se även

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator=(const T1\&) method


Ersätter objektets för närvarande representerade värde med det angivna.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value &&!std::is_null_pointer<T1>::value, Nullable<T> &>::type System::Nullable<T>::operator=(const T1 &x)
```


| Parameter | Beskrivning |
| --- | --- |
| Den | typ av det nya värdet som ska representeras av det aktuella objektet |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | const T1\& | Det nya värdet som ska representeras av det aktuella objektet |

### ReturnValue

En referens till sig själv

## Se även

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator=(std::nullptr_t) method


Tilldelar ett null till det aktuella objektet.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator=(std::nullptr_t)
```


### ReturnValue

Ett [Nullable](../) objekt som representerar null-värde.

## Se även

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
