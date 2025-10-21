---
title: System::Drawing::ImageFormatConverter::ConvertTo method
linktitle: ConvertTo
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::ImageFormatConverter::ConvertTo method. Converts object to specific type in C++.'
type: docs
weight: 300
url: /cpp/system.drawing/imageformatconverter/convertto/
---
## ImageFormatConverter::ConvertTo(const SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, const SharedPtr\<Object\>\&, const TypeInfo\&) method


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
## ImageFormatConverter::ConvertTo(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) method


Converts object to specific type.

```cpp
virtual System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```


| Parameter | Type | Description |
| --- | --- | --- |
| context | const System::SharedPtr\<ITypeDescriptorContext\>\& | [Object](../../../system/object/) conversion context information. |
| culture | const System::SharedPtr\<System::Globalization::CultureInfo\>\& | Culture to use when converting objects. |
| value | const System::SharedPtr\<System::Object\>\& | [Object](../../../system/object/) to convert. |
| destinationType | const System::TypeInfo\& | Type to convert to. |

### ReturnValue

Converted object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [ImageFormatConverter](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## ImageFormatConverter::ConvertTo(const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) method


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
* Class [ImageFormatConverter](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
