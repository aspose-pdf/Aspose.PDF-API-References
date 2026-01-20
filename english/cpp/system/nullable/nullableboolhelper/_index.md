---
title: System::Nullable::NullableBoolHelper method
linktitle: NullableBoolHelper
second_title: Aspose.PDF for C++ API Reference
description: 'System::Nullable::NullableBoolHelper method. Helper function to check if this and other are both not nulls and call a lambda if so. Used in implementation.s in C++.'
type: docs
weight: 800
url: /cpp/system/nullable/nullableboolhelper/
---
## Nullable::NullableBoolHelper method


Helper function to check if this and **other** are both not nulls and call a lambda if so. Used in implementation.s.

```cpp
template<typename T1> bool System::Nullable<T>::NullableBoolHelper(const T1 &other, const std::function<bool()> &f, bool default_if_both_are_null=false) const
```


| Parameter | Description |
| --- | --- |
| T1 | Other nullable type. |

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | Other nullable value to compare to. |
| f | const std::function\<bool()>\& | Lambda to call if both **this** and **other** are not nulls. |
| default_if_both_are_null | bool | Return value if both values are nulls. |

### ReturnValue

false if either **this** or **other** is null; **default_if_both_are_null** if both are null; result of **f** call if both are not null.

## See Also

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
