---
title: System::EnumValuesBase::ToObject method
linktitle: ToObject
second_title: Aspose.PDF for C++ API Reference
description: 'System::EnumValuesBase::ToObject method. Converts the specified object with an integer value to an enumeration member in C++.'
type: docs
weight: 500
url: /cpp/system/enumvaluesbase/toobject/
---
## EnumValuesBase::ToObject(const TypeInfo\&, const SharedPtr\<Object\>\&) method


Converts the specified object with an integer value to an enumeration member.

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, const SharedPtr<Object> &value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| type | const TypeInfo\& | The enumeration type to return. |
| value | const SharedPtr\<Object\>\& | The value convert to an enumeration member. |

### ReturnValue

An enumeration object whose value is value.

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [TypeInfo](../../typeinfo/)
* Class [EnumValuesBase](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## EnumValuesBase::ToObject(const TypeInfo\&, uint64_t) method


Converts the specified 64-bit unsigned integer value to an enumeration member.

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, uint64_t value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| type | const TypeInfo\& | The enumeration type to return. |
| value | uint64_t | The value to convert to an enumeration member. |

### ReturnValue

An instance of the enumeration set to value.

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [TypeInfo](../../typeinfo/)
* Class [EnumValuesBase](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
