---
title: "System::TestPredicates::TypeTraits::AnyOfDecimal typedef"
linktitle: "AnyOfDecimal"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::TestPredicates::TypeTraits::AnyOfDecimal typedef. Проверяет, что хотя бы один из типовых аргументов является System::Decimal. Если да, устанавливает член value в true, иначе — false в C++."
type: docs
weight: 100
url: /ru/cpp/system.testpredicates.typetraits/anyofdecimal/
---
## AnyOfDecimal typedef


Проверяет, что хотя бы один из типовых аргументов является [System::Decimal](../../system/decimal/). Если да, устанавливает член value в true, иначе — false.

```cpp
using System::TestPredicates::TypeTraits::AnyOfDecimal =  std::integral_constant<bool, std::is_same<T1, System::Decimal>::value || std::is_same<T2, System::Decimal>::value>
```


## См. также

* Namespace [System::TestPredicates::TypeTraits](../)
* Library [Aspose.PDF for C++](../../)
