---
title: "System::Xml::Schema::XmlSchemaSequence класс"
linktitle: "XmlSchemaSequence"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaSequence класс. Представляет элемент последовательности (композитор) из XML Schema, как указано World Wide Web Consortium (W3C). Последовательность требует, чтобы элементы в группе появлялись в указанном порядке внутри содержащего элемента в C++."
type: docs
weight: 5700
url: /ru/cpp/system.xml.schema/xmlschemasequence/
---
## XmlSchemaSequence class


Представляет элемент **sequence** (композитор) из XML [Schema](../), как указано World Wide [Web](../../system.web/) Consortium (W3C). Элемент **sequence** требует, чтобы элементы в группе появлялись в указанном порядке внутри содержащего элемента.

```cpp
class XmlSchemaSequence : public System::Xml::Schema::XmlSchemaGroupBase
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Items](./get_items/)() override | Элементы, содержащиеся в композиторе. Коллекция [XmlSchemaElement](../xmlschemaelement/), [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaSequence](./) или [XmlSchemaAny](../xmlschemaany/). |
| [XmlSchemaSequence](./xmlschemasequence/)() | Инициализирует новый экземпляр класса [XmlSchemaSequence](./). |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [XmlSchemaGroupBase](../xmlschemagroupbase/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
