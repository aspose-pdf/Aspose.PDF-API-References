---
title: "Класс System::Xml::Schema::XmlSchemaSimpleContentExtension"
linktitle: "XmlSchemaSimpleContentExtension"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Xml::Schema::XmlSchemaSimpleContentExtension. Представляет элемент extension для простого содержимого из XML Schema, как указано консорциумом World Wide Web (W3C). Этот класс может использоваться для создания простых типов посредством расширения. Такие расширения применяются для расширения содержимого простого типа элемента путем добавления атрибутов в C++."
type: docs
weight: 6000
url: /ru/cpp/system.xml.schema/xmlschemasimplecontentextension/
---
## XmlSchemaSimpleContentExtension class


Представляет элемент **extension** для простого содержимого из XML [Schema](../), как указано консорциумом World Wide [Web](../../system.web/) (W3C). Этот класс может использоваться для создания простых типов посредством расширения. Такие расширения применяются для расширения содержимого простого типа элемента путем добавления атрибутов.

```cpp
class XmlSchemaSimpleContentExtension : public System::Xml::Schema::XmlSchemaContent
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_AnyAttribute](./get_anyattribute/)() | Возвращает [XmlSchemaAnyAttribute](../xmlschemaanyattribute/), который будет использоваться для значения атрибута. |
| [get_Attributes](./get_attributes/)() | Возвращает коллекцию [XmlSchemaAttribute](../xmlschemaattribute/) и [XmlSchemaAttributeGroupRef](../xmlschemaattributegroupref/). |
| [get_BaseTypeName](./get_basetypename/)() | Возвращает имя встроенного типа данных или простого типа, от которого расширяется этот тип. |
| [set_AnyAttribute](./set_anyattribute/)(const SharedPtr\<XmlSchemaAnyAttribute\>\&) | Устанавливает [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) для использования в значении атрибута. |
| [set_BaseTypeName](./set_basetypename/)(const SharedPtr\<XmlQualifiedName\>\&) | Устанавливает имя встроенного типа данных или простого типа, от которого расширяется этот тип. |
| [XmlSchemaSimpleContentExtension](./xmlschemasimplecontentextension/)() | Инициализирует новый экземпляр класса [XmlSchemaSimpleContentExtension](./). |
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
