---
title: "System::ComponentModel::TypeConverter::ConvertFrom metod"
linktitle: "ConvertFrom"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::ComponentModel::TypeConverter::ConvertFrom metod. Konverterar objekt i C++."
type: docs
weight: 200
url: /sv/cpp/system.componentmodel/typeconverter/convertfrom/
---
## TypeConverter::ConvertFrom(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&) method


Konverterar objekt.

```cpp
virtual System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFrom(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| context | const System::SharedPtr\<ITypeDescriptorContext\>\& | [Object](../../../system/object/) konverteringskontextinformation. |
| kultur | const System::SharedPtr\<System::Globalization::CultureInfo\>\& | Kultur att använda när objekt konverteras. |
| value | const System::SharedPtr\<System::Object\>\& | [Object](../../../system/object/) att konvertera. |

### ReturnValue

konverterat objekt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [TypeConverter](../)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.PDF for C++](../../../)
## TypeConverter::ConvertFrom(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::String\&) method


Konverterar sträng till objekt.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFrom(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::String &value)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| context | const System::SharedPtr\<ITypeDescriptorContext\>\& | [Object](../../../system/object/) konverteringskontextinformation. |
| kultur | const System::SharedPtr\<System::Globalization::CultureInfo\>\& | Kultur att använda när objekt konverteras. |
| värde | const System::String\& | Värde att konvertera. |

### ReturnValue

konverterat objekt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [String](../../../system/string/)
* Class [TypeConverter](../)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.PDF for C++](../../../)
## TypeConverter::ConvertFrom(const System::SharedPtr\<System::Object\>\&) method


Konverterar objekt.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFrom(const System::SharedPtr<System::Object> &value)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const System::SharedPtr\<System::Object\>\& | [Object](../../../system/object/) att konvertera. |

### ReturnValue

konverterat objekt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeConverter](../)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.PDF for C++](../../../)
