---
title: "System::Xml::Schema::XmlSchemaGroupRef класс"
linktitle: "XmlSchemaGroupRef"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Xml::Schema::XmlSchemaGroupRef. Представляет элемент group с атрибутом ref из XML Schema, как указано World Wide Web Consortium (W3C). Этот класс используется в сложных типах, которые ссылаются на группу, определённую на уровне схемы в C++."
type: docs
weight: 3300
url: /ru/cpp/system.xml.schema/xmlschemagroupref/
---
## XmlSchemaGroupRef class


Представляет элемент **group** с атрибутом **ref** из XML [Schema](../) как указано World Wide [Web](../../system.web/) Consortium (W3C). Этот класс используется в сложных типах, которые ссылаются на **group**, определённый на уровне **schema**.

```cpp
class XmlSchemaGroupRef : public System::Xml::Schema::XmlSchemaParticle
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Particle](./get_particle/)() | Возвращает один из классов [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/), или [XmlSchemaSequence](../xmlschemasequence/), который содержит посткомпиляционную интерпретацию значения **Particle**. |
| [get_RefName](./get_refname/)() | Возвращает имя группы, определённой в этой схеме (или в другой схеме, указанной заданным пространством имён). |
| [set_RefName](./set_refname/)(const SharedPtr\<XmlQualifiedName\>\&) | Устанавливает имя группы, определённой в этой схеме (или в другой схеме, указанной заданным пространством имён). |
| [XmlSchemaGroupRef](./xmlschemagroupref/)() | Инициализирует новый экземпляр класса [XmlSchemaGroupRef](./). |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [XmlSchemaParticle](../xmlschemaparticle/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
