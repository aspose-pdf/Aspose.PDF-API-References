---
title: "System::Xml::Schema::XmlSchemaAppInfo класс"
linktitle: "XmlSchemaAppInfo"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaAppInfo класс. Представляет элемент appinfo консорциума World Wide Web (W3C) в C++."
type: docs
weight: 1000
url: /ru/cpp/system.xml.schema/xmlschemaappinfo/
---
## XmlSchemaAppInfo class


Представляет элемент **appinfo** консорциума World Wide [Web](../../system.web/) (W3C).

```cpp
class XmlSchemaAppInfo : public System::Xml::Schema::XmlSchemaObject
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Markup](./get_markup/)() | Возвращает массив объектов [XmlNode](../../system.xml/xmlnode/), представляющих дочерние узлы **appinfo**. |
| [get_Source](./get_source/)() | Возвращает источник информации о приложении. |
| [set_Markup](./set_markup/)(const ArrayPtr\<SharedPtr\<XmlNode\>\>\&) | Устанавливает массив объектов [XmlNode](../../system.xml/xmlnode/), представляющих дочерние узлы **appinfo**. |
| [set_Source](./set_source/)(const String\&) | Устанавливает источник информации о приложении. |
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
