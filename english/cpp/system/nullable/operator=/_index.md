---
title: System::Nullable::operator= method
linktitle: operator=
second_title: Aspose.PDF for C++ API Reference
description: 'System::Nullable::operator= method. Replaces the object''s currently represented value with the specified one in C++.'
type: docs
weight: 1800
url: /cpp/system/nullable/operator=/
---
## Nullable::operator=(const Nullable\<T1\>\&) method


Replaces the object's currently represented value with the specified one.

```cpp
template<typename T1> Nullable<T> & System::Nullable<T>::operator=(const Nullable<T1> &x)
```


| Parameter | Description |
| --- | --- |
| The | type of the new value to be represented by the current object |

| Parameter | Type | Description |
| --- | --- | --- |
| x | const Nullable\<T1\>\& | The new value to be represented by the current object |

### ReturnValue

A reference to the self

## See Also

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator=(const T1\&) method


Replaces the object's currently represented value with the specified one.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value &&!std::is_null_pointer<T1>::value, Nullable<T> &>::type System::Nullable<T>::operator=(const T1 &x)
```


| Parameter | Description |
| --- | --- |
| The | type of the new value to be represented by the current object |

| Parameter | Type | Description |
| --- | --- | --- |
| x | const T1\& | The new value to be represented by the current object |

### ReturnValue

A reference to the self

## See Also

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator=(std::nullptr_t) method


Assigns a null to the current object.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator=(std::nullptr_t)
```


### ReturnValue

A [Nullable](../) object that represents null-value.

## See Also

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
