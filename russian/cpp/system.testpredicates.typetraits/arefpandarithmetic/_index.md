---
title: "System::TestPredicates::TypeTraits::AreFPandArithmetic typedef"
linktitle: "AreFPandArithmetic"
second_title: "Справочник API Aspose.PDF для C++"
description: "typedef System::TestPredicates::TypeTraits::AreFPandArithmetic. Проверяет, что T1 является арифметическим типом, а T2 — типом с плавающей точкой, или наоборот. Если да, член value устанавливается в true, в противном случае — false в C++."
type: docs
weight: 200
url: /ru/cpp/system.testpredicates.typetraits/arefpandarithmetic/
---
## AreFPandArithmetic typedef


Проверяет, что **T1** является арифметическим, а **T2** — типом с плавающей точкой, или наоборот. Если да, устанавливает член value в true, иначе — в false.

```cpp
using System::TestPredicates::TypeTraits::AreFPandArithmetic =  std::integral_constant<bool, (std::is_floating_point<T1>::value && std::is_arithmetic<T2>::value) || (std::is_arithmetic<T1>::value && std::is_floating_point<T2>::value) >
```


## См. также

* Namespace [System::TestPredicates::TypeTraits](../)
* Library [Aspose.PDF for C++](../../)
