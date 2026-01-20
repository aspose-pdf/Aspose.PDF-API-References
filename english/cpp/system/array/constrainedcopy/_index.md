---
title: System::Array::ConstrainedCopy method
linktitle: ConstrainedCopy
second_title: Aspose.PDF for C++ API Reference
description: 'System::Array::ConstrainedCopy method. Copies a range of elements from an System.Array starting at the specified source in C++.'
type: docs
weight: 4700
url: /cpp/system/array/constrainedcopy/
---
## Array::ConstrainedCopy method


Copies a range of elements from an [System.Array](../) starting at the specified source.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::ConstrainedCopy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


| Parameter | Description |
| --- | --- |
| SrcType | Type of elements in source array |
| DstType | Type of elements in destination array |

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | const ArrayPtr\<SrcType\>\& | Source array |
| srcIndex | int64_t | Index in the source array designating the beginning of the range of items to copy |
| dstArray | const ArrayPtr\<DstType\>\& | Destination array |
| dstIndex | int64_t | Index in destination array to start inserting copied items at |
| count | int64_t | The number of elements to copy |
## Remarks


TEMPORARY RAW IMPLEMENTATION WITHOUT ANY UNDONES! 
## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
