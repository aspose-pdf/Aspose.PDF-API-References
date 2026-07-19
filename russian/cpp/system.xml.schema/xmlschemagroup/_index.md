---
title: "System::Xml::Schema::XmlSchemaGroup класс"
linktitle: "XmlSchemaGroup"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaGroup класс. Представляет элемент group из XML Schema согласно спецификации World Wide Web Consortium (W3C). Этот класс определяет группы на уровне схемы, которые используются в сложных типах. Он объединяет набор объявлений элементов, чтобы их можно было включить как группу в определения сложных типов в C++."
type: docs
weight: 3100
url: /ru/cpp/system.xml.schema/xmlschemagroup/
---
## XmlSchemaGroup class


Представляет элемент **group** из XML [Schema](../) согласно спецификации World Wide [Web](../../system.web/) Consortium (W3C). Этот класс определяет группы на уровне **schema**, которые используются в сложных типах. Он группирует набор объявлений элементов, чтобы их можно было включить как группу в определения сложных типов.

```cpp
class XmlSchemaGroup : public System::Xml::Schema::XmlSchemaAnnotated
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Name](./get_name/)() | Возвращает имя группы схемы. |
| [get_Particle](./get_particle/)() | Возвращает один из классов [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) или [XmlSchemaSequence](../xmlschemasequence/). |
| [get_QualifiedName](./get_qualifiedname/)() | Возвращает квалифицированное имя группы схемы. |
| [set_Name](./set_name/)(const String\&) | Устанавливает имя группы схемы. |
| [set_Particle](./set_particle/)(const SharedPtr\<XmlSchemaGroupBase\>\&) | Устанавливает один из классов [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) или [XmlSchemaSequence](../xmlschemasequence/). |
| [XmlSchemaGroup](./xmlschemagroup/)() | Инициализирует новый экземпляр класса [XmlSchemaGroup](./). |
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
