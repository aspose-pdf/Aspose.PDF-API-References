---
title: System::Drawing::ImageFormatConverter::ConvertTo method
linktitle: ConvertTo
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::ImageFormatConverter::ConvertTo method. Converts object to specific type in C++.'
type: docs
weight: 300
url: /cpp/system.drawing/imageformatconverter/convertto/
---
## ImageFormatConverter::ConvertTo method


Converts object to specific type.

```cpp
SharedPtr<Object> System::Drawing::ImageFormatConverter::ConvertTo(const SharedPtr<ComponentModel::ITypeDescriptorContext> &context, const SharedPtr<Globalization::CultureInfo> &culture, const SharedPtr<Object> &value, const TypeInfo &destinationType) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| context | const SharedPtr\<ComponentModel::ITypeDescriptorContext\>\& | [Object](../../../system/object/) conversion context information. |
| culture | const SharedPtr\<Globalization::CultureInfo\>\& | Culture to use when converting objects. |
| value | const SharedPtr\<Object\>\& | [Object](../../../system/object/) to convert. |
| destinationType | const TypeInfo\& | Type to convert to. |

### ReturnValue

Converted object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [ImageFormatConverter](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
