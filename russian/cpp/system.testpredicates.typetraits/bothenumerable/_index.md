---
title: "System::TestPredicates::TypeTraits::BothEnumerable typedef"
linktitle: "BothEnumerable"
second_title: "Справочник API Aspose.PDF для C++"
description: "typedef System::TestPredicates::TypeTraits::BothEnumerable. Проверяет, являются ли оба аргумента типа IEnumerable. Если да, член value устанавливается в true, в противном случае — в false в C++."
type: docs
weight: 400
url: /ru/cpp/system.testpredicates.typetraits/bothenumerable/
---
## BothEnumerable typedef


Проверяет, являются ли оба аргумента типа IEnumerable. Если да, член value устанавливается в true, иначе — в false.

```cpp
using System::TestPredicates::TypeTraits::BothEnumerable =  std::integral_constant<bool, IsEnumerable<T1>::value && IsEnumerable<T2>::value>
```


## См. также

* Namespace [System::TestPredicates::TypeTraits](../)
* Library [Aspose.PDF for C++](../../)
