---
title: System::Linq::IOrderedEnumerable::LINQ_ThenBy method
linktitle: LINQ_ThenBy
second_title: Aspose.PDF for C++ API Reference
description: 'How to use LINQ_ThenBy method of System::Linq::IOrderedEnumerable class in C++.'
type: docs
weight: 300
url: /cpp/system.linq/iorderedenumerable/linq_thenby/
---
## IOrderedEnumerable::LINQ_ThenBy(const Func\<Source, Key\>\&) method




```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<Source>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<Source, Key> &keySelector)
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOrderedEnumerable](../)
* Class [Func](../../../system/func/)
* Class [IOrderedEnumerable](../)
* Namespace [System::Linq](../../)
* Library [Aspose.PDF for C++](../../../)
## IOrderedEnumerable::LINQ_ThenBy(const Func\<T, Key\>\&) method


Performs a subsequent ordering of the elements in a sequence in ascending order according to a key.

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<T>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<T, Key> &keySelector)
```


| Parameter | Description |
| --- | --- |
| Key | The type of the key returned by keySelector. |

| Parameter | Type | Description |
| --- | --- | --- |
| keySelector | const Func\<T, Key\>\& | A function to extract a key from each element. |

### ReturnValue

[System::Linq::IOrderedEnumerable](../) whose elements are sorted according to a key.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOrderedEnumerable](../)
* Class [Func](../../../system/func/)
* Class [IOrderedEnumerable](../)
* Namespace [System::Linq](../../)
* Library [Aspose.PDF for C++](../../../)
