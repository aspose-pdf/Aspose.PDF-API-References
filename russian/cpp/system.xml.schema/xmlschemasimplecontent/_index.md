---
title: "System::Xml::Schema::XmlSchemaSimpleContent класс"
linktitle: "XmlSchemaSimpleContent"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaSimpleContent класс. Представляет элемент simpleContent из XML Schema, как указано World Wide Web Consortium (W3C). Этот класс предназначен для простых и сложных типов с простой моделью содержимого в C++."
type: docs
weight: 5900
url: /ru/cpp/system.xml.schema/xmlschemasimplecontent/
---
## XmlSchemaSimpleContent class


Представляет элемент **simpleContent** из XML [Schema](../) как указано World Wide [Web](../../system.web/) Consortium (W3C). Этот класс предназначен для простых и сложных типов с простой моделью содержимого.

```cpp
class XmlSchemaSimpleContent : public System::Xml::Schema::XmlSchemaContentModel
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Content](./get_content/)() override | Возвращает один из [XmlSchemaSimpleContentRestriction](../xmlschemasimplecontentrestriction/) или [XmlSchemaSimpleContentExtension](../xmlschemasimplecontentextension/). |
| [set_Content](./set_content/)(SharedPtr\<XmlSchemaContent\>) override | Возвращает один из [XmlSchemaSimpleContentRestriction](../xmlschemasimplecontentrestriction/) или [XmlSchemaSimpleContentExtension](../xmlschemasimplecontentextension/). |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [XmlSchemaContentModel](../xmlschemacontentmodel/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
