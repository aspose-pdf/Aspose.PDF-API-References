---
title: "System::Xml::Schema::XmlSchemaSimpleContentRestriction class"
linktitle: "XmlSchemaSimpleContentRestriction"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaSimpleContentRestriction class. Представляет элемент ограничения для простого содержимого из XML Schema, как указано World Wide Web Consortium (W3C). Этот класс может использоваться для получения простых типов посредством ограничения. Такие наследования могут использоваться для ограничения диапазона значений элемента до подмножества значений, указанных в унаследованном простом типе, в C++."
type: docs
weight: 6100
url: /ru/cpp/system.xml.schema/xmlschemasimplecontentrestriction/
---
## XmlSchemaSimpleContentRestriction class


Представляет элемент **restriction** для простого содержимого из XML [Schema](../), как указано World Wide [Web](../../system.web/) Consortium (W3C). Этот класс может использоваться для получения простых типов посредством ограничения. Такие наследования могут использоваться для ограничения диапазона значений элемента до подмножества значений, указанных в унаследованном простом типе.

```cpp
class XmlSchemaSimpleContentRestriction : public System::Xml::Schema::XmlSchemaContent
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_AnyAttribute](./get_anyattribute/)() | Возвращает [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) для использования в значении атрибута. |
| [get_Attributes](./get_attributes/)() | Возвращает коллекцию атрибутов [XmlSchemaAttribute](../xmlschemaattribute/) и [XmlSchemaAttributeGroupRef](../xmlschemaattributegroupref/) для простого типа. |
| [get_BaseType](./get_basetype/)() | Возвращает базовое значение простого типа. |
| [get_BaseTypeName](./get_basetypename/)() | Возвращает имя встроенного типа данных или простого типа, от которого происходит данный тип. |
| [get_Facets](./get_facets/)() | Возвращает фасет [Xml](../../system.xml/)[Schema](../). |
| [set_AnyAttribute](./set_anyattribute/)(const SharedPtr\<XmlSchemaAnyAttribute\>\&) | Устанавливает [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) для использования в значении атрибута. |
| [set_BaseType](./set_basetype/)(const SharedPtr\<XmlSchemaSimpleType\>\&) | Устанавливает базовое значение простого типа. |
| [set_BaseTypeName](./set_basetypename/)(const SharedPtr\<XmlQualifiedName\>\&) | Устанавливает имя встроенного типа данных или простого типа, от которого происходит данный тип. |
| [XmlSchemaSimpleContentRestriction](./xmlschemasimplecontentrestriction/)() | Инициализирует новый экземпляр класса [XmlSchemaSimpleContentRestriction](./). |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [XmlSchemaContent](../xmlschemacontent/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
