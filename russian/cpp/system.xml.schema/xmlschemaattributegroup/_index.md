---
title: "System::Xml::Schema::XmlSchemaAttributeGroup класс"
linktitle: "XmlSchemaAttributeGroup"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaAttributeGroup класс. Представляет элемент attributeGroup из XML Schema, как указано World Wide Web Consortium (W3C). AttributesGroups предоставляет механизм группировки набора объявлений атрибутов, чтобы их можно было включать как группу в определения сложных типов в C++."
type: docs
weight: 1200
url: /ru/cpp/system.xml.schema/xmlschemaattributegroup/
---
## XmlSchemaAttributeGroup class


Представляет элемент **attributeGroup** из XML [Schema](../) в соответствии с World Wide [Web](../../system.web/) Consortium (W3C). AttributesGroups предоставляет механизм группировки набора объявлений атрибутов, чтобы их можно было включать как группу в определения сложных типов.

```cpp
class XmlSchemaAttributeGroup : public System::Xml::Schema::XmlSchemaAnnotated
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_AnyAttribute](./get_anyattribute/)() | Возвращает компонент [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) группы атрибутов. |
| [get_Attributes](./get_attributes/)() | Возвращает коллекцию атрибутов для группы атрибутов. Содержит элементы [XmlSchemaAttribute](../xmlschemaattribute/) и [XmlSchemaAttributeGroupRef](../xmlschemaattributegroupref/). |
| [get_Name](./get_name/)() | Возвращает имя группы атрибутов. |
| [get_QualifiedName](./get_qualifiedname/)() | Возвращает квалифицированное имя группы атрибутов. |
| [get_RedefinedAttributeGroup](./get_redefinedattributegroup/)() | Возвращает переопределённое свойство группы атрибутов из XML [Schema](../). |
| [set_AnyAttribute](./set_anyattribute/)(const SharedPtr\<XmlSchemaAnyAttribute\>\&) | Устанавливает компонент [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) группы атрибутов. |
| [set_Name](./set_name/)(const String\&) | Устанавливает имя группы атрибутов. |
| [XmlSchemaAttributeGroup](./xmlschemaattributegroup/)() | Инициализирует новый экземпляр класса [XmlSchemaAttributeGroup](./). |
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
