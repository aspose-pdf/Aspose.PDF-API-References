---
title: System::ObjectExt::ExplicitCastToObject method
linktitle: ExplicitCastToObject
second_title: Aspose.PDF for C++ API Reference
description: 'How to use ExplicitCastToObject method of System::ObjectExt class in C++.'
type: docs
weight: 900
url: /cpp/system/objectext/explicitcasttoobject/
---
## ObjectExt::ExplicitCastToObject(const T\&) method




```cpp
template<typename T> static std::enable_if<System::IsBoxable<T>::value, System::SharedPtr<System::Object>>::type System::ObjectExt::ExplicitCastToObject(const T &value)
```

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ExplicitCastToObject(const T\&) method




```cpp
template<typename T> static std::enable_if<System::IsSmartPtr<T>::value, System::SharedPtr<System::Object>>::type System::ObjectExt::ExplicitCastToObject(const T &value)
```

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
