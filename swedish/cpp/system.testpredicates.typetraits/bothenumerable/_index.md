---
title: "System::TestPredicates::TypeTraits::BothEnumerable typedef"
linktitle: "BothEnumerable"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::TestPredicates::TypeTraits::BothEnumerable typedef. Kontrollerar om båda typargumenten är IEnumerable. Om så är fallet sätts värdemedlemmen till true, annars sätts den till false i C++."
type: docs
weight: 400
url: /sv/cpp/system.testpredicates.typetraits/bothenumerable/
---
## BothEnumerable typedef


Kontrollerar om båda typargumenten är IEnumerable. Om så är fallet sätts värdemedlemmen till true, annars sätts den till false.

```cpp
using System::TestPredicates::TypeTraits::BothEnumerable =  std::integral_constant<bool, IsEnumerable<T1>::value && IsEnumerable<T2>::value>
```


## Se även

* Namespace [System::TestPredicates::TypeTraits](../)
* Library [Aspose.PDF for C++](../../)
