---
title: "System::Xml::Schema::XmlSchemaImport класс"
linktitle: "XmlSchemaImport"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaImport класс. Представляет элемент import из XML Schema, указанный World Wide Web Consortium (W3C). Этот класс используется для импорта компонентов схемы из других схем в C++."
type: docs
weight: 3500
url: /ru/cpp/system.xml.schema/xmlschemaimport/
---
## XmlSchemaImport class


Представляет элемент **import** из XML [Schema](../), указанный World Wide [Web](../../system.web/) Consortium (W3C). Этот класс используется для импорта компонентов схемы из других схем.

```cpp
class XmlSchemaImport : public System::Xml::Schema::XmlSchemaExternal
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Annotation](./get_annotation/)() | Возвращает значение **annotation**. |
| [get_Namespace](./get_namespace/)() | Возвращает целевое пространство имён импортируемой схемы в виде ссылки Uniform Resource Identifier (URI). |
| [set_Annotation](./set_annotation/)(const SharedPtr\<XmlSchemaAnnotation\>\&) | Устанавливает значение **annotation**. |
| [set_Namespace](./set_namespace/)(const String\&) | Устанавливает целевое пространство имён импортируемой схемы в виде ссылки Uniform Resource Identifier (URI). |
| [XmlSchemaImport](./xmlschemaimport/)() | Инициализирует новый экземпляр класса [XmlSchemaImport](./). |
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
