---
title: "System::Xml::Schema::XmlSchemaIdentityConstraint класс"
linktitle: "XmlSchemaIdentityConstraint"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaIdentityConstraint класс. Класс для ограничений идентичности: элементы key, keyref и unique в C++."
type: docs
weight: 3400
url: /ru/cpp/system.xml.schema/xmlschemaidentityconstraint/
---
## XmlSchemaIdentityConstraint class


Класс для ограничений идентичности: элементы **key**, **keyref** и **unique**.

```cpp
class XmlSchemaIdentityConstraint : public System::Xml::Schema::XmlSchemaAnnotated
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Fields](./get_fields/)() | Возвращает коллекцию полей, которые применяются как дочерние элементы для селектора выражения XML Path Language ([XPath](../../system.xml.xpath/)). |
| [get_Name](./get_name/)() | Возвращает имя ограничения идентичности. |
| [get_QualifiedName](./get_qualifiedname/)() | Возвращает квалифицированное имя ограничения идентичности, которое содержит посткомпиляционную интерпретацию значения **QualifiedName**. |
| [get_Selector](./get_selector/)() | Возвращает элемент **selector** выражения [XPath](../../system.xml.xpath/). |
| [set_Name](./set_name/)(const String\&) | Устанавливает имя ограничения идентичности. |
| [set_Selector](./set_selector/)(const SharedPtr\<XmlSchemaXPath\>\&) | Устанавливает элемент **selector** выражения [XPath](../../system.xml.xpath/). |
| [XmlSchemaIdentityConstraint](./xmlschemaidentityconstraint/)() | Инициализирует новый экземпляр класса [XmlSchemaIdentityConstraint](./). |
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
