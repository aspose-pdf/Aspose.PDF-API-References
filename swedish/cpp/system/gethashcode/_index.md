---
title: "System::GetHashCode metod"
linktitle: "GetHashCode"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::GetHashCode metod. Specialisering för std::thread::id; Returnerar hashkoden för det angivna trådföremålet i C++."
type: docs
weight: 21900
url: /sv/cpp/system/gethashcode/
---
## System::GetHashCode(const std::thread::id\&) method


Specialisering för std::thread::id; Returnerar hashkoden för det angivna trådföremålet.

```cpp
int System::GetHashCode(const std::thread::id &id)
```

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::GetHashCode(const T\&) method


Returnerar en hashkod för det angivna skalära värdet.

```cpp
template<typename T> std::enable_if<std::is_scalar<T>::value, int>::type System::GetHashCode(const T &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typen av värdet för vilket funktionen genererar hashkod |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const T\& | Värdet att generera hashkod för |

### ReturnValue

Hashkoden som genererats för det angivna värdet

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::GetHashCode(const T\&) method


Returnerar en hashkod för det angivna objektet.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&System::IsSmartPtr<T>::value, int>::type System::GetHashCode(const T &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typen av objektet för vilket funktionen genererar hashkod |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const T\& | Den [SmartPtr](../smartptr/) som pekar på objektet att generera hashkod för |

### ReturnValue

Hashkoden som genererats för det angivna objektet

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::GetHashCode(const T\&) method


Returnerar en hashkod för det angivna objektet som är ett undantag.

```cpp
template<typename T> std::enable_if<System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typen av objektet för vilket funktionen genererar hashkod |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const T\& | Den [Exception](../exception/) omslag som innehåller objektet att generera hashkod för |

### ReturnValue

Hashkoden som genererats för det angivna objektet

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::GetHashCode(const T\&) method


Returnerar en hashkod för det angivna objektet som varken är en smart pekare eller ett undantag.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&!System::IsSmartPtr<T>::value &&!System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typen av objektet för vilket funktionen genererar hashkod |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const T\& | En konstant referens till objektet att generera hashkod för |

### ReturnValue

Hashkoden som genererats för det angivna objektet

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
