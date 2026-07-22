---
title: "System::TestPredicates::TypeTraits::BothArrayOrList typedef"
linktitle: "BothArrayOrList"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::TestPredicates::TypeTraits::BothArrayOrList typedef. Kontrollerar om båda typargumenten är arrayer eller listor. Om så är fallet sätts värdemedlemmen till true, annars sätts den till false i C++."
type: docs
weight: 300
url: /sv/cpp/system.testpredicates.typetraits/botharrayorlist/
---
## BothArrayOrList typedef


Kontrollerar om båda typargumenten är arrayer eller listor. Om så är fallet sätts värdemedlemmen till true, annars sätts den till false.

```cpp
using System::TestPredicates::TypeTraits::BothArrayOrList =  std::integral_constant<bool, (IsArray<T1>::value || IsList<T1>::value) && (IsArray<T2>::value || IsList<T2>::value)>
```


## Se även

* Namespace [System::TestPredicates::TypeTraits](../)
* Library [Aspose.PDF for C++](../../)
