---
title: System::WeakPtr::operator= method
linktitle: operator=
second_title: Aspose.PDF for C++ API Reference
description: 'System::WeakPtr::operator= method. Assigns value to weak pointer. Calls into specific assignment operator of SmartPtr_ in C++.'
type: docs
weight: 400
url: /cpp/system/weakptr/operator=/
---
## WeakPtr::operator= method


Assigns value to weak pointer. Calls into specific assignment operator of [SmartPtr_](../smartptr_/).

```cpp
template<typename Q> WeakPtr & System::WeakPtr<T>::operator=(Q &&value)
```


| Parameter | Description |
| --- | --- |
| Q | Argument type supported by [System::SmartPtr](../../smartptr/) assignment operators. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | Q\&& | Pointer to copy pointee value from. |

## See Also

* Class [WeakPtr](../)
* Class [WeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
