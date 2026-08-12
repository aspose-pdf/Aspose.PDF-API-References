---
title: "Класс System::Xml::Schema::XmlSchemaType"
linktitle: "XmlSchemaType"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Xml::Schema::XmlSchemaType. Базовый класс для всех простых и сложных типов в C++."
type: docs
weight: 6800
url: /ru/cpp/system.xml.schema/xmlschematype/
---
## XmlSchemaType class


Базовый класс для всех простых и сложных типов.

```cpp
class XmlSchemaType : public System::Xml::Schema::XmlSchemaAnnotated
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_BaseSchemaType](./get_baseschematype/)() | Возвращает тип объекта после компиляции или встроенный тип данных XML [Schema](../) Definition Language (XSD), элемент simpleType или элемент complexType. Это значение набора информации после компиляции схемы. |
| [get_BaseXmlSchemaType](./get_basexmlschematype/)() | Возвращает значение после компиляции для базового типа этой схемы. |
| [get_Datatype](./get_datatype/)() | Возвращает значение после компиляции для типа данных сложного типа. |
| [get_DerivedBy](./get_derivedby/)() | Возвращает информацию после компиляции о том, как этот элемент был получен из своего базового типа. |
| [get_Final](./get_final/)() | Возвращает атрибут final производного типа, указывающий, разрешены ли дальнейшие производные. |
| [get_FinalResolved](./get_finalresolved/)() | Возвращает интерпретацию после компиляции значения [XmlSchemaType::get_Final](./get_final/). |
| virtual [get_IsMixed](./get_ismixed/)() | Возвращает значение, указывающее, имеет ли этот тип смешанную модель содержимого. Этот вызов действителен только для сложного типа. |
| [get_Name](./get_name/)() | Возвращает имя типа. |
| [get_QualifiedName](./get_qualifiedname/)() | Возвращает квалифицированное имя типа, построенное из атрибута **Name** этого типа. Это значение после компиляции схемы. |
| [get_TypeCode](./get_typecode/)() | Возвращает [XmlTypeCode](../xmltypecode/) типа. |
| static [GetBuiltInComplexType](./getbuiltincomplextype/)(XmlTypeCode) | Возвращает [XmlSchemaComplexType](../xmlschemacomplextype/), представляющий встроенный сложный тип указанного сложного типа. |
| static [GetBuiltInComplexType](./getbuiltincomplextype/)(const SharedPtr\<XmlQualifiedName\>\&) | Возвращает [XmlSchemaComplexType](../xmlschemacomplextype/), представляющий встроенный сложный тип сложного типа, указанный квалифицированным именем. |
| static [GetBuiltInSimpleType](./getbuiltinsimpletype/)(const SharedPtr\<XmlQualifiedName\>\&) | Возвращает [XmlSchemaSimpleType](../xmlschemasimpletype/), представляющий встроенный простой тип простого типа, указанный квалифицированным именем. |
| static [GetBuiltInSimpleType](./getbuiltinsimpletype/)(XmlTypeCode) | Возвращает [XmlSchemaSimpleType](../xmlschemasimpletype/), представляющий встроенный простой тип указанного простого типа. |
| static [IsDerivedFrom](./isderivedfrom/)(SharedPtr\<XmlSchemaType\>, const SharedPtr\<XmlSchemaType\>\&, XmlSchemaDerivationMethod) | Возвращает значение, указывающее, является ли указанный производный тип схемы производным от указанного базового типа схемы. |
| [set_Final](./set_final/)(XmlSchemaDerivationMethod) | Устанавливает атрибут final производного типа, указывающий, разрешены ли дальнейшие производные. |
| virtual [set_IsMixed](./set_ismixed/)(bool) | Устанавливает значение, указывающее, имеет ли этот тип смешанную модель содержимого. Этот вызов действителен только для сложного типа. |
| [set_Name](./set_name/)(const String\&) | Устанавливает имя типа. |
| [XmlSchemaType](./xmlschematype/)() | Инициализирует новый экземпляр класса [XmlSchemaType](./). |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [XmlSchemaAnnotated](../xmlschemaannotated/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
