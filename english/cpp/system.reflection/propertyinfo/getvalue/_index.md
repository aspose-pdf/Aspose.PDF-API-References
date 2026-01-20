---
title: System::Reflection::PropertyInfo::GetValue method
linktitle: GetValue
second_title: Aspose.PDF for C++ API Reference
description: 'System::Reflection::PropertyInfo::GetValue method. Gets property value from specific object in C++.'
type: docs
weight: 400
url: /cpp/system.reflection/propertyinfo/getvalue/
---
## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>) method


Gets property value from specific object.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj)
```


| Parameter | Type | Description |
| --- | --- | --- |
| obj | System::SharedPtr\<System::Object\> | [Object](../../../system/object/) to read property from. |

### ReturnValue

Value of specified property for specified object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) method


Gets property value from specific object.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```


| Parameter | Type | Description |
| --- | --- | --- |
| obj | System::SharedPtr\<System::Object\> | [Object](../../../system/object/) to read property from. |
| indexer | System::ArrayPtr\<System::SharedPtr\<System::Object\>\> | These are optional index values for indexed properties. For non-indexed properties, this value should be null. |

### ReturnValue

Value of specified property for specified object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.PDF for C++](../../../)
