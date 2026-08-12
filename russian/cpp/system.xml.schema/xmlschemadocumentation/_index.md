---
title: "System::Xml::Schema::XmlSchemaDocumentation класс"
linktitle: "XmlSchemaDocumentation"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaDocumentation класс. Представляет элемент documentation из XML Schema, определённый консорциумом World Wide Web (W3C). Этот класс задаёт информацию, которую могут читать или использовать люди внутри аннотации в C++."
type: docs
weight: 2500
url: /ru/cpp/system.xml.schema/xmlschemadocumentation/
---
## XmlSchemaDocumentation class


Представляет элемент **documentation** из XML [Schema](../), определённый консорциумом World Wide [Web](../../system.web/) (W3C). Этот класс задаёт информацию, которую могут читать или использовать люди внутри **annotation**.

```cpp
class XmlSchemaDocumentation : public System::Xml::Schema::XmlSchemaObject
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Language](./get_language/)() | Возвращает атрибут **xml:lang**. Он служит индикатором языка, используемого в содержимом. |
| [get_Markup](./get_markup/)() | Возвращает массив объектов [XmlNode](../../system.xml/xmlnode/), представляющих дочерние узлы documentation. |
| [get_Source](./get_source/)() | Возвращает источник Uniform Resource Identifier (URI) информации. |
| [set_Language](./set_language/)(const String\&) | Устанавливает атрибут **xml:lang**. Он служит индикатором языка, используемого в содержимом. |
| [set_Markup](./set_markup/)(const ArrayPtr\<SharedPtr\<XmlNode\>\>\&) | Устанавливает массив объектов [XmlNode](../../system.xml/xmlnode/), представляющих дочерние узлы documentation. |
| [set_Source](./set_source/)(const String\&) | Устанавливает источник Uniform Resource Identifier (URI) информации. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [XmlSchemaObject](../xmlschemaobject/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
