---
title: System::Nullable::operator<= method
linktitle: operator<=
second_title: Aspose.PDF for C++ API Reference
description: 'System::Nullable::operator<= method. Determines if the value represented by the current object is less or equal to the value represented by the specified Nullable object by applying operator<=() to these values in C++.'
type: docs
weight: 1700
url: /cpp/system/nullable/operator_=/
---
## Nullable::operator<=(const Nullable\<T1\>\&) const method


Determines if the value represented by the current object is less or equal to the value represented by the specified [Nullable](../) object by applying [operator<=()](./) to these values.

```cpp
template<typename T1> bool System::Nullable<T>::operator<=(const Nullable<T1> &other) const
```


| Parameter | Description |
| --- | --- |
| T1 | The underlying type of the [Nullable](../) object to compare with |

| Parameter | Type | Description |
| --- | --- | --- |
| other | const Nullable\<T1\>\& | A constant reference to the [Nullable](../) object to compare with |

### ReturnValue

True if the value represented by the current object is less or equal to the value represented by the specified [Nullable](../) object, otherwise - false

## See Also

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator<=(const T1\&) const method


Determines if the value represented by the current object is less or equal to the specified value by applying [operator<=()](./) to these values.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<=(const T1 &other) const
```


| Parameter | Description |
| --- | --- |
| T1 | The type of the value to compare with |

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | A constant reference to the value to compare with |

### ReturnValue

True if the value represented by the current object is less or equal to the specified value, otherwise - false

## See Also

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator<=(std::nullptr_t) const method


Always returns false.

```cpp
bool System::Nullable<T>::operator<=(std::nullptr_t) const
```

## See Also

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
---
title: System::Nullable::operator>= method
linktitle: operator>=
second_title: Aspose.PDF for C++ API Reference
description: 'System::Nullable::operator>= method. Determines if the value represented by the current object is greater or equal to the value represented by the specified Nullable object by applying operator>=() to these values in C++.'
type: docs
weight: 2100
url: /cpp/system/nullable/operator_=/
---
## Nullable::operator>=(const Nullable\<T1\>\&) const method


Determines if the value represented by the current object is greater or equal to the value represented by the specified [Nullable](../) object by applying [operator>=()](./) to these values.

```cpp
template<typename T1> bool System::Nullable<T>::operator>=(const Nullable<T1> &other) const
```


| Parameter | Description |
| --- | --- |
| T1 | The underlying type of the [Nullable](../) object to compare with |

| Parameter | Type | Description |
| --- | --- | --- |
| other | const Nullable\<T1\>\& | A constant reference to the [Nullable](../) object to compare with |

### ReturnValue

True if the value represented by the current object is greater or equal to the value represented by the specified [Nullable](../) object, otherwise - false

## See Also

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator>=(const T1\&) const method


Determines if the value represented by the current object is greater or equal to the value represented by the specified object by applying [operator>=()](./) to these values.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>=(const T1 &other) const
```


| Parameter | Description |
| --- | --- |
| T1 | The underlying type of the value to compare the value represented by the current object with |

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | A constant reference to an object to compare the current object with |

### ReturnValue

True if the value represented by the current object is greater or equal to the value represented by the specified object, otherwise - false

## See Also

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator>=(std::nullptr_t) const method


Always returns false.

```cpp
bool System::Nullable<T>::operator>=(std::nullptr_t) const
```


### ReturnValue

Always - false

## See Also

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
---
title: System::Nullable::operator|= method
linktitle: operator|=
second_title: Aspose.PDF for C++ API Reference
description: 'System::Nullable::operator|= method. Applies operator|=() to the value represented by the current object using the specified value as a right-side argument in C++.'
type: docs
weight: 2200
url: /cpp/system/nullable/operator_=/
---
## Nullable::operator|= method


Applies [operator|=()](./) to the value represented by the current object using the specified value as a right-side argument.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator|=(bool other)
```


| Parameter | Description |
| --- | --- |
| T1 | The template parameter to make SFINAE work. |

| Parameter | Type | Description |
| --- | --- | --- |
| other | bool | A boolean value that is used as a right-side value of the [operator|=()](./) applied to the value represented by the current object. |

### ReturnValue

A reference to the self.

## See Also

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
