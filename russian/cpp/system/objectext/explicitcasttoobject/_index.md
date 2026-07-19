---
title: "Метод System::ObjectExt::ExplicitCastToObject"
linktitle: "ExplicitCastToObject"
second_title: "Справочник API Aspose.PDF для C++"
description: "Как использовать метод ExplicitCastToObject класса System::ObjectExt в C++."
type: docs
weight: 900
url: /ru/cpp/system/objectext/explicitcasttoobject/
---
## ObjectExt::ExplicitCastToObject(const T\&) method




```cpp
template<typename T> static std::enable_if<System::IsBoxable<T>::value, System::SharedPtr<System::Object>>::type System::ObjectExt::ExplicitCastToObject(const T &value)
```

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ExplicitCastToObject(const T\&) method




```cpp
template<typename T> static std::enable_if<System::IsSmartPtr<T>::value, System::SharedPtr<System::Object>>::type System::ObjectExt::ExplicitCastToObject(const T &value)
```

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
