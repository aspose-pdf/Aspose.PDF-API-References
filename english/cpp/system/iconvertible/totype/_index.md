---
title: System::IConvertible::ToType method
linktitle: ToType
second_title: Aspose.PDF for C++ API Reference
description: 'System::IConvertible::ToType method. Converts the value of this instance to a System::Object of the specified System::Type that has an equivalent value, using the specified culture-specific formatting information in C++.'
type: docs
weight: 1400
url: /cpp/system/iconvertible/totype/
---
## IConvertible::ToType method


Converts the value of this instance to a [System::Object](../../object/) of the specified System::Type that has an equivalent value, using the specified culture-specific formatting information.

```cpp
virtual System::SharedPtr<System::Object> System::IConvertible::ToType(const TypeInfo &conversionType, System::SharedPtr<System::IFormatProvider> provider)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| conversionType | const TypeInfo\& | The System::Type to which the value of this instance is converted. |
| provider | System::SharedPtr\<System::IFormatProvider\> | A [System::IFormatProvider](../../iformatprovider/) interface implementation that supplies culture-specific formatting information. |

### ReturnValue

A [System::Object](../../object/) instance of type conversionType whose value is equivalent to the value of this instance.

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [TypeInfo](../../typeinfo/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [IConvertible](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
