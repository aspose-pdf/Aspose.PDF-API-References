---
title: System::Collections::Generic::IEnumerable::LINQ_Zip method
linktitle: LINQ_Zip
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::IEnumerable::LINQ_Zip method. Applies a specified function to the corresponding elements of two sequences, producing a sequence of the results in C++.'
type: docs
weight: 3900
url: /cpp/system.collections.generic/ienumerable/linq_zip/
---
## IEnumerable::LINQ_Zip(SharedPtr\<IEnumerable\<TSecond\>\>, const Func\<T, TSecond, TResult\>\&) method


Applies a specified function to the corresponding elements of two sequences, producing a sequence of the results.

```cpp
template<typename TSecond,typename TResult> SharedPtr<IEnumerable<TResult>> System::Collections::Generic::IEnumerable<T>::LINQ_Zip(SharedPtr<IEnumerable<TSecond>> second, const Func<T, TSecond, TResult> &resultSelector)
```


| Parameter | Description |
| --- | --- |
| TSecond | The type of the elements of the second input sequence. |
| TResult | The type of the elements of the result sequence. |

| Parameter | Type | Description |
| --- | --- | --- |
| second | SharedPtr\<IEnumerable\<TSecond\>\> | The second sequence to merge. |
| resultSelector | const Func\<T, TSecond, TResult\>\& | A function that specifies how to merge the elements from the two sequences. |

### ReturnValue

An [System::Collections::Generic::IEnumerable](../) that contains merged elements of two input sequences.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_Zip(SharedPtr\<IEnumerable\<TSecond\>\>, const Func\<TFirst, TSecond, TResult\>\&) method




```cpp
template<typename TSecond,typename TResult> SharedPtr<IEnumerable<TResult>> System::Collections::Generic::IEnumerable<T>::LINQ_Zip(SharedPtr<IEnumerable<TSecond>> second, const Func<TFirst, TSecond, TResult> &resultSelector)
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
