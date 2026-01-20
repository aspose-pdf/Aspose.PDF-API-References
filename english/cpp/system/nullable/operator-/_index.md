---
title: System::Nullable::operator- method
linktitle: operator-
second_title: Aspose.PDF for C++ API Reference
description: 'System::Nullable::operator- method. Subtracts nullable values in C++.'
type: docs
weight: 1400
url: /cpp/system/nullable/operator-/
---
## Nullable::operator-(const Nullable\<T1\>\&) const method


Subtracts nullable values.

```cpp
template<typename T1> System::Nullable<decltype(get_Value() - other.get_Value())> System::Nullable<T>::operator-(const Nullable<T1> &other) const
```


| Parameter | Description |
| --- | --- |
| T1 | Right operand type. |

| Parameter | Type | Description |
| --- | --- | --- |
| other | const Nullable\<T1\>\& | value to subtract. |

### ReturnValue

Subtraction result.

## See Also

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator-(const T1\&) const method


Subtracts nullable and non-nullable values.

```cpp
template<typename T1,typename> Nullable<decltype(get_Value() - other)> System::Nullable<T>::operator-(const T1 &other) const
```


| Parameter | Description |
| --- | --- |
| T1 | Right operand type. |

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | value to subtract. |

### ReturnValue

Subtraction result.

## See Also

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator-(T1) const method


Subtracts nullable and null-pointed values.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-(T1) const
```


| Parameter | Description |
| --- | --- |
| T1 | Right operand type, should be nullptr_t. |

### ReturnValue

Empty [Nullable](../) object.

## See Also

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
