---
title: System::Nullable::operator&= method
linktitle: operator&=
second_title: Aspose.PDF for C++ API Reference
description: 'System::Nullable::operator&= method. Applies operator&=() to the value represented by the current object using the specified value as a right-side argument in C++.'
type: docs
weight: 1100
url: /cpp/system/nullable/operator&=/
---
## Nullable::operator&= method


Applies [operator&=()](./) to the value represented by the current object using the specified value as a right-side argument.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator&=(bool other)
```


| Parameter | Description |
| --- | --- |
| T1 | The template parameter to make SFINAE work. |

| Parameter | Type | Description |
| --- | --- | --- |
| other | bool | A boolean value that is used as a right-side value of the [operator&=()](./) applied to the value represented by the current object. |

### ReturnValue

A reference to the self.

## See Also

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
