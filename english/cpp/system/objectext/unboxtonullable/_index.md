---
title: System::ObjectExt::UnboxToNullable method
linktitle: UnboxToNullable
second_title: Aspose.PDF for C++ API Reference
description: 'System::ObjectExt::UnboxToNullable method. Unboxes object to nullable type in C++.'
type: docs
weight: 1600
url: /cpp/system/objectext/unboxtonullable/
---
## ObjectExt::UnboxToNullable method


Unboxes object to nullable type.

```cpp
template<class T> static Nullable<T> System::ObjectExt::UnboxToNullable(const SmartPtr<Object> &obj, bool safe=true)
```


| Parameter | Description |
| --- | --- |
| T | Destination type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) to unbox. |
| safe | bool | If true, return nullptr on failure, otherwise throw InvalidCastException. |

### ReturnValue

Unboxed nullable value (could be null).

## See Also

* Class [Nullable](../../nullable/)
* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
