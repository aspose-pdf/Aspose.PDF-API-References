---
title: "System::Xml::Schema::XmlSchemaInference класс"
linktitle: "XmlSchemaInference"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaInference класс. Выводит схему XML Schema Definition Language (XSD) из XML‑документа. Класс XmlSchemaInference нельзя наследовать в C++."
type: docs
weight: 3700
url: /ru/cpp/system.xml.schema/xmlschemainference/
---
## XmlSchemaInference class


Выводит XML [Schema](../) Definition Language (XSD) схему из XML‑документа. Класс [XmlSchemaInference](./) нельзя наследовать.

```cpp
class XmlSchemaInference : public System::Object
```

## Enums

| Перечисление | Описание |
| --- | --- |
| [InferenceOption](./inferenceoption/) | Влияет на информацию о вхождениях и типах, выводимую классом [XmlSchemaInference](./) для элементов и атрибутов в XML‑документе. |
## Методы

| Метод | Описание |
| --- | --- |
| [get_Occurrence](./get_occurrence/)() | Возвращает значение [XmlSchemaInference::InferenceOption](./inferenceoption/), которое влияет на декларации вхождений схемы, выводимые из XML‑документа. |
| [get_TypeInference](./get_typeinference/)() | Возвращает значение [XmlSchemaInference::InferenceOption](./inferenceoption/), которое влияет на типы, выводимые из XML‑документа. |
| [InferSchema](./inferschema/)(const SharedPtr\<XmlReader\>\&) | Выводит XML [Schema](../) Definition Language (XSD) схему из XML‑документа, содержащегося в указанном объекте [XmlReader](../../system.xml/xmlreader/). |
| [InferSchema](./inferschema/)(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlSchemaSet\>) | Выводит XML [Schema](../) Definition Language (XSD) схему из XML‑документа, содержащегося в указанном объекте [XmlReader](../../system.xml/xmlreader/), и уточняет полученную схему, используя существующую схему в указанном объекте [XmlSchemaSet](../xmlschemaset/) с тем же целевым пространством имён. |
| [set_Occurrence](./set_occurrence/)(XmlSchemaInference::InferenceOption) | Устанавливает значение [XmlSchemaInference::InferenceOption](./inferenceoption/), которое влияет на декларации вхождений схемы, выводимые из XML‑документа. |
| [set_TypeInference](./set_typeinference/)(XmlSchemaInference::InferenceOption) | Устанавливает значение [XmlSchemaInference::InferenceOption](./inferenceoption/), которое влияет на типы, выводимые из XML‑документа. |
| [XmlSchemaInference](./xmlschemainference/)() | Инициализирует новый экземпляр класса [XmlSchemaInference](./). |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [Object](../../system/object/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
