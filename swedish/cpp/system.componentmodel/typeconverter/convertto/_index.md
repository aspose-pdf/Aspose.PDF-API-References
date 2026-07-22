---
title: "System::ComponentModel::TypeConverter::ConvertTo metod"
linktitle: "ConvertTo"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::ComponentModel::TypeConverter::ConvertTo metod. Konverterar objekt till en specifik typ i C++."
type: docs
weight: 500
url: /sv/cpp/system.componentmodel/typeconverter/convertto/
---
## TypeConverter::ConvertTo(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) method


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
* Class [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [TypeConverter](../)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.PDF for C++](../../../)
## TypeConverter::ConvertTo(const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) method


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
* Class [TypeConverter](../)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.PDF for C++](../../../)
