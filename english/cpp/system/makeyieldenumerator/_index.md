---
title: System::MakeYieldEnumerator method
linktitle: MakeYieldEnumerator
second_title: Aspose.PDF for C++ API Reference
description: 'System::MakeYieldEnumerator method. Creates an IEnumerator from a yield function in C++.'
type: docs
weight: 24200
url: /cpp/system/makeyieldenumerator/
---
## System::MakeYieldEnumerator method


Creates an IEnumerator from a yield function.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerator<T>> System::MakeYieldEnumerator(const Details::YieldFunction<T> &fnc)
```


| Parameter | Description |
| --- | --- |
| T | The type of elements in the sequence |

| Parameter | Type | Description |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | The yield function to execute |

### ReturnValue

Shared pointer to the IEnumerator

## See Also

* Typedef [SharedPtr](../sharedptr/)
* Class [IEnumerator](../../system.collections.generic/ienumerator/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
