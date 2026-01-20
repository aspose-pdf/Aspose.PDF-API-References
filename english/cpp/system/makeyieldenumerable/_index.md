---
title: System::MakeYieldEnumerable method
linktitle: MakeYieldEnumerable
second_title: Aspose.PDF for C++ API Reference
description: 'System::MakeYieldEnumerable method. Creates an IEnumerable from a yield function in C++.'
type: docs
weight: 25300
url: /cpp/system/makeyieldenumerable/
---
## System::MakeYieldEnumerable method


Creates an IEnumerable from a yield function.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerable<T>> System::MakeYieldEnumerable(const Details::YieldFunction<T> &fnc)
```


| Parameter | Description |
| --- | --- |
| T | The type of elements in the sequence |

| Parameter | Type | Description |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | The yield function to execute |

### ReturnValue

Shared pointer to the IEnumerable

## See Also

* Typedef [SharedPtr](../sharedptr/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
