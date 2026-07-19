---
title: "System::TestPredicates::TypeTraits::IsList typedef"
linktitle: "IsList"
second_title: "Справочник API Aspose.PDF для C++"
description: "typedef System::TestPredicates::TypeTraits::IsList. Проверяет, является ли тип специализацией System::Collections::Generic::List. Если да, член value устанавливается в true, в противном случае — в false в C++."
type: docs
weight: 600
url: /ru/cpp/system.testpredicates.typetraits/islist/
---
## IsList typedef


Проверяет, является ли тип специализацией [System::Collections::Generic::List](../../system.collections.generic/list/). Если да, член value устанавливается в true, в противном случае — в false.

```cpp
using System::TestPredicates::TypeTraits::IsList =  std::is_same<T, System::Collections::Generic::List<typename T::ValueType>>
```


## См. также

* Namespace [System::TestPredicates::TypeTraits](../)
* Library [Aspose.PDF for C++](../../)
