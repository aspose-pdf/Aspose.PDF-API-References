---
title: "System::TestPredicates::TypeTraits::IsList typedef"
linktitle: "IsList"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::TestPredicates::TypeTraits::IsList typedef. Kontrollerar om typen är en System::Collections::Generic::List-specialisering. Om så är fallet sätts värdemedlemmen till true, annars sätts den till false i C++."
type: docs
weight: 600
url: /sv/cpp/system.testpredicates.typetraits/islist/
---
## IsList typedef


Kontrollerar om typen är en [System::Collections::Generic::List](../../system.collections.generic/list/) specialisering. Om så är fallet sätts värdemedlemmen till true, annars är den false.

```cpp
using System::TestPredicates::TypeTraits::IsList =  std::is_same<T, System::Collections::Generic::List<typename T::ValueType>>
```


## Se även

* Namespace [System::TestPredicates::TypeTraits](../)
* Library [Aspose.PDF for C++](../../)
