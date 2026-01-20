---
title: System::Nullable::operator-= method
linktitle: operator-=
second_title: Aspose.PDF for C++ API Reference
description: 'System::Nullable::operator-= method. Applies operator-=() to the value represented by the current object using the value represented by the specified Nullable object as the right-side argument in C++.'
type: docs
weight: 1500
url: /cpp/system/nullable/operator-=/
---
## Nullable::operator-=(const Nullable\<T1\>\&) method


Applies [operator-=()](./) to the value represented by the current object using the value represented by the specified [Nullable](../) object as the right-side argument.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator-=(const Nullable<T1> &other)
```


| Parameter | Description |
| --- | --- |
| T1 | The underlying type of a [Nullable](../) object the value represented by which is used as the right-side argument of [operator-=()](./) |

| Parameter | Type | Description |
| --- | --- | --- |
| other | const Nullable\<T1\>\& | A constant reference to [Nullable](../) object the value represented by which is used as a right-side argument of the [operator-=()](./) applied to the value represented by the current object. |

### ReturnValue

A reference to the self

## See Also

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator-=(const T1\&) method


Applies [operator-=()](./) to the value represented by the current object using the specified value as a right-side argument.

```cpp
template<typename T1,typename> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator-=(const T1 &other)
```


| Parameter | Description |
| --- | --- |
| T1 | The type of the value used as the right-side value of [operator-=()](./) |

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | A constant reference to the value that is used as a right-side value of the [operator-=()](./) applied to the value represented by the current object. |

### ReturnValue

A reference to the self

## See Also

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator-=(T1) method


Returns an instance of [Nullable](../) class that represents a null-value.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-=(T1)
```

## See Also

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
