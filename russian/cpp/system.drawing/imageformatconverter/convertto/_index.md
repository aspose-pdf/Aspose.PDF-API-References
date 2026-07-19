---
title: "System::Drawing::ImageFormatConverter::ConvertTo method"
linktitle: "ConvertTo"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Drawing::ImageFormatConverter::ConvertTo method. Преобразует объект в конкретный тип в C++."
type: docs
weight: 300
url: /ru/cpp/system.drawing/imageformatconverter/convertto/
---
## ImageFormatConverter::ConvertTo(const SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, const SharedPtr\<Object\>\&, const TypeInfo\&) method


Преобразует объект в конкретный тип.

```cpp
SharedPtr<Object> System::Drawing::ImageFormatConverter::ConvertTo(const SharedPtr<ComponentModel::ITypeDescriptorContext> &context, const SharedPtr<Globalization::CultureInfo> &culture, const SharedPtr<Object> &value, const TypeInfo &destinationType) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| context | const SharedPtr\<ComponentModel::ITypeDescriptorContext\>\& | [Object](../../../system/object/) информация о контексте преобразования. |
| культура | const SharedPtr\<Globalization::CultureInfo\>\& | Культура, используемая при преобразовании объектов. |
| value | const SharedPtr\<Object\>\& | [Object](../../../system/object/) для преобразования. |
| destinationType | const TypeInfo\& | Тип для преобразования. |

### ReturnValue

Преобразованный объект.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [ImageFormatConverter](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## ImageFormatConverter::ConvertTo(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) method


Преобразует объект в конкретный тип.

```cpp
virtual System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| context | const System::SharedPtr\<ITypeDescriptorContext\>\& | [Object](../../../system/object/) информация о контексте преобразования. |
| культура | const System::SharedPtr\<System::Globalization::CultureInfo\>\& | Культура, используемая при преобразовании объектов. |
| value | const System::SharedPtr\<System::Object\>\& | [Object](../../../system/object/) для преобразования. |
| destinationType | const System::TypeInfo\& | Тип для преобразования. |

### ReturnValue

Преобразованный объект.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [ImageFormatConverter](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## ImageFormatConverter::ConvertTo(const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) method


Преобразует объект в конкретный тип.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const System::SharedPtr\<System::Object\>\& | [Object](../../../system/object/) для преобразования. |
| destinationType | const System::TypeInfo\& | Тип для преобразования. |

### ReturnValue

Преобразованный объект.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [ImageFormatConverter](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
