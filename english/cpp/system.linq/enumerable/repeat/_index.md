---
title: System::Linq::Enumerable::Repeat method
linktitle: Repeat
second_title: Aspose.PDF for C++ API Reference
description: 'System::Linq::Enumerable::Repeat method. Generates a sequence that contains one repeated value in C++.'
type: docs
weight: 300
url: /cpp/system.linq/enumerable/repeat/
---
## Enumerable::Repeat method


Generates a sequence that contains one repeated value.

```cpp
template<typename TResult> static SharedPtr<Collections::Generic::IEnumerable<TResult>> System::Linq::Enumerable::Repeat(const TResult &element, int32_t count)
```


| Parameter | Description |
| --- | --- |
| T | The type of the value to be repeated in the result sequence. |

| Parameter | Type | Description |
| --- | --- | --- |
| element | const TResult\& | The value to be repeated. |
| count | int32_t | The number of times to repeat the value in the generated sequence. |

### ReturnValue

An [System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/) that contains a repeated value.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [Enumerable](../)
* Namespace [System::Linq](../../)
* Library [Aspose.PDF for C++](../../../)
