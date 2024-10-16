---
title: System::EnumValues::GetValueOf method
linktitle: GetValueOf
second_title: Aspose.PDF for C++ API Reference
description: 'System::EnumValues::GetValueOf method. Returns boxed value of the enum constant with the specified name in C++.'
type: docs
weight: 300
url: /cpp/system/enumvalues/getvalueof/
---
## EnumValues::GetValueOf method


Returns boxed value of the enum constant with the specified name.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(const String &str, bool ignoreCase) const override
```


| Parameter | Type | Description |
| --- | --- | --- |
| str | const String\& | The name of the enum constant |
| ignoreCase | bool | Specifeis if the case should be ignored when interpreting the name of the enum constant |

### ReturnValue

A boxed value of the enum constant whose name is specified in **str**.

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [String](../../string/)
* Class [EnumValues](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
