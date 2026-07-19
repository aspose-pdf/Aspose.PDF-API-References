---
title: "System::Xml::Schema::XmlSchemaAttribute class"
linktitle: "XmlSchemaAttribute"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaAttribute class. Представляет элемент attribute из XML Schema, как указано World Wide Web Consortium (W3C). Атрибуты предоставляют дополнительную информацию для других элементов документа. Тег атрибута вложен между тегами элемента документа для схемы. XML‑документ отображает атрибуты как именованные элементы в открывающем теге элемента в C++."
type: docs
weight: 1100
url: /ru/cpp/system.xml.schema/xmlschemaattribute/
---
## XmlSchemaAttribute class


Представляет элемент **attribute** из XML [Schema](../) как указано World Wide [Web](../../system.web/) Consortium (W3C). Атрибуты предоставляют дополнительную информацию для других элементов документа. Тег атрибута вложен между тегами элемента документа для схемы. XML‑документ отображает атрибуты как именованные элементы в открывающем теге элемента.

```cpp
class XmlSchemaAttribute : public System::Xml::Schema::XmlSchemaAnnotated
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_AttributeSchemaType](./get_attributeschematype/)() | Возвращает объект [XmlSchemaSimpleType](../xmlschemasimpletype/), представляющий тип атрибута на основе значения [XmlSchemaAttribute::get_SchemaType](./get_schematype/) или [XmlSchemaAttribute::get_SchemaTypeName](./get_schematypename/) атрибута. |
| [get_AttributeType](./get_attributetype/)() | Возвращает объект на основе значения [XmlSchemaAttribute::get_SchemaType](./get_schematype/) или [XmlSchemaAttribute::get_SchemaTypeName](./get_schematypename/) атрибута, содержащего посткомпиляционную интерпретацию значения **AttributeType**. |
| [get_DefaultValue](./get_defaultvalue/)() | Возвращает значение по умолчанию для атрибута. |
| [get_FixedValue](./get_fixedvalue/)() | Возвращает фиксированное значение для атрибута. |
| [get_Form](./get_form/)() | Возвращает форму атрибута. |
| [get_Name](./get_name/)() | Возвращает имя атрибута. |
| [get_QualifiedName](./get_qualifiedname/)() | Возвращает квалифицированное имя атрибута. |
| [get_RefName](./get_refname/)() | Возвращает имя атрибута, объявленного в этой схеме (или в другой схеме, указанной указанным пространством имён). |
| [get_SchemaType](./get_schematype/)() | Возвращает тип атрибута как простой тип. |
| [get_SchemaTypeName](./get_schematypename/)() | Возвращает имя простого типа, определённого в этой схеме (или в другой схеме, указанной указанным пространством имён). |
| [get_Use](./get_use/)() | Возвращает информацию о том, как используется атрибут. |
| [set_DefaultValue](./set_defaultvalue/)(const String\&) | Устанавливает значение по умолчанию для атрибута. |
| [set_FixedValue](./set_fixedvalue/)(const String\&) | Устанавливает фиксированное значение для атрибута. |
| [set_Form](./set_form/)(XmlSchemaForm) | Устанавливает форму атрибута. |
| [set_Name](./set_name/)(const String\&) | Устанавливает имя атрибута. |
| [set_RefName](./set_refname/)(const SharedPtr\<XmlQualifiedName\>\&) | Устанавливает имя атрибута, объявленного в этой схеме (или в другой схеме, указанной указанным пространством имён). |
| [set_SchemaType](./set_schematype/)(const SharedPtr\<XmlSchemaSimpleType\>\&) | Устанавливает тип атрибута как простой тип. |
| [set_SchemaTypeName](./set_schematypename/)(const SharedPtr\<XmlQualifiedName\>\&) | Устанавливает имя простого типа, определённого в этой схеме (или в другой схеме, указанной заданным пространством имён). |
| [set_Use](./set_use/)(XmlSchemaUse) | Устанавливает информацию о том, как используется атрибут. |
| [XmlSchemaAttribute](./xmlschemaattribute/)() | Инициализирует новый экземпляр класса [XmlSchemaAttribute](./). |
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
