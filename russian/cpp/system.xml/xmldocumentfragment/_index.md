---
title: "System::Xml::XmlDocumentFragment класс"
linktitle: "XmlDocumentFragment"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlDocumentFragment класс. Представляет лёгкий объект, полезный для операций вставки в дерево в C++."
type: docs
weight: 1500
url: /ru/cpp/system.xml/xmldocumentfragment/
---
## XmlDocumentFragment class


Представляет лёгкий объект, полезный для операций вставки в дерево.

```cpp
class XmlDocumentFragment : public System::Xml::XmlNode
```

## Методы

| Метод | Описание |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Создаёт дубликат этого узла. |
| [get_InnerXml](./get_innerxml/)() override | Возвращает разметку, представляющую дочерние элементы этого узла. |
| [get_LocalName](./get_localname/)() override | Возвращает локальное имя узла. |
| [get_Name](./get_name/)() override | Возвращает квалифицированное имя узла. |
| [get_NodeType](./get_nodetype/)() override | Возвращает тип текущего узла. |
| [get_OwnerDocument](./get_ownerdocument/)() override | Возвращает [XmlDocument](../xmldocument/), к которому принадлежит этот узел. |
| [set_InnerXml](./set_innerxml/)(String) override | Устанавливает разметку, представляющую дочерние элементы этого узла. |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Сохраняет всех дочерних узлов узла в указанный [XmlWriter](../xmlwriter/). |
| [WriteTo](./writeto/)(const SharedPtr\<XmlWriter\>\&) override | Сохраняет узел в указанный [XmlWriter](../xmlwriter/). |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [XmlNode](../xmlnode/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
