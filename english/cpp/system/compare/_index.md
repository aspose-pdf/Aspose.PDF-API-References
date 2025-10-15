---
title: System::Compare method
linktitle: Compare
second_title: Aspose.PDF for C++ API Reference
description: 'System::Compare method. Compares two values in C++.'
type: docs
weight: 15700
url: /cpp/system/compare/
---
## System::Compare(const TA\&, const TB\&) method


Compares two values.

```cpp
template<typename TA,typename TB> std::enable_if_t<!std::is_floating_point<TA>::value &&!std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```


| Parameter | Description |
| --- | --- |
| TA | The type of the first comparand |
| TB | The type of the second comparand |

| Parameter | Type | Description |
| --- | --- | --- |
| a | const TA\& | The first comparand |
| b | const TB\& | The second comparand |

### ReturnValue

-1 if **a** compares less than **b**; 0 if the values are equal; 1 if **a** compares greater than **b**

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::Compare(const TA\&, const TB\&) method


Compares two floating point values.

```cpp
template<typename TA,typename TB> std::enable_if_t<std::is_floating_point<TA>::value &&std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```


| Parameter | Description |
| --- | --- |
| TA | The type of the first comparand |
| TB | The type of the second comparand |

| Parameter | Type | Description |
| --- | --- | --- |
| a | const TA\& | The first comparand |
| b | const TB\& | The second comparand |

### ReturnValue

-1 if **a** compares less than **b**; 0 if the values are equal; 1 if **a** compares greater than **b**

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
