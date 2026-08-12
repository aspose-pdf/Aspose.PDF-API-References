---
title: "System::Xml::Schema::XmlSchemaFacet class"
linktitle: "XmlSchemaFacet"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaFacet class. Базовый класс для всех фасетов, используемых при выводе простых типов посредством ограничения в C++."
type: docs
weight: 2900
url: /ru/cpp/system.xml.schema/xmlschemafacet/
---
## XmlSchemaFacet class


Базовый класс для всех фасетов, используемых при выводе простых типов посредством ограничения.

```cpp
class XmlSchemaFacet : public System::Xml::Schema::XmlSchemaAnnotated
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [get_IsFixed](./get_isfixed/)() | Возвращает информацию, указывающую, что этот фасет фиксирован. |
| [get_Value](./get_value/)() | Возвращает атрибут **value** фасета. |
| virtual [set_IsFixed](./set_isfixed/)(bool) | Устанавливает информацию, указывающую, что этот фасет фиксирован. |
| [set_Value](./set_value/)(const String\&) | Устанавливает атрибут **value** фасета. |
| [XmlSchemaFacet](./xmlschemafacet/)() | Инициализирует новый экземпляр класса [XmlSchemaFacet](./). |
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
