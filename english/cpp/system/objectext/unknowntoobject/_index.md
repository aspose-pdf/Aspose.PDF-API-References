---
title: System::ObjectExt::UnknownToObject method
linktitle: UnknownToObject
second_title: Aspose.PDF for C++ API Reference
description: 'System::ObjectExt::UnknownToObject method. Converts unknown type to Object, handling both smart pointer type and value type situations in C++.'
type: docs
weight: 1900
url: /cpp/system/objectext/unknowntoobject/
---
## ObjectExt::UnknownToObject(const T\&) method


Converts unknown type to [Object](../../object/), handling both smart pointer type and value type situations.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(const T &obj)
```


| Parameter | Description |
| --- | --- |
| T | Type to convert to [Object](../../object/). |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) to convert. |

### ReturnValue

Smart pointer to [Object](../../object/) being either converted pointer or boxed value.

## See Also

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::UnknownToObject(T) method


Converts unknown type to [Object](../../object/), handling both smart pointer type and value type situations.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(T obj)
```


| Parameter | Description |
| --- | --- |
| T | Type to convert to [Object](../../object/). |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | T | [Object](../../object/) to convert. |

### ReturnValue

Smart pointer to [Object](../../object/) being either converted pointer or boxed value.

## See Also

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
