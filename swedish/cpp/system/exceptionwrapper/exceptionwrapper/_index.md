---
title: "System::ExceptionWrapper::ExceptionWrapper-konstruktor"
linktitle: "ExceptionWrapper"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::ExceptionWrapper::ExceptionWrapper-konstruktor. Konstruktor som vidarebefordrar parametrar till Exception-klassens konstruktorer och skapar en smart pekare som håller en ny Exception-klassinstans i C++."
type: docs
weight: 100
url: /sv/cpp/system/exceptionwrapper/exceptionwrapper/
---
## ExceptionWrapper::ExceptionWrapper(Args\&&...) constructor


Konstruktor som vidarebefordrar parametrar till [Exception](../../exception/)-klassens konstruktorer och skapar en smart pekare som håller en ny [Exception](../../exception/)-klassinstans.

```cpp
template<typename ...,typename> System::ExceptionWrapper<T>::ExceptionWrapper(Args &&...args)
```

## Se även

* Class [ExceptionWrapper](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ExceptionWrapper::ExceptionWrapper(const ExceptionPtr\&) constructor


Skapar en instans av [ExceptionWrapper](../)-klassen som innehåller den överförda pekaren.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionPtr &ptr)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ptr | const ExceptionPtr\& | Smart pekare till instansen av [Exception](../../exception/)-klassen. |

## Se även

* Typedef [ExceptionPtr](../../exceptionptr/)
* Class [ExceptionWrapper](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ExceptionWrapper::ExceptionWrapper(const ExceptionWrapper\&) constructor


Kopieringskonstruktor.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionWrapper &other)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| annat | const ExceptionWrapper\& | Annan instans av omslagsklassen som måste kopieras. |

## Se även

* Class [ExceptionWrapper](../)
* Class [ExceptionWrapper](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ExceptionWrapper::ExceptionWrapper(ExceptionWrapper\&&) constructor


Flyttkonstruktor.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(ExceptionWrapper &&other) noexcept
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| annat | ExceptionWrapper\&& | Annan instans av omslagsklass som måste flyttas. |

## Se även

* Class [ExceptionWrapper](../)
* Class [ExceptionWrapper](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ExceptionWrapper::ExceptionWrapper(std::nullptr_t) constructor


Skapar en null-instans av [ExceptionWrapper](../)-klassen som inte representerar något undantag.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(std::nullptr_t)
```

## Se även

* Class [ExceptionWrapper](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
