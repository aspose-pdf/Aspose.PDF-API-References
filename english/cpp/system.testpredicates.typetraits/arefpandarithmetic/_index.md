---
title: System::TestPredicates::TypeTraits::AreFPandArithmetic typedef
linktitle: AreFPandArithmetic
second_title: Aspose.PDF for C++ API Reference
description: 'System::TestPredicates::TypeTraits::AreFPandArithmetic typedef. Checks that T1 is arithmetic and T2 is floating point, or vice versa. If so, sets value member to true, otherwise it is false in C++.'
type: docs
weight: 200
url: /cpp/system.testpredicates.typetraits/arefpandarithmetic/
---
## AreFPandArithmetic typedef


Checks that **T1** is arithmetic and **T2** is floating point, or vice versa. If so, sets value member to true, otherwise it is false.

```cpp
using System::TestPredicates::TypeTraits::AreFPandArithmetic =  std::integral_constant<bool, (std::is_floating_point<T1>::value && std::is_arithmetic<T2>::value) || (std::is_arithmetic<T1>::value && std::is_floating_point<T2>::value) >
```


## See Also

* Namespace [System::TestPredicates::TypeTraits](../)
* Library [Aspose.PDF for C++](../../)
