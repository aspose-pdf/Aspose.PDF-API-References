---
title: System::Collections::Generic::ISet::IsProperSubsetOf method
linktitle: IsProperSubsetOf
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::ISet::IsProperSubsetOf method. Checks if current set is a strict subset of other container in C++.'
type: docs
weight: 400
url: /cpp/system.collections.generic/iset/ispropersubsetof/
---
## ISet::IsProperSubsetOf method


Checks if current set is a strict subset of other container.

```cpp
virtual bool System::Collections::Generic::ISet<T>::IsProperSubsetOf(IEnumerablePtr other)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| other | IEnumerablePtr | Superset to check against. |

### ReturnValue

True if all elements in current set are present in **other** and **other** has more elements than current set, false otherwise.

## See Also

* Typedef [IEnumerablePtr](../ienumerableptr/)
* Class [ISet](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
