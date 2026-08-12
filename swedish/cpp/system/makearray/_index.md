---
title: "System::MakeArray‑metod"
linktitle: "MakeArray"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::MakeArray‑metod. En fabrikfunktion som konstruerar ett nytt Array objekt genom att skicka de angivna argumenten till dess konstruktor i C++."
type: docs
weight: 24800
url: /sv/cpp/system/makearray/
---
## System::MakeArray(Args\&&...) method


En fabrikfunktion som konstruerar ett nytt [Array](../array/) objekt genom att skicka de angivna argumenten till dess konstruktor.

```cpp
template<class T,class...> ArrayPtr<T> System::MakeArray(Args &&... args)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i det [Array](../array/) objekt som funktionen konstruerar |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| args | Args\&&... | Argumenten som skickas till konstruktorn för det [Array](../array/) objekt som konstrueras |

### ReturnValue

En smart pekare som pekar på det konstruerade [Array](../array/) objektet

## Se även

* Typedef [ArrayPtr](../arrayptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::MakeArray(Integral, Args\&&...) method


En fabrikfunktion som konstruerar ett nytt [Array](../array/) objekt genom att skicka de angivna argumenten till dess konstruktor.

```cpp
template<class T,class Integral,class...> std::enable_if<std::is_integral<Integral>::value, ArrayPtr<T>>::type System::MakeArray(Integral size, Args &&... args)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i det [Array](../array/) objekt som funktionen konstruerar |
| Integral | Typ av arraystorlek. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size | Integral | Storlek på den array som skapas. |
| args | Args\&&... | Argumenten som skickas till konstruktorn för det [Array](../array/) objekt som konstrueras |

### ReturnValue

En smart pekare som pekar på det konstruerade [Array](../array/) objektet

## Se även

* Typedef [ArrayPtr](../arrayptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::MakeArray(std::initializer_list\<T\>) method


En fabrikfunktion som konstruerar ett nytt [Array](../array/)‑objekt, fyller det med elementen från den angivna initieringslistan och returnerar en smart pekare som pekar på [Array](../array/)‑objektet.

```cpp
template<typename T> ArrayPtr<T> System::MakeArray(std::initializer_list<T> init)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i det [Array](../array/) objekt som funktionen konstruerar |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| init | std::initializer_list\<T\> | Initieringslistan som innehåller elementen för att fylla arrayen med |

### ReturnValue

En smart pekare som pekar på det konstruerade [Array](../array/) objektet

## Se även

* Typedef [ArrayPtr](../arrayptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
