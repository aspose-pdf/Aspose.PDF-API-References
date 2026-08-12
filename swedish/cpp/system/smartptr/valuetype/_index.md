---
title: "System::SmartPtr::ValueType typedef"
linktitle: "ValueType"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::SmartPtr::ValueType typedef. Lagringstyp för pekad array. Endast meningsfull om T är en specialisering av System::Array i C++."
type: docs
weight: 4100
url: /sv/cpp/system/smartptr/valuetype/
---
## ValueType typedef


Lagringstyp för pekad array. Endast meningsfull om T är en specialisering av [System::Array](../../array/).

```cpp
using System::SmartPtr< T >::ValueType =  typename System::Details::SelectType<typename System::Details::ArrayTypeResolver<T>::value_type>::type
```

## Se även

* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
