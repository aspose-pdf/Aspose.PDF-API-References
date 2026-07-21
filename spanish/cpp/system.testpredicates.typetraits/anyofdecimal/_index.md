---
title: "System::TestPredicates::TypeTraits::AnyOfDecimal typedef"
linktitle: "AnyOfDecimal"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::TestPredicates::TypeTraits::AnyOfDecimal typedef. Verifica que al menos uno de los argumentos de tipo sea System::Decimal. Si es así, establece el miembro value en true, de lo contrario es false en C++."
type: docs
weight: 100
url: /es/cpp/system.testpredicates.typetraits/anyofdecimal/
---
## AnyOfDecimal typedef


Verifica que al menos uno de los argumentos de tipo sea [System::Decimal](../../system/decimal/). Si es así, establece el miembro value en true, de lo contrario es false.

```cpp
using System::TestPredicates::TypeTraits::AnyOfDecimal =  std::integral_constant<bool, std::is_same<T1, System::Decimal>::value || std::is_same<T2, System::Decimal>::value>
```


## Ver también

* Namespace [System::TestPredicates::TypeTraits](../)
* Library [Aspose.PDF for C++](../../)
