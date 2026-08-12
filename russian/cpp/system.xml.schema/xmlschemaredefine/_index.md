---
title: "System::Xml::Schema::XmlSchemaRedefine класс"
linktitle: "XmlSchemaRedefine"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaRedefine класс. Представляет элемент redefine из XML Schema, как указано World Wide Web Consortium (W3C). Этот класс может использоваться для переопределения простых и сложных типов, групп и групп атрибутов из внешних файлов схем в текущей схеме. Этот класс также может использоваться для обеспечения версионирования элементов схемы в C++."
type: docs
weight: 5600
url: /ru/cpp/system.xml.schema/xmlschemaredefine/
---
## XmlSchemaRedefine class


Представляет элемент **redefine** из XML [Schema](../), как указано World Wide [Web](../../system.web/) Consortium (W3C). Этот класс может использоваться для переопределения простых и сложных типов, групп и групп атрибутов из внешних файлов схем в текущей схеме. Этот класс также может использоваться для обеспечения версионирования элементов схемы.

```cpp
class XmlSchemaRedefine : public System::Xml::Schema::XmlSchemaExternal
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_AttributeGroups](./get_attributegroups/)() | Возвращает [XmlSchemaObjectTable](../xmlschemaobjecttable/), содержащий все атрибуты схемы и представляющий посткомпиляционную интерпретацию значения **AttributeGroups**. |
| [get_Groups](./get_groups/)() | Возвращает [XmlSchemaObjectTable](../xmlschemaobjecttable/), содержащий все группы схемы и представляющий посткомпиляционную интерпретацию значения **Groups**. |
| [get_Items](./get_items/)() | Возвращает коллекцию следующих классов: [XmlSchemaAnnotation](../xmlschemaannotation/), [XmlSchemaAttributeGroup](../xmlschemaattributegroup/), [XmlSchemaComplexType](../xmlschemacomplextype/), [XmlSchemaSimpleType](../xmlschemasimpletype/), и [XmlSchemaGroup](../xmlschemagroup/). |
| [get_SchemaTypes](./get_schematypes/)() | Возвращает [XmlSchemaObjectTable](../xmlschemaobjecttable/), содержащий все простые и сложные типы схемы и представляющий посткомпиляционную интерпретацию значения **SchemaTypes**. |
| [XmlSchemaRedefine](./xmlschemaredefine/)() | Инициализирует новый экземпляр класса [XmlSchemaRedefine](./). |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [XmlSchemaExternal](../xmlschemaexternal/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
