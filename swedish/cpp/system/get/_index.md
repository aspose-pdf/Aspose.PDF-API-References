---
title: "System::Get metod"
linktitle: "Get"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Get metod. Funktion för att hämta det N-te elementet i en given tupel. Överlagring för basobjekt i C++."
type: docs
weight: 21200
url: /sv/cpp/system/get/
---
## System::Get(const SharedPtr\<Object\>\&) method


Funktion för att hämta det N-te elementet i en given tupel. Överlagring för basobjekt.

```cpp
template<std::size_t> auto System::Get(const SharedPtr<Object> &object)
```


| Parameter | Beskrivning |
| --- | --- |
| N | elementindex. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| objekt | const SharedPtr\<Object\>\& | objekt att inspektera. |

### ReturnValue

värde av det N-te tupel-elementet kastat till objekt.

## Se även

* Typedef [SharedPtr](../sharedptr/)
* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::Get(const SharedPtr\<T\>\&) method


Funktion för att hämta det N-te elementet i en given tupel. Överlagring för delade pekare.

```cpp
template<std::size_t,typename T> auto System::Get(const SharedPtr<T> &pointer)
```


| Parameter | Beskrivning |
| --- | --- |
| N | elementindex. |
| T | typ av inspekterat objekt. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| objekt | const SharedPtr\<T\>\& | objekt att inspektera. |

### ReturnValue

värde av det N-te tupel-elementet.

## Se även

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::Get(const T\&) method


Funktion för att hämta det N-te elementet i en given tupel. Överlagring för objekt med Deconstruct-metod.

```cpp
template<std::size_t,typename T> auto System::Get(const T &object)
```


| Parameter | Beskrivning |
| --- | --- |
| N | elementindex. |
| T | typ av inspekterat objekt. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| objekt | const T\& | objekt att inspektera. |

### ReturnValue

värde av det N-te tupel-elementet.

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::Get(const ValueTuple\<Args...\>\&) method


Hämtar det N-te elementet i värdetupeln.

```cpp
template<std::size_t,typename...> auto System::Get(const ValueTuple<Args...> &tuple)
```


| Parameter | Beskrivning |
| --- | --- |
| N | elementindex. |
| Argument | tupel-element. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tupel | const ValueTuple\<Args...\>\& | tuple för att hämta element från. |

### ReturnValue

värde av det N-te tupel-elementet.

## Se även

* Class [ValueTuple](../valuetuple/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::Get(T\&, const Index\&) method


Implementering för collection[index]-uttryck.

```cpp
template<typename T> auto & System::Get(T &collection, const Index &index)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typ av samling. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| samling | T\& | Samlingsobjekt. |
| index | const Index\& | Elementindex av typen [System.Index](../index/). |

### ReturnValue

Samlingselement vid den beräknade förskjutningen.

## Se även

* Class [Index](../index/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::Get(T\&, const Range\&) method


Returnerar en slice av den angivna samlingen som definieras av det angivna intervallet.

```cpp
template<typename T> auto System::Get(T &collection, const Range &range)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| samling | T\& | Samlingen att slice:a. |
| intervall | const Range\& | Intervallet som specificerar slice-gränserna. |

### ReturnValue

En vy eller slice av samlingen från den beräknade startförskjutningen och längden.

## Se även

* Class [Range](../range/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
