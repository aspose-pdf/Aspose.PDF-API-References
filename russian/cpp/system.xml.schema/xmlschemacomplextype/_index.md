---
title: "Класс System::Xml::Schema::XmlSchemaComplexType"
linktitle: "XmlSchemaComplexType"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Xml::Schema::XmlSchemaComplexType. Представляет элемент complexType из XML Schema, определённый World Wide Web Consortium (W3C). Этот класс определяет сложный тип, который определяет набор атрибутов и содержимое элемента в C++."
type: docs
weight: 2100
url: /ru/cpp/system.xml.schema/xmlschemacomplextype/
---
## XmlSchemaComplexType class


Представляет элемент **complexType** из XML [Schema](../), определённый World Wide [Web](../../system.web/) Consortium (W3C). Этот класс определяет сложный тип, который определяет набор атрибутов и содержимое элемента.

```cpp
class XmlSchemaComplexType : public System::Xml::Schema::XmlSchemaType
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_AnyAttribute](./get_anyattribute/)() | Возвращает значение компонента [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) сложного типа. |
| [get_Attributes](./get_attributes/)() | Возвращает коллекцию атрибутов сложного типа. |
| [get_AttributeUses](./get_attributeuses/)() | Возвращает коллекцию всех согласованных атрибутов этого сложного типа и его базовых типов. |
| [get_AttributeWildcard](./get_attributewildcard/)() | Возвращает значение после компиляции для **anyAttribute** этого сложного типа и его базовых типов. |
| [get_Block](./get_block/)() | Возвращает атрибут **block**. |
| [get_BlockResolved](./get_blockresolved/)() | Возвращает значение после того, как тип был скомпилирован в набор информации после проверки схемы (infoset). Это значение указывает, как тип применяется, когда в документе экземпляра используется **xsi:type**. |
| [get_ContentModel](./get_contentmodel/)() | Возвращает послекомпиляционный [XmlSchemaContentModel](../xmlschemacontentmodel/) этого сложного типа. |
| [get_ContentType](./get_contenttype/)() | Возвращает модель содержимого сложного типа, которая содержит значение после компиляции. |
| [get_ContentTypeParticle](./get_contenttypeparticle/)() | Возвращает частицу, которая содержит значение после компиляции частицы [XmlSchemaComplexType::get_ContentType](./get_contenttype/). |
| [get_IsAbstract](./get_isabstract/)() | Возвращает информацию, определяющую, может ли элемент **complexType** использоваться в документе экземпляра. |
| [get_IsMixed](./get_ismixed/)() override | Возвращает информацию, определяющую, имеет ли сложный тип смешанную модель содержимого (разметку внутри содержимого). |
| [get_Particle](./get_particle/)() | Возвращает тип композитора как один из классов [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) или [XmlSchemaSequence](../xmlschemasequence/). |
| [set_AnyAttribute](./set_anyattribute/)(const SharedPtr\<XmlSchemaAnyAttribute\>\&) | Устанавливает значение для компонента [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) сложного типа. |
| [set_Block](./set_block/)(XmlSchemaDerivationMethod) | Устанавливает атрибут **block**. |
| [set_ContentModel](./set_contentmodel/)(const SharedPtr\<XmlSchemaContentModel\>\&) | Устанавливает послекомпиляционный [XmlSchemaContentModel](../xmlschemacontentmodel/) этого сложного типа. |
| [set_IsAbstract](./set_isabstract/)(bool) | Устанавливает информацию, определяющую, может ли элемент **complexType** использоваться в документе экземпляра. |
| [set_IsMixed](./set_ismixed/)(bool) override | Устанавливает информацию, определяющую, имеет ли сложный тип смешанную модель содержимого (разметку внутри содержимого). |
| [set_Particle](./set_particle/)(const SharedPtr\<XmlSchemaParticle\>\&) | Устанавливает тип композитора как один из классов [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) или [XmlSchemaSequence](../xmlschemasequence/). |
| [XmlSchemaComplexType](./xmlschemacomplextype/)() | Инициализирует новый экземпляр класса [XmlSchemaComplexType](./). |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [XmlSchemaType](../xmlschematype/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
