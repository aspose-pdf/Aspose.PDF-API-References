---
title: "System::Threading::Interlocked::CompareExchange-metod"
linktitle: "CompareExchange"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::Interlocked::CompareExchange-metod. Jämför-utbyter värdet på en variabel: kontrollerar om variabeln är lika med ett specifikt värde och lagrar det nya värdet endast om det lagrade värdet matchar det förväntade i C++."
type: docs
weight: 200
url: /sv/cpp/system.threading/interlocked/compareexchange/
---
## Interlocked::CompareExchange(int32_t\&, int32_t, int32_t, bool\&) method


Jämför-och-utbyter värde på variabel: kontrollerar om variabeln är lika med ett specifikt värde och lagrar det nya värdet endast om det lagrade värdet matchar det förväntade.

```cpp
static int32_t System::Threading::Interlocked::CompareExchange(int32_t &location1, int32_t value, int32_t comparand, bool &succeeded)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| location1 | int32_t\& | Variabelreferens för att ändra. |
| värde | int32_t | Värde att lagra. |
| jämförelseobjekt | int32_t | Värde att jämföra variabelns värde med innan utbyte. |
| lyckades | bool\& | Referens till variabel som sätts till true om utbytet inträffade och till false annars. |

### ReturnValue

Variabelns värde vid operationens start oavsett om den ändrades eller inte.

## Se även

* Class [Interlocked](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Interlocked::CompareExchange(T\&, T, T) method


Jämför-och-utbyter värde på variabel: kontrollerar om variabeln är lika med ett specifikt värde och lagrar det nya värdet endast om det lagrade värdet matchar det förväntade.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Variabeltyp. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| location1 | T\& | Variabelreferens för att ändra. |
| värde | T | Värde att lagra. |
| jämförelseobjekt | T | Värde att jämföra variabelns värde med innan utbyte. |

### ReturnValue

Variabelns värde vid operationens start oavsett om den ändrades eller inte.

## Se även

* Class [Interlocked](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Interlocked::CompareExchange(T\&, T, T) method


Jämför-och-utbyter värde på variabel: kontrollerar om variabeln är lika med ett specifikt värde och lagrar det nya värdet endast om det lagrade värdet matchar det förväntade. Inte implementerad.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Variabeltyp. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| location1 | T\& | Variabelreferens för att ändra. |
| värde | T | Värde att lagra. |
| jämförelseobjekt | T | Värde att jämföra variabelns värde med innan utbyte. |

### ReturnValue

Variabelns värde vid operationens start oavsett om den ändrades eller inte.

## Se även

* Class [Interlocked](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
