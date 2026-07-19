---
title: "Класс System::Xml::Schema::XmlSchemaAnnotation"
linktitle: "XmlSchemaAnnotation"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Xml::Schema::XmlSchemaAnnotation. Представляет элемент аннотации World Wide Web Consortium (W3C) в C++."
type: docs
weight: 700
url: /ru/cpp/system.xml.schema/xmlschemaannotation/
---
## XmlSchemaAnnotation class


Представляет элемент **annotation** World Wide [Web](../../system.web/) Consortium (W3C).

```cpp
class XmlSchemaAnnotation : public System::Xml::Schema::XmlSchemaObject
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Id](./get_id/)() | Возвращает строковый идентификатор. |
| [get_Items](./get_items/)() | Возвращает коллекцию **Items**, используемую для хранения дочерних элементов **appinfo** и **documentation**. |
| [get_UnhandledAttributes](./get_unhandledattributes/)() | Возвращает квалифицированные атрибуты, которые не принадлежат целевому пространству имён схемы. |
| [set_Id](./set_id/)(const String\&) | Устанавливает строковый идентификатор. |
| [set_UnhandledAttributes](./set_unhandledattributes/)(const ArrayPtr\<SharedPtr\<XmlAttribute\>\>\&) | Устанавливает квалифицированные атрибуты, которые не принадлежат целевому пространству имён схемы. |
| [XmlSchemaAnnotation](./xmlschemaannotation/)() | Инициализирует новый экземпляр класса [XmlSchemaAnnotation](./). |
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
