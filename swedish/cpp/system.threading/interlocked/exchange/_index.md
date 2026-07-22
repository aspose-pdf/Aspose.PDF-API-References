---
title: "System::Threading::Interlocked::Exchange-metod"
linktitle: "Exchange"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::Interlocked::Exchange-metod. Byter värde på variabeln: lagrar det nya värdet och returnerar det värde variabeln hade omedelbart innan lagringen i C++."
type: docs
weight: 400
url: /sv/cpp/system.threading/interlocked/exchange/
---
## Interlocked::Exchange(T\&, T) method


Byter värde på variabel: lagrar det nya värdet och returnerar det värde variabeln hade omedelbart innan lagringen.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Variabeltyp. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| location1 | T\& | Variabelreferens för att ändra. |
| värde | T | Värde att lagra. |

### ReturnValue

Variabelns värde precis innan den ändrades.

## Se även

* Class [Interlocked](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Interlocked::Exchange(T\&, T) method


Byter värde på variabel: lagrar det nya värdet och returnerar det värde variabeln hade omedelbart innan lagringen. Inte implementerad.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Variabeltyp. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| location1 | T\& | Variabelreferens för att ändra. |
| värde | T | Värde att lagra. |

### ReturnValue

Variabelns värde precis innan den ändrades.

## Se även

* Class [Interlocked](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
