---
title: "System::Xml::Schema::XmlSchemaExternal класс"
linktitle: "XmlSchemaExternal"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaExternal класс. Предоставляет информацию о включённой схеме в C++."
type: docs
weight: 2800
url: /ru/cpp/system.xml.schema/xmlschemaexternal/
---
## XmlSchemaExternal class


Предоставляет информацию о включённой схеме.

```cpp
class XmlSchemaExternal : public System::Xml::Schema::XmlSchemaObject
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Id](./get_id/)() | Возвращает строковый идентификатор. |
| [get_Schema](./get_schema/)() | Возвращает [XmlSchema](../xmlschema/) для указанной схемы. |
| [get_SchemaLocation](./get_schemalocation/)() | Возвращает расположение Uniform Resource Identifier (URI) схемы, которое сообщает процессору схем, где схема физически находится. |
| [get_UnhandledAttributes](./get_unhandledattributes/)() | Возвращает квалифицированные атрибуты, которые не принадлежат целевому пространству имён схемы. |
| [set_Id](./set_id/)(const String\&) | Устанавливает строковый идентификатор. |
| [set_Schema](./set_schema/)(const SharedPtr\<XmlSchema\>\&) | Устанавливает [XmlSchema](../xmlschema/) для указанной схемы. |
| [set_SchemaLocation](./set_schemalocation/)(const String\&) | Устанавливает расположение Uniform Resource Identifier (URI) схемы, которое сообщает процессору схем, где схема физически находится. |
| [set_UnhandledAttributes](./set_unhandledattributes/)(const ArrayPtr\<SharedPtr\<XmlAttribute\>\>\&) | Устанавливает квалифицированные атрибуты, которые не принадлежат целевому пространству имён схемы. |
| [XmlSchemaExternal](./xmlschemaexternal/)() | Инициализирует новый экземпляр класса [XmlSchemaExternal](./). |
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
