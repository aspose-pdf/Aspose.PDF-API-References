---
title: "System::Xml::Schema::XmlSchemaComplexContentRestriction class"
linktitle: "XmlSchemaComplexContentRestriction"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaComplexContentRestriction class. Представляет элемент restriction из XML Schema, определённый World Wide Web Consortium (W3C). Этот класс предназначен для сложных типов с моделью сложного содержимого, полученной посредством ограничения. Он ограничивает содержимое сложного типа подмножеством унаследованного сложного типа в C++."
type: docs
weight: 2000
url: /ru/cpp/system.xml.schema/xmlschemacomplexcontentrestriction/
---
## XmlSchemaComplexContentRestriction class


Представляет элемент **restriction** из XML [Schema](../) согласно спецификации World Wide [Web](../../system.web/) Consortium (W3C). Этот класс предназначен для сложных типов с моделью сложного содержимого, полученной путем ограничения. Он ограничивает содержимое сложного типа до подмножества унаследованного сложного типа.

```cpp
class XmlSchemaComplexContentRestriction : public System::Xml::Schema::XmlSchemaContent
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_AnyAttribute](./get_anyattribute/)() | Возвращает компонент [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) сложной модели содержимого. |
| [get_Attributes](./get_attributes/)() | Возвращает коллекцию атрибутов для сложного типа. Содержит элементы [XmlSchemaAttribute](../xmlschemaattribute/) и [XmlSchemaAttributeGroupRef](../xmlschemaattributegroupref/). |
| [get_BaseTypeName](./get_basetypename/)() | Возвращает имя сложного типа, от которого данный тип получен путем ограничения. |
| [get_Particle](./get_particle/)() | Возвращает один из классов [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) или [XmlSchemaSequence](../xmlschemasequence/). |
| [set_AnyAttribute](./set_anyattribute/)(const SharedPtr\<XmlSchemaAnyAttribute\>\&) | Устанавливает компонент [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) сложной модели содержимого. |
| [set_BaseTypeName](./set_basetypename/)(const SharedPtr\<XmlQualifiedName\>\&) | Устанавливает имя сложного типа, от которого данный тип получен путем ограничения. |
| [set_Particle](./set_particle/)(const SharedPtr\<XmlSchemaParticle\>\&) | Устанавливает один из классов [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) или [XmlSchemaSequence](../xmlschemasequence/). |
| [XmlSchemaComplexContentRestriction](./xmlschemacomplexcontentrestriction/)() | Инициализирует новый экземпляр класса [XmlSchemaComplexContentRestriction](./). |
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
