---
title: "Метод System::PrintTo"
linktitle: "PrintTo"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::PrintTo. Записывает значение, представленное указанным объектом, в указанный поток вывода в C++."
type: docs
weight: 36100
url: /ru/cpp/system/printto/
---
## System::PrintTo(const Decimal\&, ::std::ostream *) method


Записывает значение, представленное указанным объектом, в указанный поток вывода.

```cpp
void System::PrintTo(const Decimal &d, ::std::ostream *os)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| d | const Decimal\& | Объект [Decimal](../decimal/), который нужно вывести в поток |
| os | ::std::ostream * | Поток, в который нужно вывести указанный объект |

## См. также

* Class [Decimal](../decimal/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(const Details_Exception\&, std::ostream *) method


Выводит значение в ostream. В основном используется для отладки.

```cpp
void System::PrintTo(const Details_Exception &exception, std::ostream *stream)
```

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(const ExceptionWrapper\<T\>\&, std::ostream *) method


Выводит значение в ostream. В основном используется для отладки.

```cpp
template<typename T> void System::PrintTo(const ExceptionWrapper<T> &exception_wrapper, std::ostream *stream)
```

## См. также

* Class [ExceptionWrapper](../exceptionwrapper/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(const Guid\&, std::ostream *) method


Выводит значение в ostream. В основном используется для отладки.

```cpp
void System::PrintTo(const Guid &value, std::ostream *stream)
```

## См. также

* Class [Guid](../guid/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(const Nullable\<T\>\&, std::ostream *) method


Выводит значение в ostream. В основном используется для отладки.

```cpp
template<typename T> void System::PrintTo(const Nullable<T> &value, std::ostream *stream)
```

## См. также

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) method


Выводит значение в ostream. В основном используется для отладки.

```cpp
template<typename T> std::enable_if_t<detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## См. также

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) method


Выводит значение в ostream. В основном используется для отладки.

```cpp
template<typename T> std::enable_if_t<!detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## См. также

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(const System::Object\&, std::ostream *) method


Выводит значение в ostream. В основном используется для отладки.

```cpp
void System::PrintTo(const System::Object &value, std::ostream *stream)
```

## См. также

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(const System::String\&, std::ostream *) method


Выводит строку в ostream. В основном используется для отладки.

```cpp
void System::PrintTo(const System::String &value, std::ostream *os)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const System::String\& | для вывода. |
| os | std::ostream * | целевой ostream. |

## См. также

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(const WeakPtr\<T\>\&, std::ostream *) method


Выводит значение в ostream. В основном используется для отладки.

```cpp
template<typename T> void System::PrintTo(const WeakPtr<T> &object_ptr, std::ostream *stream)
```

## См. также

* Class [WeakPtr](../weakptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(DateTime, std::ostream *) method


Выводит значение в ostream. В основном используется для отладки.

```cpp
void System::PrintTo(DateTime value, std::ostream *stream)
```

## См. также

* Class [DateTime](../datetime/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(DateTimeOffset, std::ostream *) method


Выводит значение в ostream. В основном используется для отладки.

```cpp
void System::PrintTo(DateTimeOffset value, std::ostream *stream)
```

## См. также

* Class [DateTimeOffset](../datetimeoffset/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(TimeSpan, std::ostream *) method


Выводит значение в ostream. В основном используется для отладки.

```cpp
void System::PrintTo(TimeSpan value, std::ostream *stream)
```

## См. также

* Class [TimeSpan](../timespan/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
