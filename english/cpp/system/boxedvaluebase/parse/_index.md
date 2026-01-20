---
title: System::BoxedValueBase::Parse method
linktitle: Parse
second_title: Aspose.PDF for C++ API Reference
description: 'System::BoxedValueBase::Parse method. Boxes the value of enumeration constant of the specified enumeration with the specified name in C++.'
type: docs
weight: 500
url: /cpp/system/boxedvaluebase/parse/
---
## BoxedValueBase::Parse(const TypeInfo\&, const String\&) method


Boxes the value of enumeration constant of the specified enumeration with the specified name.

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str)
```


| Parameter | Type | Description |
| --- | --- | --- |
| type | const TypeInfo\& | Specifies the type of the enumeration |
| str | const String\& | The name of the enumeration constant, value of which is to be boxed |

### ReturnValue

A shared pointer to the object representing boxed value of the specified enumeration constant

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [TypeInfo](../../typeinfo/)
* Class [String](../../string/)
* Class [BoxedValueBase](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## BoxedValueBase::Parse(const TypeInfo\&, const String\&, bool) method


Boxes the value of enumeration constant of the specified enumeration with the specified name. A parameter specifies if the case should be ignored when interpreting the string specifying the name of the enumeration constant.

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```


| Parameter | Type | Description |
| --- | --- | --- |
| type | const TypeInfo\& | Specifies the type of the enumeration |
| str | const String\& | The name of the enumeration constant, value of which is to be boxed |
| ignoreCase | bool | Specifies if case should be ignored when interpreting the string representing the name of the enumeration constant |

### ReturnValue

A shared pointer to the object representing boxed value of the specified enumeration constant

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [TypeInfo](../../typeinfo/)
* Class [String](../../string/)
* Class [BoxedValueBase](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
