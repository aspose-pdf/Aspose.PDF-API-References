---
title: System::TestPredicates::TypeTraits::AnyOfDecimal typedef
linktitle: AnyOfDecimal
second_title: Aspose.PDF for C++ API Reference
description: 'System::TestPredicates::TypeTraits::AnyOfDecimal typedef. Checks that at least one of type arguments is System::Decimal. If so, sets value member to true, otherwise it is false in C++.'
type: docs
weight: 100
url: /cpp/system.testpredicates.typetraits/anyofdecimal/
---
## AnyOfDecimal typedef


Checks that at least one of type arguments is [System::Decimal](../../system/decimal/). If so, sets value member to true, otherwise it is false.

```cpp
using System::TestPredicates::TypeTraits::AnyOfDecimal =  std::integral_constant<bool, std::is_same<T1, System::Decimal>::value || std::is_same<T2, System::Decimal>::value>
```


## See Also

* Namespace [System::TestPredicates::TypeTraits](../)
* Library [Aspose.PDF for C++](../../)
