---
title: System::ObjectExt::ObjectToUnknown method
linktitle: ObjectToUnknown
second_title: Aspose.PDF for C++ API Reference
description: 'System::ObjectExt::ObjectToUnknown method. Converts Object to unknown type, handling both smart pointer type and bpxed value situations in C++.'
type: docs
weight: 1300
url: /cpp/system/objectext/objecttounknown/
---
## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) method


Converts [Object](../../object/) to unknown type, handling both smart pointer type and bpxed value situations.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```


| Parameter | Description |
| --- | --- |
| T | Type to convert [Object](../../object/) to. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | SmartPtr\<Object\> | [Object](../../object/) to convert. |

### ReturnValue

Either unboxed value or converted pointer.

## See Also

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) method


Converts [Object](../../object/) to unknown type, handling both smart pointer type and boxed value situations.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```


| Parameter | Description |
| --- | --- |
| T | Type to convert [Object](../../object/) to. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | SmartPtr\<Object\> | [Object](../../object/) to convert. |

### ReturnValue

Either unboxed value or converted pointer.

## See Also

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
