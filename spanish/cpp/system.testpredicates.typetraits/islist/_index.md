---
title: "System::TestPredicates::TypeTraits::IsList typedef"
linktitle: "IsList"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::TestPredicates::TypeTraits::IsList typedef. Verifica si el tipo es una especialización de System::Collections::Generic::List. Si es así, el miembro value se establece en true, de lo contrario se establece en false en C++."
type: docs
weight: 600
url: /es/cpp/system.testpredicates.typetraits/islist/
---
## IsList typedef


Verifica si el tipo es una especialización de [System::Collections::Generic::List](../../system.collections.generic/list/). Si es así, el miembro value se establece en true, de lo contrario es false.

```cpp
using System::TestPredicates::TypeTraits::IsList =  std::is_same<T, System::Collections::Generic::List<typename T::ValueType>>
```


## Ver también

* Namespace [System::TestPredicates::TypeTraits](../)
* Library [Aspose.PDF for C++](../../)
