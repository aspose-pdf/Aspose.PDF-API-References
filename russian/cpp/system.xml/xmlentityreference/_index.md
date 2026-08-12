---
title: "Класс System::Xml::XmlEntityReference"
linktitle: "XmlEntityReference"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlEntityReference класс. Представляет узел ссылки на сущность в C++."
type: docs
weight: 1900
url: /ru/cpp/system.xml/xmlentityreference/
---
## XmlEntityReference class


Представляет узел ссылки на сущность.

```cpp
class XmlEntityReference : public System::Xml::XmlLinkedNode
```

## Методы

| Метод | Описание |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Создаёт дубликат этого узла. |
| [get_BaseURI](./get_baseuri/)() override | Возвращает базовый Uniform Resource Identifier (URI) текущего узла. |
| [get_IsReadOnly](./get_isreadonly/)() override | Возвращает значение, указывающее, является ли узел только для чтения. |
| [get_LocalName](./get_localname/)() override | Возвращает локальное имя узла. |
| [get_Name](./get_name/)() override | Возвращает имя узла. |
| [get_NodeType](./get_nodetype/)() override | Возвращает тип узла. |
| [get_Value](./get_value/)() override | Возвращает значение узла. |
| [set_Value](./set_value/)(String) override | Устанавливает значение узла. |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Сохраняет всех дочерних узлов узла в указанный [XmlWriter](../xmlwriter/). |
| [WriteTo](./writeto/)(const SharedPtr\<XmlWriter\>\&) override | Сохраняет узел в указанный [XmlWriter](../xmlwriter/). |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [XmlLinkedNode](../xmllinkednode/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
