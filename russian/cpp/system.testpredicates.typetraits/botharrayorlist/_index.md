---
title: "System::TestPredicates::TypeTraits::BothArrayOrList typedef"
linktitle: "BothArrayOrList"
second_title: "Справочник API Aspose.PDF для C++"
description: "typedef System::TestPredicates::TypeTraits::BothArrayOrList. Проверяет, являются ли оба аргумента типа массивами или списками. Если да, член value устанавливается в true, в противном случае — в false в C++."
type: docs
weight: 300
url: /ru/cpp/system.testpredicates.typetraits/botharrayorlist/
---
## BothArrayOrList typedef


Проверяет, являются ли оба аргумента типа массивами или списками. Если да, член value устанавливается в true, иначе — в false.

```cpp
using System::TestPredicates::TypeTraits::BothArrayOrList =  std::integral_constant<bool, (IsArray<T1>::value || IsList<T1>::value) && (IsArray<T2>::value || IsList<T2>::value)>
```


## См. также

* Namespace [System::TestPredicates::TypeTraits](../)
* Library [Aspose.PDF for C++](../../)
