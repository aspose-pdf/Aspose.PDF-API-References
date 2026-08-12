---
title: "System::Drawing::ImageFormatConverter::ConvertTo method"
linktitle: "ConvertTo"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::ImageFormatConverter::ConvertTo method. Konverterar objekt till en specifik typ i C++."
type: docs
weight: 300
url: /sv/cpp/system.drawing/imageformatconverter/convertto/
---
## ImageFormatConverter::ConvertTo(const SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, const SharedPtr\<Object\>\&, const TypeInfo\&) method


Konverterar objekt till en specifik typ.

```cpp
SharedPtr<Object> System::Drawing::ImageFormatConverter::ConvertTo(const SharedPtr<ComponentModel::ITypeDescriptorContext> &context, const SharedPtr<Globalization::CultureInfo> &culture, const SharedPtr<Object> &value, const TypeInfo &destinationType) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| context | const SharedPtr\<ComponentModel::ITypeDescriptorContext\>\& | [Object](../../../system/object/) konverteringskontextinformation. |
| kultur | const SharedPtr\<Globalization::CultureInfo\>\& | Kultur att använda när objekt konverteras. |
| value | const SharedPtr\<Object\>\& | [Object](../../../system/object/) att konvertera. |
| destinationType | const TypeInfo\& | Typ att konvertera till. |

### ReturnValue

Konverterat objekt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [ImageFormatConverter](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## ImageFormatConverter::ConvertTo(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) method


Konverterar objekt till en specifik typ.

```cpp
virtual System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| context | const System::SharedPtr\<ITypeDescriptorContext\>\& | [Object](../../../system/object/) konverteringskontextinformation. |
| kultur | const System::SharedPtr\<System::Globalization::CultureInfo\>\& | Kultur att använda när objekt konverteras. |
| value | const System::SharedPtr\<System::Object\>\& | [Object](../../../system/object/) att konvertera. |
| destinationType | const System::TypeInfo\& | Typ att konvertera till. |

### ReturnValue

Konverterat objekt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [ImageFormatConverter](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## ImageFormatConverter::ConvertTo(const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) method


Konverterar objekt till en specifik typ.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const System::SharedPtr\<System::Object\>\& | [Object](../../../system/object/) att konvertera. |
| destinationType | const System::TypeInfo\& | Typ att konvertera till. |

### ReturnValue

Konverterat objekt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [ImageFormatConverter](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
