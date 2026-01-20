---
title: System::ExceptionWrapper::ExceptionWrapper constructor
linktitle: ExceptionWrapper
second_title: Aspose.PDF for C++ API Reference
description: 'System::ExceptionWrapper::ExceptionWrapper constructor. Constructor that forwards parameters to the Exception class constructors and creates smart pointer that holds new Exception class instance in C++.'
type: docs
weight: 100
url: /cpp/system/exceptionwrapper/exceptionwrapper/
---
## ExceptionWrapper::ExceptionWrapper(Args\&&...) constructor


Constructor that forwards parameters to the [Exception](../../exception/) class constructors and creates smart pointer that holds new [Exception](../../exception/) class instance.

```cpp
template<typename ...,typename> System::ExceptionWrapper<T>::ExceptionWrapper(Args &&...args)
```

## See Also

* Class [ExceptionWrapper](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ExceptionWrapper::ExceptionWrapper(const ExceptionPtr\&) constructor


Constructs a instance of [ExceptionWrapper](../) class that contains passed pointer.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionPtr &ptr)
```


| Parameter | Type | Description |
| --- | --- | --- |
| ptr | const ExceptionPtr\& | Smart pointer to the instance of [Exception](../../exception/) class. |

## See Also

* Typedef [ExceptionPtr](../../exceptionptr/)
* Class [ExceptionWrapper](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ExceptionWrapper::ExceptionWrapper(const ExceptionWrapper\&) constructor


Copy constructor.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionWrapper &other)
```


| Parameter | Type | Description |
| --- | --- | --- |
| other | const ExceptionWrapper\& | Other instance of wrapper class that must be copied. |

## See Also

* Class [ExceptionWrapper](../)
* Class [ExceptionWrapper](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ExceptionWrapper::ExceptionWrapper(ExceptionWrapper\&&) constructor


Move constructor.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(ExceptionWrapper &&other) noexcept
```


| Parameter | Type | Description |
| --- | --- | --- |
| other | ExceptionWrapper\&& | Other instance of wrapper class that must be moved. |

## See Also

* Class [ExceptionWrapper](../)
* Class [ExceptionWrapper](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ExceptionWrapper::ExceptionWrapper(std::nullptr_t) constructor


Constructs a null-instance of [ExceptionWrapper](../) class that does not represent any exception.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(std::nullptr_t)
```

## See Also

* Class [ExceptionWrapper](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
