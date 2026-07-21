---
title: "System::TestPredicates::TypeTraits::AreFPandArithmetic typedef"
linktitle: "AreFPandArithmetic"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::TestPredicates::TypeTraits::AreFPandArithmetic typedef. Verifica que T1 sea aritmético y T2 sea de punto flotante, o viceversa. Si es así, establece el miembro value en true, de lo contrario es false en C++."
type: docs
weight: 200
url: /es/cpp/system.testpredicates.typetraits/arefpandarithmetic/
---
## AreFPandArithmetic typedef


Comprueba que **T1** sea aritmético y **T2** sea de punto flotante, o viceversa. Si es así, establece el miembro value en true, de lo contrario es false.

```cpp
using System::TestPredicates::TypeTraits::AreFPandArithmetic =  std::integral_constant<bool, (std::is_floating_point<T1>::value && std::is_arithmetic<T2>::value) || (std::is_arithmetic<T1>::value && std::is_floating_point<T2>::value) >
```


## Ver también

* Namespace [System::TestPredicates::TypeTraits](../)
* Library [Aspose.PDF for C++](../../)
