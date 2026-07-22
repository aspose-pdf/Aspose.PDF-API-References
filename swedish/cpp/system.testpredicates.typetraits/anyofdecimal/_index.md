---
title: "System::TestPredicates::TypeTraits::AnyOfDecimal typedef"
linktitle: "AnyOfDecimal"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::TestPredicates::TypeTraits::AnyOfDecimal typedef. Kontrollerar att minst ett av typargumenten är System::Decimal. Om så är fallet sätts värdemedlemmen till true, annars är den false i C++."
type: docs
weight: 100
url: /sv/cpp/system.testpredicates.typetraits/anyofdecimal/
---
## AnyOfDecimal typedef


Kontrollerar att minst ett av typargumenten är [System::Decimal](../../system/decimal/). Om så är fallet sätts värdemedlemmen till true, annars är den false.

```cpp
using System::TestPredicates::TypeTraits::AnyOfDecimal =  std::integral_constant<bool, std::is_same<T1, System::Decimal>::value || std::is_same<T2, System::Decimal>::value>
```


## Se även

* Namespace [System::TestPredicates::TypeTraits](../)
* Library [Aspose.PDF for C++](../../)
