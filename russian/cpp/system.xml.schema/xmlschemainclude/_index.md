---
title: "System::Xml::Schema::XmlSchemaInclude class"
linktitle: "XmlSchemaInclude"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaInclude class. Представляет элемент include из XML Schema, определённый World Wide Web Consortium (W3C). Этот класс используется для включения объявлений и определений из внешней схемы. Включённые объявления и определения затем доступны для обработки в содержащей схеме в C++."
type: docs
weight: 3600
url: /ru/cpp/system.xml.schema/xmlschemainclude/
---
## XmlSchemaInclude class


Представляет элемент **include** из XML [Schema](../), определённый World Wide [Web](../../system.web/) Consortium (W3C). Этот класс используется для включения объявлений и определений из внешней схемы. Включённые объявления и определения затем доступны для обработки в содержащей схеме.

```cpp
class XmlSchemaInclude : public System::Xml::Schema::XmlSchemaExternal
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Annotation](./get_annotation/)() | Возвращает значение **annotation**. |
| [set_Annotation](./set_annotation/)(const SharedPtr\<XmlSchemaAnnotation\>\&) | Устанавливает значение **annotation**. |
| [XmlSchemaInclude](./xmlschemainclude/)() | Инициализирует новый экземпляр класса [XmlSchemaInclude](./). |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [XmlSchemaExternal](../xmlschemaexternal/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
