---
title: "System::PrintTo‑metod"
linktitle: "PrintTo"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::PrintTo‑metod. Skriver värdet som representeras av det angivna objektet till den angivna utmatningsströmmen i C++."
type: docs
weight: 36100
url: /sv/cpp/system/printto/
---
## System::PrintTo(const Decimal\&, ::std::ostream *) method


Skriver värdet som representeras av det angivna objektet till den angivna utmatningsströmmen.

```cpp
void System::PrintTo(const Decimal &d, ::std::ostream *os)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| d | const Decimal\& | Det [Decimal](../decimal/)-objektet att skriva ut till strömmen |
| os | ::std::ostream * | Strömmen att skriva ut det angivna objektet till |

## Se även

* Class [Decimal](../decimal/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(const Details_Exception\&, std::ostream *) method


Skriver värde till ostream. Används mest för felsökning.

```cpp
void System::PrintTo(const Details_Exception &exception, std::ostream *stream)
```

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(const ExceptionWrapper\<T\>\&, std::ostream *) method


Skriver värde till ostream. Används mest för felsökning.

```cpp
template<typename T> void System::PrintTo(const ExceptionWrapper<T> &exception_wrapper, std::ostream *stream)
```

## Se även

* Class [ExceptionWrapper](../exceptionwrapper/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(const Guid\&, std::ostream *) method


Skriver värde till ostream. Används mest för felsökning.

```cpp
void System::PrintTo(const Guid &value, std::ostream *stream)
```

## Se även

* Class [Guid](../guid/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(const Nullable\<T\>\&, std::ostream *) method


Skriver värde till ostream. Används mest för felsökning.

```cpp
template<typename T> void System::PrintTo(const Nullable<T> &value, std::ostream *stream)
```

## Se även

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) method


Skriver värde till ostream. Används mest för felsökning.

```cpp
template<typename T> std::enable_if_t<detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## Se även

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) method


Skriver värde till ostream. Används mest för felsökning.

```cpp
template<typename T> std::enable_if_t<!detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## Se även

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(const System::Object\&, std::ostream *) method


Skriver värde till ostream. Används mest för felsökning.

```cpp
void System::PrintTo(const System::Object &value, std::ostream *stream)
```

## Se även

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(const System::String\&, std::ostream *) method


Skriver sträng till ostream. Används mest för felsökning.

```cpp
void System::PrintTo(const System::String &value, std::ostream *os)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | const System::String\& | att skriva ut. |
| os | std::ostream * | mål‑ostream. |

## Se även

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(const WeakPtr\<T\>\&, std::ostream *) method


Skriver värde till ostream. Används mest för felsökning.

```cpp
template<typename T> void System::PrintTo(const WeakPtr<T> &object_ptr, std::ostream *stream)
```

## Se även

* Class [WeakPtr](../weakptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(DateTime, std::ostream *) method


Skriver värde till ostream. Används mest för felsökning.

```cpp
void System::PrintTo(DateTime value, std::ostream *stream)
```

## Se även

* Class [DateTime](../datetime/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(DateTimeOffset, std::ostream *) method


Skriver värde till ostream. Används mest för felsökning.

```cpp
void System::PrintTo(DateTimeOffset value, std::ostream *stream)
```

## Se även

* Class [DateTimeOffset](../datetimeoffset/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(TimeSpan, std::ostream *) method


Skriver värde till ostream. Används mest för felsökning.

```cpp
void System::PrintTo(TimeSpan value, std::ostream *stream)
```

## Se även

* Class [TimeSpan](../timespan/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
