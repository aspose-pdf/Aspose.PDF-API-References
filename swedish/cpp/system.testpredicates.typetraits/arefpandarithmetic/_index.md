---
title: "System::TestPredicates::TypeTraits::AreFPandArithmetic typedef"
linktitle: "AreFPandArithmetic"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::TestPredicates::TypeTraits::AreFPandArithmetic typedef. Kontrollerar att T1 är aritmetisk och T2 är flyttal, eller tvärtom. Om så är fallet sätts värdemedlemmen till true, annars är den false i C++."
type: docs
weight: 200
url: /sv/cpp/system.testpredicates.typetraits/arefpandarithmetic/
---
## AreFPandArithmetic typedef


Kontrollerar att **T1** är aritmetisk och **T2** är flyttal, eller omvänt. Om så är fallet sätts värdemedlemmen till true, annars är den false.

```cpp
using System::TestPredicates::TypeTraits::AreFPandArithmetic =  std::integral_constant<bool, (std::is_floating_point<T1>::value && std::is_arithmetic<T2>::value) || (std::is_arithmetic<T1>::value && std::is_floating_point<T2>::value) >
```


## Se även

* Namespace [System::TestPredicates::TypeTraits](../)
* Library [Aspose.PDF for C++](../../)
