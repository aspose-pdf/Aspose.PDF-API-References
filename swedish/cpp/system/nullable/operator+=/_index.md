---
title: "System::Nullable::operator+= metod"
linktitle: "operator+="
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Nullable::operator+= metod. Tillämpa operator+=() på värdet som representeras av det aktuella objektet med värdet som representeras av det angivna Nullable-objektet som ett högersidigt argument i C++."
type: docs
weight: 1300
url: /sv/cpp/system/nullable/operator+=/
---
## Nullable::operator+=(const Nullable\<T1\>\&) method


Tillämpa [operator+=()](./) på värdet som representeras av det aktuella objektet med värdet som representeras av det angivna [Nullable](../)-objektet som ett högersidigt argument.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator+=(const Nullable<T1> &other)
```


| Parameter | Beskrivning |
| --- | --- |
| T1 | Den underliggande typen av ett [Nullable](../)-objekt vars värde som representeras av används som ett högersidigt argument för [operator+=()](./) |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | const Nullable\<T1\>\& | En konstant referens till [Nullable](../)-objekt vars värde som representeras av används som ett högersidigt argument för [operator+=()](./) som tillämpas på värdet som representeras av det aktuella objektet. |

### ReturnValue

En referens till sig själv

## Se även

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator+=(const T1\&) method


Tillämpa [operator+=()](./) på värdet som representeras av det aktuella objektet med det angivna värdet som ett högersidigt argument.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator+=(const T1 &other)
```


| Parameter | Beskrivning |
| --- | --- |
| T1 | Typen av värdet som används som ett högersidigt värde för [operator+=()](./) |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | const T1\& | En konstant referens till värdet som används som ett högersidigt värde för [operator+=()](./) som tillämpas på värdet som representeras av det aktuella objektet. |

### ReturnValue

En referens till sig själv

## Se även

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator+=(std::nullptr_t) method


Återställer det aktuella objektet så att det representerar ett null‑värde.

```cpp
Nullable<T> System::Nullable<T>::operator+=(std::nullptr_t)
```


### ReturnValue

En kopia av objektet

## Se även

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
