---
title: System::GetHashCode method
linktitle: GetHashCode
second_title: Aspose.PDF for C++ API Reference
description: 'System::GetHashCode method. Specialization for std::thread::id; Returns the hash code for the specified thread object in C++.'
type: docs
weight: 21200
url: /cpp/system/gethashcode/
---
## System::GetHashCode(const std::thread::id\&) method


Specialization for std::thread::id; Returns the hash code for the specified thread object.

```cpp
int System::GetHashCode(const std::thread::id &id)
```

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::GetHashCode(const T\&) method


Returns a hash code for the specified scalar value.

```cpp
template<typename T> std::enable_if<std::is_scalar<T>::value, int>::type System::GetHashCode(const T &obj)
```


| Parameter | Description |
| --- | --- |
| T | The type of the value for which the function generates hash code |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | The value to generate hash code for |

### ReturnValue

The hash code generated for the specified value

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::GetHashCode(const T\&) method


Returns a hash code for the specified object.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&System::IsSmartPtr<T>::value, int>::type System::GetHashCode(const T &obj)
```


| Parameter | Description |
| --- | --- |
| T | The type of the object for which the function generates hash code |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | The [SmartPtr](../smartptr/) pointing to the object to generate hash code for |

### ReturnValue

The hash code generated for the specified object

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::GetHashCode(const T\&) method


Returns a hash code for the specified object which is exception.

```cpp
template<typename T> std::enable_if<System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```


| Parameter | Description |
| --- | --- |
| T | The type of the object for which the function generates hash code |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | The [Exception](../exception/) Wrapper that contains the object to generate hash code for |

### ReturnValue

The hash code generated for the specified object

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::GetHashCode(const T\&) method


Returns a hash code for the specified object which is not a smart pointer nor exception.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&!System::IsSmartPtr<T>::value &&!System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```


| Parameter | Description |
| --- | --- |
| T | The type of the object for which the function generates hash code |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | A const reference to the object to generate hash code for |

### ReturnValue

The hash code generated for the specified object

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
