---
title: System::Drawing::FontConverter::ConvertTo method
linktitle: ConvertTo
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::FontConverter::ConvertTo method. Converts object to specific type in C++.'
type: docs
weight: 200
url: /cpp/system.drawing/fontconverter/convertto/
---
## FontConverter::ConvertTo method


Converts object to specific type.

```cpp
System::SharedPtr<System::Object> System::Drawing::FontConverter::ConvertTo(const System::SharedPtr<ComponentModel::ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| context | const System::SharedPtr\<ComponentModel::ITypeDescriptorContext\>\& | [Object](../../../system/object/) conversion context information. |
| culture | const System::SharedPtr\<System::Globalization::CultureInfo\>\& | Culture to use when converting objects. |
| value | const System::SharedPtr\<System::Object\>\& | An object to convert. |
| destinationType | const System::TypeInfo\& | Type to convert to. |

### ReturnValue

Converted object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [FontConverter](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
