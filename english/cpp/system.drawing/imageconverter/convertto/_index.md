---
title: System::Drawing::ImageConverter::ConvertTo method
linktitle: ConvertTo
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::ImageConverter::ConvertTo method. Converts object to specific type in C++.'
type: docs
weight: 200
url: /cpp/system.drawing/imageconverter/convertto/
---
## ImageConverter::ConvertTo(const System::SharedPtr\<System::ComponentModel::ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) method


Converts object to specific type.

```cpp
System::SharedPtr<System::Object> System::Drawing::ImageConverter::ConvertTo(const System::SharedPtr<System::ComponentModel::ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| context | const System::SharedPtr\<System::ComponentModel::ITypeDescriptorContext\>\& | [Object](../../../system/object/) conversion context information |
| culture | const System::SharedPtr\<System::Globalization::CultureInfo\>\& | Culture to use when converting objects |
| value | const System::SharedPtr\<System::Object\>\& | An object to convert. |
| destinationType | const System::TypeInfo\& | A type to convert to. |

### ReturnValue

Converted object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [ImageConverter](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## ImageConverter::ConvertTo(const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) method


Converts object to specific type.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::SharedPtr\<System::Object\>\& | [Object](../../../system/object/) to convert. |
| destinationType | const System::TypeInfo\& | Type to convert to. |

### ReturnValue

Converted object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [ImageConverter](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
