---
title: "System::ComponentModel::TypeConverter::ConvertTo метод"
linktitle: "ConvertTo"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::ComponentModel::TypeConverter::ConvertTo метод. Преобразует объект в конкретный тип в C++."
type: docs
weight: 500
url: /ru/cpp/system.componentmodel/typeconverter/convertto/
---
## TypeConverter::ConvertTo(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) method


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
* Class [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [TypeConverter](../)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.PDF for C++](../../../)
## TypeConverter::ConvertTo(const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) method


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
* Class [TypeConverter](../)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.PDF for C++](../../../)
