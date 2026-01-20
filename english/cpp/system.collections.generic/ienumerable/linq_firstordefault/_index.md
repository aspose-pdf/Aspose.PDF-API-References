---
title: System::Collections::Generic::IEnumerable::LINQ_FirstOrDefault method
linktitle: LINQ_FirstOrDefault
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::IEnumerable::LINQ_FirstOrDefault method. Returns the first element of a sequence, or a default value if the sequence is empty in C++.'
type: docs
weight: 1600
url: /cpp/system.collections.generic/ienumerable/linq_firstordefault/
---
## IEnumerable::LINQ_FirstOrDefault() method


Returns the first element of a sequence, or a default value if the sequence is empty.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault()
```


### ReturnValue

First element in the sequence or default-constructed value if the sequence is empty.

## See Also

* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_FirstOrDefault(std::function\<bool(T)>) method


Returns the first element of the sequence that satisfies a condition or a default value if no such element is found.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault(std::function<bool(T)> predicate)
```


| Parameter | Type | Description |
| --- | --- | --- |
| predicate | std::function\<bool(T)> | A function to test each element for a condition. |

### ReturnValue

default(T) if source is empty or if no element passes the test specified by predicate; otherwise, the first element in source that passes the test specified by predicate.

## See Also

* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
