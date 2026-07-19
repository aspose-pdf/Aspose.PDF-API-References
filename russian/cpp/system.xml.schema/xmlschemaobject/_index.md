---
title: "System::Xml::Schema::XmlSchemaObject класс"
linktitle: "XmlSchemaObject"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaObject класс. Представляет корневой класс для иерархии модели объектов Xml схемы и служит базовым классом для таких классов, как класс XmlSchema на C++."
type: docs
weight: 5000
url: /ru/cpp/system.xml.schema/xmlschemaobject/
---
## XmlSchemaObject class


Представляет корневой класс для иерархии модели объектов схемы [Xml](../../system.xml/) и служит базовым классом для таких классов, как класс [XmlSchema](../xmlschema/).

```cpp
class XmlSchemaObject : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_LineNumber](./get_linenumber/)() | Возвращает номер строки в файле, к которому относится элемент **schema**. |
| [get_LinePosition](./get_lineposition/)() | Возвращает позицию строки в файле, к которой относится элемент **schema**. |
| [get_Namespaces](./get_namespaces/)() | Возвращает XmlSerializerNamespaces, которые следует использовать с этим объектом схемы. |
| [get_Parent](./get_parent/)() | Возвращает родителя этого [XmlSchemaObject](./). |
| [get_SourceUri](./get_sourceuri/)() | Возвращает исходное расположение файла, загрузившего схему. |
| [set_LineNumber](./set_linenumber/)(int32_t) | Устанавливает номер строки в файле, к которой относится элемент **schema**. |
| [set_LinePosition](./set_lineposition/)(int32_t) | Устанавливает позицию строки в файле, к которой относится элемент **schema**. |
| [set_Namespaces](./set_namespaces/)(const SharedPtr\<System::Xml::Serialization::XmlSerializerNamespaces\>\&) | Устанавливает XmlSerializerNamespaces, которые следует использовать с этим объектом схемы. |
| [set_Parent](./set_parent/)(const SharedPtr\<XmlSchemaObject\>\&) | Устанавливает родителя для этого [XmlSchemaObject](./). |
| [set_SourceUri](./set_sourceuri/)(const String\&) | Устанавливает исходное расположение файла, загрузившего схему. |
| [XmlSchemaObject](./xmlschemaobject/)() | Инициализирует новый экземпляр класса [XmlSchemaObject](./). |
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
