---
title: "System::TestPredicates::TypeTraits::BothArrayOrList typedef"
linktitle: "BothArrayOrList"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::TestPredicates::TypeTraits::BothArrayOrList typedef. Verifica si ambos argumentos de tipo son matrices o listas. Si es así, el miembro value se establece en true, de lo contrario se establece en false en C++."
type: docs
weight: 300
url: /es/cpp/system.testpredicates.typetraits/botharrayorlist/
---
## BothArrayOrList typedef


Comprueba si ambos argumentos de tipo son arreglos o listas. Si es así, el miembro value se establece en true, de lo contrario se establece en false.

```cpp
using System::TestPredicates::TypeTraits::BothArrayOrList =  std::integral_constant<bool, (IsArray<T1>::value || IsList<T1>::value) && (IsArray<T2>::value || IsList<T2>::value)>
```


## Ver también

* Namespace [System::TestPredicates::TypeTraits](../)
* Library [Aspose.PDF for C++](../../)
