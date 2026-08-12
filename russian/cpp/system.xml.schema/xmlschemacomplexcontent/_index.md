---
title: "Класс System::Xml::Schema::XmlSchemaComplexContent"
linktitle: "XmlSchemaComplexContent"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaComplexContent класс. Представляет элемент complexContent из XML Schema, как указано World Wide Web Consortium (W3C). Этот класс представляет модель сложного содержимого для сложных типов. Он содержит расширения или ограничения для сложного типа, который имеет только элементы или смешанное содержимое в C++."
type: docs
weight: 1800
url: /ru/cpp/system.xml.schema/xmlschemacomplexcontent/
---
## XmlSchemaComplexContent class


Представляет элемент **complexContent** из XML [Schema](../) согласно спецификации World Wide [Web](../../system.web/) Consortium (W3C). Этот класс представляет модель сложного содержимого для сложных типов. Он содержит расширения или ограничения для сложного типа, который имеет только элементы или смешанное содержимое.

```cpp
class XmlSchemaComplexContent : public System::Xml::Schema::XmlSchemaContentModel
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Content](./get_content/)() override | Возвращает содержимое. |
| [get_IsMixed](./get_ismixed/)() | Возвращает информацию, определяющую, имеет ли тип модель смешанного содержимого. |
| [set_Content](./set_content/)(SharedPtr\<XmlSchemaContent\>) override | Устанавливает содержимое. |
| [set_IsMixed](./set_ismixed/)(bool) | Устанавливает информацию, определяющую, имеет ли тип модель смешанного содержимого. |
| [XmlSchemaComplexContent](./xmlschemacomplexcontent/)() | Инициализирует новый экземпляр класса [XmlSchemaComplexContent](./). |
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
