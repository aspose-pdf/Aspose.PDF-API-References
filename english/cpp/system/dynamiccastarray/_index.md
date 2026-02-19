---
title: System::DynamicCastArray method
linktitle: DynamicCastArray
second_title: Aspose.PDF for C++ API Reference
description: 'System::DynamicCastArray method. Performs casting of elements of the specified array to different type in C++.'
type: docs
weight: 18000
url: /cpp/system/dynamiccastarray/
---
## System::DynamicCastArray method


Performs casting of elements of the specified array to different type.

```cpp
template<class To,class From> SharedPtr<Array<To>> System::DynamicCastArray(const SharedPtr<Array<From>> &from)
```


| Parameter | Description |
| --- | --- |
| To | The type to cast the elements of the specified array to |
| From | The type of elements of the elements of the arry elements of which to cast |

| Parameter | Type | Description |
| --- | --- | --- |
| from | const SharedPtr\<Array\<From\>\>\& | Shared pointer to the array containing the elements to cast |

### ReturnValue

A pointer to a new array containing elements of type **To** equivalent to the elements of **from**

## Deprecated
Added for backward compatibility. Use ExplicitCast instead. 

## See Also

* Typedef [SharedPtr](../sharedptr/)
* Class [Array](../array/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
