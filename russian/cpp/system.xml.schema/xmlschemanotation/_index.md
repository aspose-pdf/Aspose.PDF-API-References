---
title: "System::Xml::Schema::XmlSchemaNotation class"
linktitle: "XmlSchemaNotation"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaNotation класс. Представляет элемент notation из XML Schema, как указано World Wide Web Consortium (W3C). Объявление XML Schemanotation является реконструкцией объявлений XML 1.0 NOTATION. Цель нотций — описать формат данных, не являющихся XML, внутри XML‑документа на C++."
type: docs
weight: 4800
url: /ru/cpp/system.xml.schema/xmlschemanotation/
---
## XmlSchemaNotation class


Представляет элемент **notation** из XML [Schema](../) согласно World Wide [Web](../../system.web/) Consortium (W3C). Объявление XML [Schema](../)**notation** является реконструкцией объявлений **XML** 1.0 NOTATION. Цель нотций — описать формат данных, не являющихся XML, внутри XML‑документа.

```cpp
class XmlSchemaNotation : public System::Xml::Schema::XmlSchemaAnnotated
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Name](./get_name/)() | Возвращает имя нотции. |
| [get_Public](./get_public/)() | Возвращает **public** идентификатор. |
| [get_System](./get_system/)() | Возвращает **system** идентификатор. |
| [set_Name](./set_name/)(const String\&) | Устанавливает имя нотции. |
| [set_Public](./set_public/)(const String\&) | Устанавливает **public** идентификатор. |
| [set_System](./set_system/)(const String\&) | Устанавливает **system** идентификатор. |
| [XmlSchemaNotation](./xmlschemanotation/)() | Инициализирует новый экземпляр класса [XmlSchemaNotation](./). |
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
