---
title: System::SmartPtr::operator[] method
linktitle: operator[]
second_title: Aspose.PDF for C++ API Reference
description: 'System::SmartPtr::operator[] method. Accessor for array elements. Only compiles if SmartPtr_ is specialization of System::Array in C++.'
type: docs
weight: 3000
url: /cpp/system/smartptr/operator[]/
---
## SmartPtr::operator[] method


Accessor for array elements. Only compiles if [SmartPtr_](../smartptr_/) is specialization of [System::Array](../../array/).

```cpp
template<typename IdxType> decltype(System::Details::GetByIndex(std::declval<const SmartPtr_ *>(), std::declval<IdxType>())) System::SmartPtr<T>::operator[](IdxType idx) const
```


| Parameter | Description |
| --- | --- |
| IdxType | Type of index (assumed integral). |

| Parameter | Type | Description |
| --- | --- | --- |
| idx | IdxType | Index in array. |

### ReturnValue

[Array](../../array/) value at idx position.

## See Also

* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
