---
title: "System::Xml::Schema::XmlSchemaAnnotated класс"
linktitle: "XmlSchemaAnnotated"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaAnnotated класс. Базовый класс для любого элемента, который может содержать элементы аннотации в C++."
type: docs
weight: 600
url: /ru/cpp/system.xml.schema/xmlschemaannotated/
---
## XmlSchemaAnnotated class


Базовый класс для любого элемента, который может содержать элементы аннотации.

```cpp
class XmlSchemaAnnotated : public System::Xml::Schema::XmlSchemaObject
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Annotation](./get_annotation/)() | Возвращает свойство **annotation**. |
| [get_Id](./get_id/)() | Возвращает строковый идентификатор. |
| [get_UnhandledAttributes](./get_unhandledattributes/)() | Возвращает квалифицированные атрибуты, которые не принадлежат целевому пространству имён текущей схемы. |
| [set_Annotation](./set_annotation/)(const SharedPtr\<XmlSchemaAnnotation\>\&) | Устанавливает свойство **annotation**. |
| [set_Id](./set_id/)(const String\&) | Устанавливает строковый идентификатор. |
| [set_UnhandledAttributes](./set_unhandledattributes/)(const ArrayPtr\<SharedPtr\<XmlAttribute\>\>\&) | Устанавливает квалифицированные атрибуты, которые не принадлежат целевому пространству имён текущей схемы. |
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
