---
title: System::Collections::Generic::DefaultComparer::Compare method
linktitle: Compare
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::DefaultComparer::Compare method. RTTI information in C++.'
type: docs
weight: 100
url: /cpp/system.collections.generic/defaultcomparer/compare/
---
## DefaultComparer::Compare method


RTTI information.

```cpp
virtual int System::Collections::Generic::DefaultComparer<T>::Compare(typename ThisType::args_type x, typename ThisType::args_type y) const override
```


| Parameter | Type | Description |
| --- | --- | --- |
| x | typename ThisType::args_type | LHS operand. |
| y | typename ThisType::args_type | RHS operand. |

### ReturnValue

Negative value if **x** is less than **y**, 0 if operands are equal and positive value otherwise.
## Remarks


Actual data comparison. 
## See Also

* Typedef [args_type](../../icomparer/args_type/)
* Class [DefaultComparer](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
