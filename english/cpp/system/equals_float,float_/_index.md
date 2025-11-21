---
title: System::Equals< float, float > method
linktitle: Equals< float, float >
second_title: Aspose.PDF for C++ API Reference
description: 'System::Equals< float, float > method. Specialization for single-precision floating point values. Although two floating point NaNs are defined by IEC 60559:1989 to always compare as unequal, the contract for System.Object.Equals, requires that overrides must satisfy the requirements for an equivalence operator. Therefore, System.Double.Equals and System.Single.Equals return True when comparing two NaNs, while the equality operator returns False in that case, as required by the standard in C++.'
type: docs
weight: 18400
url: /cpp/system/equals_float,float_/
---
## System::Equals< float, float > method


Specialization for single-precision floating point values. Although two floating point NaNs are defined by IEC 60559:1989 to always compare as unequal, the contract for [System.Object.Equals](../object/equals/), requires that overrides must satisfy the requirements for an equivalence operator. Therefore, System.Double.Equals and System.Single.Equals return True when comparing two NaNs, while the equality operator returns False in that case, as required by the standard.

```cpp
bool System::Equals<float, float>(const float &a, const float &b)
```


| Parameter | Type | Description |
| --- | --- | --- |
| a | const float\& | The first comparand |
| b | const float\& | The second comparand |

### ReturnValue

True if both values are NaN or are equal, otherwise - false

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
