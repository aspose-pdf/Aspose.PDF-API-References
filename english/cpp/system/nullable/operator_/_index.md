---
title: System::Nullable::operator< method
linktitle: operator<
second_title: Aspose.PDF for C++ API Reference
description: 'System::Nullable::operator< method. Determines if the value represented by the current object is less than the value represented by the specified Nullable object by applying operator<() to these values in C++.'
type: docs
weight: 1600
url: /cpp/system/nullable/operator_/
---
## Nullable::operator<(const Nullable\<T1\>\&) const method


Determines if the value represented by the current object is less than the value represented by the specified [Nullable](../) object by applying [operator<()](./) to these values.

```cpp
template<typename T1> bool System::Nullable<T>::operator<(const Nullable<T1> &other) const
```


| Parameter | Description |
| --- | --- |
| T1 | The underlying type of the [Nullable](../) object to compare with |

| Parameter | Type | Description |
| --- | --- | --- |
| other | const Nullable\<T1\>\& | A constant reference to the [Nullable](../) object to compare with |

### ReturnValue

True if the value represented by the current object is less than the value represented by the specified [Nullable](../) object, otherwise - false

## See Also

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator<(const T1\&) const method


Determines if the value represented by the current object is less than the specified value by applying [operator<()](./) to these values.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<(const T1 &other) const
```


| Parameter | Description |
| --- | --- |
| T1 | The type of the value to compare with |

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | A constant reference to the value to compare with |

### ReturnValue

True if the value represented by the current object is less than the specified value, otherwise - false

## See Also

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator<(std::nullptr_t) const method


Always returns false.

```cpp
bool System::Nullable<T>::operator<(std::nullptr_t) const
```

## See Also

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
---
title: System::Nullable::operator> method
linktitle: operator>
second_title: Aspose.PDF for C++ API Reference
description: 'System::Nullable::operator> method. Determines if the value represented by the current object is greater than the value represented by the specified Nullable object by applying operator>() to these values in C++.'
type: docs
weight: 2000
url: /cpp/system/nullable/operator_/
---
## Nullable::operator>(const Nullable\<T1\>\&) const method


Determines if the value represented by the current object is greater than the value represented by the specified [Nullable](../) object by applying [operator>()](./) to these values.

```cpp
template<typename T1> bool System::Nullable<T>::operator>(const Nullable<T1> &other) const
```


| Parameter | Description |
| --- | --- |
| T1 | The underlying type of the [Nullable](../) object to compare with |

| Parameter | Type | Description |
| --- | --- | --- |
| other | const Nullable\<T1\>\& | A constant reference to the [Nullable](../) object to compare with |

### ReturnValue

True if the value represented by the current object is greater than the value represented by the specified [Nullable](../) object, otherwise - false

## See Also

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator>(const T1\&) const method


Determines if the value represented by the current object is greater than the specified value by applying [operator>()](./) to these values.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>(const T1 &other) const
```


| Parameter | Description |
| --- | --- |
| T1 | The type of the value to compare with |

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | A constant reference to the value to compare with |

### ReturnValue

True if the value represented by the current object is greater than the specified value, otherwise - false

## See Also

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator>(std::nullptr_t) const method


Always returns false.

```cpp
bool System::Nullable<T>::operator>(std::nullptr_t) const
```

## See Also

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
