---
title: System::Attribute::GetCustomAttribute method
linktitle: GetCustomAttribute
second_title: Aspose.PDF for C++ API Reference
description: 'System::Attribute::GetCustomAttribute method. Returns a custom attribute of a specified type appllied to specified type in C++.'
type: docs
weight: 100
url: /cpp/system/attribute/getcustomattribute/
---
## Attribute::GetCustomAttribute method


Returns a custom attribute of a specified type appllied to specified type.

```cpp
static Object::ptr System::Attribute::GetCustomAttribute(const TypeInfo &type, const TypeInfo &attributeType)
```


| Parameter | Type | Description |
| --- | --- | --- |
| type | const TypeInfo\& | Type attribute of which is retrieved |
| attributeType | const TypeInfo\& | Type of the attribute to retrieve |

### ReturnValue

A retrieved attribute or null if specified type does not have attribute of specified type.

## See Also

* Typedef [ptr](../../object/ptr/)
* Class [TypeInfo](../../typeinfo/)
* Class [Attribute](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
