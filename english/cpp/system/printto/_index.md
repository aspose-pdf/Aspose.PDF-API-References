---
title: System::PrintTo method
linktitle: PrintTo
second_title: Aspose.PDF for C++ API Reference
description: 'System::PrintTo method. Writes the value represented by the specified object to the specified output stream in C++.'
type: docs
weight: 35400
url: /cpp/system/printto/
---
## System::PrintTo(const Decimal\&, ::std::ostream *) method


Writes the value represented by the specified object to the specified output stream.

```cpp
void System::PrintTo(const Decimal &d, ::std::ostream *os)
```


| Parameter | Type | Description |
| --- | --- | --- |
| d | const Decimal\& | The [Decimal](../decimal/) object to print to the stream |
| os | ::std::ostream * | The stream to print the specified object to |

## See Also

* Class [Decimal](../decimal/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(const Details_Exception\&, std::ostream *) method


Prints value to ostream. Mostly used for debug.

```cpp
void System::PrintTo(const Details_Exception &exception, std::ostream *stream)
```

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(const ExceptionWrapper\<T\>\&, std::ostream *) method


Prints value to ostream. Mostly used for debug.

```cpp
template<typename T> void System::PrintTo(const ExceptionWrapper<T> &exception_wrapper, std::ostream *stream)
```

## See Also

* Class [ExceptionWrapper](../exceptionwrapper/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(const Guid\&, std::ostream *) method


Prints value to ostream. Mostly used for debug.

```cpp
void System::PrintTo(const Guid &value, std::ostream *stream)
```

## See Also

* Class [Guid](../guid/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(const Nullable\<T\>\&, std::ostream *) method


Prints value to ostream. Mostly used for debug.

```cpp
template<typename T> void System::PrintTo(const Nullable<T> &value, std::ostream *stream)
```

## See Also

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) method


Prints value to ostream. Mostly used for debug.

```cpp
template<typename T> std::enable_if_t<detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## See Also

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) method


Prints value to ostream. Mostly used for debug.

```cpp
template<typename T> std::enable_if_t<!detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## See Also

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(const System::Object\&, std::ostream *) method


Prints value to ostream. Mostly used for debug.

```cpp
void System::PrintTo(const System::Object &value, std::ostream *stream)
```

## See Also

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(const System::String\&, std::ostream *) method


Prints string to ostream. Mostly used for debug.

```cpp
void System::PrintTo(const System::String &value, std::ostream *os)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::String\& | to print. |
| os | std::ostream * | target ostream. |

## See Also

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(const WeakPtr\<T\>\&, std::ostream *) method


Prints value to ostream. Mostly used for debug.

```cpp
template<typename T> void System::PrintTo(const WeakPtr<T> &object_ptr, std::ostream *stream)
```

## See Also

* Class [WeakPtr](../weakptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(DateTime, std::ostream *) method


Prints value to ostream. Mostly used for debug.

```cpp
void System::PrintTo(DateTime value, std::ostream *stream)
```

## See Also

* Class [DateTime](../datetime/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(DateTimeOffset, std::ostream *) method


Prints value to ostream. Mostly used for debug.

```cpp
void System::PrintTo(DateTimeOffset value, std::ostream *stream)
```

## See Also

* Class [DateTimeOffset](../datetimeoffset/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::PrintTo(TimeSpan, std::ostream *) method


Prints value to ostream. Mostly used for debug.

```cpp
void System::PrintTo(TimeSpan value, std::ostream *stream)
```

## See Also

* Class [TimeSpan](../timespan/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
