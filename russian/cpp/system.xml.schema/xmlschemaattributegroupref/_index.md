---
title: "System::Xml::Schema::XmlSchemaAttributeGroupRef класс"
linktitle: "XmlSchemaAttributeGroupRef"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaAttributeGroupRef класс. Представляет элемент attributeGroup с атрибутом ref из XML Schema, как указано . AttributesGroupRef является ссылкой на attributeGroup, свойство name содержит группу атрибутов, на которую делается ссылка, в C++."
type: docs
weight: 1300
url: /ru/cpp/system.xml.schema/xmlschemaattributegroupref/
---
## XmlSchemaAttributeGroupRef class


Представляет элемент **attributeGroup** с атрибутом **ref** из XML [Schema](../) в соответствии с [World Wide Web Consortium (W3C)](https://go.microsoft.com/fwlink/?LinkId=49454). AttributesGroupRef является ссылкой на attributeGroup, свойство name содержит ссылку на группу атрибутов.

```cpp
class XmlSchemaAttributeGroupRef : public System::Xml::Schema::XmlSchemaAnnotated
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_RefName](./get_refname/)() | Возвращает имя ссылочного **attributeGroup** элемента. |
| [set_RefName](./set_refname/)(const SharedPtr\<XmlQualifiedName\>\&) | Устанавливает имя ссылочного **attributeGroup** элемента. |
| [XmlSchemaAttributeGroupRef](./xmlschemaattributegroupref/)() | Инициализирует новый экземпляр класса [XmlSchemaAttributeGroupRef](./). |
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
