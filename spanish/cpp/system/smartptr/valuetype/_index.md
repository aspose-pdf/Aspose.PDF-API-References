---
title: "typedef System::SmartPtr::ValueType"
linktitle: "ValueType"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "typedef System::SmartPtr::ValueType. Tipo de almacenamiento del arreglo apuntado. Solo tiene sentido si T es una especialización de System::Array en C++."
type: docs
weight: 4100
url: /es/cpp/system/smartptr/valuetype/
---
## ValueType typedef


Tipo de almacenamiento del arreglo apuntado. Solo tiene sentido si T es una especialización de [System::Array](../../array/).

```cpp
using System::SmartPtr< T >::ValueType =  typename System::Details::SelectType<typename System::Details::ArrayTypeResolver<T>::value_type>::type
```

## Ver también

* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
