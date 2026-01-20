---
title: System::Runtime::Serialization::FormatterConverter::Convert method
linktitle: Convert
second_title: Aspose.PDF for C++ API Reference
description: 'System::Runtime::Serialization::FormatterConverter::Convert method. RTTI information in C++.'
type: docs
weight: 100
url: /cpp/system.runtime.serialization/formatterconverter/convert/
---
## FormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) method


RTTI information.

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | System::SharedPtr\<Object\> | The object to be converted. |
| type | const TypeInfo\& | The [System::TypeInfo](../../../system/typeinfo/) into which value is to be converted. |

### ReturnValue

The converted value.
## Remarks


Converts a value to the given [System::TypeInfo](../../../system/typeinfo/). 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [FormatterConverter](../)
* Namespace [System::Runtime::Serialization](../../)
* Library [Aspose.PDF for C++](../../../)
## FormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) method


Converts a value to the given [System::TypeCode](../../../system/typecode/).

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | System::SharedPtr\<Object\> | The object to be converted. |
| typeCode | TypeCode | The [System::TypeCode](../../../system/typecode/) into which value is to be converted. |

### ReturnValue

The converted value.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Enum [TypeCode](../../../system/typecode/)
* Class [FormatterConverter](../)
* Namespace [System::Runtime::Serialization](../../)
* Library [Aspose.PDF for C++](../../../)
